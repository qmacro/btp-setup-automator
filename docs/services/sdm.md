# **sdm** (Document Management Service, Integration Option)

Service category: **SERVICE**

Leverage the APIs of SAP Document Management service and build your own document management layer to enable document management capabilities for your business applications. You can also embed the easy-to-use, UI5-based, reusable UI component of Document Management into your application for document management scenarios.

## Additional details

- [Documentation](https://help.sap.com/viewer/p/DOCUMENT_MANAGEMENT)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/document-management-service-integration-option)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | ap20 - Australia (Sydney) Azure<br> us30 - US Central (IA)<br> eu30 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap12 - South Korea (Seoul)<br> ap21 - Singapore<br> ca10 - Canada (Montreal)<br> us21 - US East (VA)<br> jp20 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |
|  free  |  free  | ap20 - Australia (Sydney) Azure<br> us30 - US Central (IA)<br> eu30 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us20 - US West (WA)<br> us10 - US East (VA)<br> us21 - US East (VA)<br> ap12 - South Korea (Seoul)<br> ap21 - Singapore<br> ap11 - Singapore<br> jp10 - Japan (Tokyo)<br> jp20 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> eu10 - Europe (Frankfurt)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap10 - Australia (Sydney)  |

## Sample configuration of **Document Management Service, Integration Option** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **sdm** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "sdm",
      "plan": "standard"
    }
  ]
}
```

### Using the service plan **free**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "sdm",
      "plan": "free"
    }
  ]
}
```
