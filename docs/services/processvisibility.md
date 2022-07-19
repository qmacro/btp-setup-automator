# **processvisibility** (Process Visibility)

Service category: **SERVICE**

Provides end-to-end visibility into processes that run in cloud, on-premise & in hybrid environments

## Additional details

- [Documentation](https://help.sap.com/viewer/product/VISIBILITY_SERVICE/Cloud/en-US)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | ca10 - Canada (Montreal)<br> ap12 - South Korea (Seoul)<br> br10 - Brazil (Sao Paulo)<br> ap21 - Singapore<br> us21 - US East (VA)<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  workflow  |  workflow  | eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap12 - South Korea (Seoul)<br> us21 - US East (VA)<br> us20 - US West (WA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> br10 - Brazil (Sao Paulo)<br> us10 - US East (VA)<br> ca10 - Canada (Montreal)<br> jp10 - Japan (Tokyo)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Process Visibility** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **processvisibility** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "processvisibility",
      "plan": "standard"
    }
  ]
}
```

### Using the service plan **workflow**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "processvisibility",
      "plan": "workflow"
    }
  ]
}
```
