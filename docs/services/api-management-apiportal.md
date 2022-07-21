# api-management-apiportal (API Management, API portal)

API Management technology helps you to share digital assets and enables consumption of these assets in new user interfaces. An API Portal application in SAP API Management helps you grow new revenue streams. You can not only configure and share but also monetize you digital assets, enabling up-sell and cross-sell though your eco-system.

## Additional details
- Service category: APPLICATION
- Supported environments: cloudfoundry, kymaruntime, sapbtp

- [Documentation](https://help.sap.com/viewer/product/SAP_CLOUD_PLATFORM_API_MANAGEMENT)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  API Management-API Portal  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> ap21 - Singapore<br> br10 - Brazil (Sao Paulo)<br> ca10 - Canada (Montreal)<br> eu10 - Europe (Frankfurt)<br> eu20 - Europe (Netherlands)<br> jp10 - Japan (Tokyo)<br> jp20 - Japan (Tokyo)<br> us10 - US East (VA)<br> us20 - US West (WA)<br> us21 - US East (VA)  |

## Sample configuration of **API Management, API portal** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **api-management-apiportal** by configuring your `usecase.json` file.

### Using the service plan **standard** (API Management-API Portal)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "api-management-apiportal",
      "plan": "standard"
    }
  ]
}
```
