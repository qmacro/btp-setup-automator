# **spatialservices** (SAP HANA spatial services)

Service category: **SERVICE**

SAP HANA spatial services provides a unified access layer for location-based services, including maps for visualization, geocoding and routing capabilities. It integrates location-based content and services from external providers into SAP products and customer applications.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/SAP_HANA_SPATIAL_SERVICES/latest/)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/sap-hana-spatial-services)
- [Documentation](https://help.sap.com/viewer/product/SAP_HANA_SPATIAL_SERVICES)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | eu10 - Europe (Frankfurt)  |
|  lite  |  lite  | us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **SAP HANA spatial services** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **spatialservices** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "spatialservices",
      "plan": "standard"
    }
  ]
}
```

### Using the service plan **lite**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "spatialservices",
      "plan": "lite"
    }
  ]
}
```
