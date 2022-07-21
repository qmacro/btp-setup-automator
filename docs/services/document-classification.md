# document-classification (Document Classification)

Document Classification helps you to automate the management and processing of large amounts of business documents by applying machine learning. Based on customer specific classification models, Document Classification can be utilized in a wide range of business scenarios and adapted to special requirements. Document Classification is targeting organizations and business units struggling with the fast, economic, high quality and efficient processing of documents used in critical business processes like Enterprise Mail-Inbox Processing, Contract Management or Invoice Processing.

## Additional details
- Service category: **SERVICE**
- Supported environments: **cloudfoundry**, **kymaruntime**, **sapbtp**

- [Documentation](https://help.sap.com/dc)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/document-classification)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  blocks_of_100  |  blocks_of_100  | eu10 - Europe (Frankfurt)  |
|  default  |  default  | eu10 - Europe (Frankfurt)  |

## Sample configuration of **Document Classification** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **document-classification** by configuring your `usecase.json` file.

### Using the service plan **blocks_of_100**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "document-classification",
      "plan": "blocks_of_100"
    }
  ]
}
```

### Using the service plan **default**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "document-classification",
      "plan": "default"
    }
  ]
}
```
