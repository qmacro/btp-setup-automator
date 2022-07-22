# dq-services (Data Quality Services)

SAP Data Quality Management offers cloud-based services that let you embed address cleansing, geocoding, and reverse geocoding within any business process orapplication,so that you can reap the value of complete and accurate address data.

## Additional details
- Service category: SERVICE
- Supported environments: cloudfoundry, kymaruntime, sapbtp

- [$18n{applicationCoordinates.serviceDescription.title_documentation}](https://help.sap.com/viewer/d95546360fea44988eb614718ff7e959/Cloud/en-US)
- [License Terms](https://www.sap.com/about/trust-center/agreements/on-premise/product-use-and-support-terms.html?tag=agreements:product-use-support-terms/on-premise-software/software-use-rights/)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/sap-data-quality-management)
- [Documentation](https://help.sap.com/viewer/d95546360fea44988eb614718ff7e959/Cloud/)
- [Support information](https://help.sap.com/viewer/d95546360fea44988eb614718ff7e959/Cloud/en-US/746b418f655840179a99cbdf9073324f.html)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | eu10 - Europe (Frankfurt)  |
|  free  |  free  | eu10 - Europe (Frankfurt)  |

## Sample configuration of **Data Quality Services** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **dq-services** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "dq-services",
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
      "name": "dq-services",
      "plan": "free"
    }
  ]
}
```
