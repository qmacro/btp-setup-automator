# dataenrichment-business-partner (Data Enrichment)

Service category: **SERVICE**

Industrializes the use of third-party data for enterprise applications, and makes it economical to find, procure and consume relevant datasets in timely fashion. Offers pre-built integrations with SAP S/4HANA Cloud and on-premise, and SAP Master Data Governance. Centrally links data from external data providers such as Dun & Bradstreet and CDQ into SAP enterprise applications, reducing overall TCO for data brokerage needs. Data Enrichment will be a one stop shop for multiple data augmentation needs.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/Cloud_Platform_Data_Enrichment/latest/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/data-enrichment)
- [Support](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5dd739823b824b539eee47b7860a00be.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  default  |  default  | ap11 - Singapore<br> eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |

## Sample configuration of **Data Enrichment** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **dataenrichment-business-partner** by configuring your `usecase.json` file.

### Using the service plan **default**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "dataenrichment-business-partner",
      "plan": "default"
    }
  ]
}
```
