# data-attribute-recommendation (Data Attribute Recommendation)

Data Attribute Recommendation uses free text, numbers and categories as input to classify entities such as products, stores and users into multiple classes and also to predict the value of missing numerical attributes in your data records. You can use Data Attribute Recommendation, for example, to classify incoming product information and predict the price of commodities based on their description.

## Additional details
- Service category: SERVICE
- Supported environments: **cloudfoundry*, **kymaruntime*, **sapbtp*

- [Documentation](https://help.sap.com/dar)
- [Support](https://help.sap.com/viewer/105bcfd88921418e8c29b24a7a402ec3/SHIP/en-US/4fb850f57a7848cab74f180c129c0b86.html)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/data-attribute-recommendation)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |
|  free  |  free  | eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |

## Sample configuration of **Data Attribute Recommendation** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **data-attribute-recommendation** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "data-attribute-recommendation",
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
      "name": "data-attribute-recommendation",
      "plan": "free"
    }
  ]
}
```
