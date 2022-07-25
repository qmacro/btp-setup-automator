# data-privacy-integration-service (Data Privacy Integration)

Data Privacy Integration (DPI) is a service that supports applications realize their data privacy functions i.e Business Purpose Management ( Ensure Data is processed in a compliant manner based on valid Business Purpose ), Data Deletion and Retrieval of personal data. Applications that are part of an end to end business process can integrate with DPI to provide a centralized management of data privacy.

## Additional details
- Service category: SERVICE
- Supported environments: cloudfoundry, kymaruntime, sapcp

- [Documentation](https://help.sap.com/viewer/product/DATA_PRIVACY_INTEGRATION/SHIP/en-US)
- [Support](https://help.sap.com/viewer/313a456d8f6c47289945699fbf5ab0c6/DEV/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/data-privacy-integration)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)
- [Documentation](https://help.sap.com/viewer/product/DATA_PRIV_INTEGRATION_OD/SHIP/en-US)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  free  |  free  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> ap21 - Singapore<br> eu10 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu20 - Europe (Netherlands)<br> jp20 - Japan (Tokyo)<br> us10 - US East (VA)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> us30 - US Central (IA)  |
|  application  |  application  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> ap21 - Singapore<br> eu10 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu20 - Europe (Netherlands)<br> jp20 - Japan (Tokyo)<br> us10 - US East (VA)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> us30 - US Central (IA)  |

## Sample configuration of **Data Privacy Integration** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **data-privacy-integration-service** by configuring your `usecase.json` file.

### Using the service plan **free**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "data-privacy-integration-service",
      "plan": "free"
    }
  ]
}
```

### Using the service plan **application**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "data-privacy-integration-service",
      "plan": "application"
    }
  ]
}
```
