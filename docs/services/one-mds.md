# **one-mds** (Master Data Integration)

Service category: **SERVICE**

SAP Business Technology Platform Master Data Integration service offers master data synchronization across SAP solutions and is a central access layer for data sharing and distribution. The service can only be used for SAP to SAP Integration, and must not be directly accessed for 3rd party master data integration scenarios with SAP. SAP Business Technology Platform Master Data Orchestration is part of the master data integration service, and can only be used in conjunction with SAP Master Data Integration service.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/SAP_MASTER_DATA_INTEGRATION/CLOUD/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/#/serviceCatalog/master-data-integration?region=all)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  sap-integration  |  sap-integration  | ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  s4hana-onpremise  |  s4hana-onpremise  | ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Master Data Integration** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **one-mds** by configuring your `usecase.json` file.

### Using the service plan **sap-integration**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "one-mds",
      "plan": "sap-integration", 
      "parameters" : { 
        "application": null,
        "businessSystemId": null,
        "enableTenantDeletion": false,
        "writePermissions": null
      }
    }
  ]
}
```

### Using the service plan **s4hana-onpremise**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "one-mds",
      "plan": "s4hana-onpremise", 
      "parameters" : { 
        "businessSystemId": null,
        "enableTenantDeletion": false,
        "writePermissions": null
      }
    }
  ]
}
```
