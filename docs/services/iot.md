# iot (Internet of Things)

The SAP Cloud Platform Internet of Things service for the Cloud Foundry environment connects devices to SAP Cloud Platform to provide scalable ingestion of IoT data and device management. The respective services provide a secure connection to remote devices using a broad variety of IoT protocols and manage the device lifecycle from onboarding to decommissioning. 

## Additional details
- Service category: **SERVICE**
- Supported environments: **cloudfoundry**

- [Documentation](https://help.sap.com/viewer/product/SAP_CP_IOT_CF/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/sap-iot)
- [Documentation](https://help.sap.com/viewer/p/SAP_CP_IOT_CF)
- [Support information](https://help.sap.com/viewer/ccc9cfa0ae70491ab359e5a414f9a1d9/Cloud)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |

## Sample configuration of **Internet of Things** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **iot** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "iot",
      "plan": "standard"
    }
  ]
}
```
