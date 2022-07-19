# **extension-center** (Extension Center)

Service category: **APPLICATION**

Allows you to create, manage, configure extensions on SAP Cloud Platform

## Additional details

- [Documentation](https://help.sap.com/viewer/product/XF_SERVERLESS_RUNTIME/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/serverless-runtime)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  Extension Center  | ap12 - South Korea (Seoul)<br> jp10 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Extension Center** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **extension-center** by configuring your `usecase.json` file.

### Using the service plan **standard** (Extension Center)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "extension-center",
      "plan": "standard"
    }
  ]
}
```
