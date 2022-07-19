# **cicd-service** (Continuous Integration & Delivery)

Service category: **SERVICE**

SAP Continuous Integration and Delivery lets you configure and run predefined continuous integration and delivery (CI/CD) pipelines that automatically test, build, and deploy your code changes to speed up your development and delivery cycles.

## Additional details

- [Documentation](https://help.sap.com/docs/CONTINUOUS_DELIVERY?version=Cloud)
- [Support](https://help.sap.com/docs/CONTINUOUS_DELIVERY/99c72101f7ee40d0b2deb4df72ba1ad3/6e10ad426e434180a0c62d4e7b6115bc.html)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/continuous-integration--delivery?region=all)
- [Documentation](https://help.sap.com/docs/CONTINUOUS_DELIVERY)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  default  |  default  | us20 - US West (WA)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Continuous Integration & Delivery** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **cicd-service** by configuring your `usecase.json` file.

### Using the service plan **default**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "cicd-service",
      "plan": "default"
    }
  ]
}
```
