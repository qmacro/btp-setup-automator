# **SAPLaunchpad** (Launchpad Service)

Service category: **APPLICATION**

SAP Launchpad service provides users with a central point of access to applications from different sources.

## Additional details

- [Documentation](https://help.sap.com/viewer/8c8e1958338140699bd4811b37b82ece/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/launchpad-service)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  free  |  Free  | eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> us20 - US West (WA)<br> us10 - US East (VA)<br> us21 - US East (VA)<br> ap21 - Singapore<br> ap12 - South Korea (Seoul)<br> ap11 - Singapore<br> jp10 - Japan (Tokyo)<br> jp20 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu10 - Europe (Frankfurt)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap10 - Australia (Sydney)  |
|  standard  |  standard  | eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> br10 - Brazil (Sao Paulo)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Launchpad Service** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **SAPLaunchpad** by configuring your `usecase.json` file.

### Using the service plan **free** (Free)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "SAPLaunchpad",
      "plan": "free"
    }
  ]
}
```

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "SAPLaunchpad",
      "plan": "standard"
    }
  ]
}
```
