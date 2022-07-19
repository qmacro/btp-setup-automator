# **it-rt** (Process Integration Runtime)

Service category: **SERVICE**

Provides access to SAP Cloud Platform Integration runtime (integration flows) and APIs.

## Additional details

- [Documentation](https://cloudintegration.hana.ondemand.com/PI/help)
- [Support](https://cloudintegration.hana.ondemand.com/PI/help)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  api  |  api  | ap20 - Australia (Sydney) Azure<br> us30 - US Central (IA)<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> jp20 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> ap21 - Singapore<br> ap10 - Australia (Sydney)<br> br10 - Brazil (Sao Paulo)<br> eu20 - Europe (Netherlands)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> ap11 - Singapore  |
|  integration-flow  |  integration-flow  | ap20 - Australia (Sydney) Azure<br> us30 - US Central (IA)<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap21 - Singapore<br> br10 - Brazil (Sao Paulo)<br> jp20 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> us20 - US West (WA)<br> jp10 - Japan (Tokyo)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Process Integration Runtime** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **it-rt** by configuring your `usecase.json` file.

### Using the service plan **api**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "it-rt",
      "plan": "api", 
      "parameters" : { 
        "grant-types": ["client_credentials"],
        "redirect-uris": [],
        "roles": null
      }
    }
  ]
}
```

### Using the service plan **integration-flow**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "it-rt",
      "plan": "integration-flow", 
      "parameters" : { 
        "grant-types": ["client_credentials"],
        "redirect-uris": [],
        "roles": ["ESBMessaging.send"]
      }
    }
  ]
}
```
