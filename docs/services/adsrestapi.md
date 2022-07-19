# **adsrestapi** (Forms Service by Adobe API)

Service category: **SERVICE**

SAP Forms service by Adobe lets you generate print and interactive forms using Adobe Document Services (ADS). Call the service from your application using a REST API for rendering documents and for managing form templates in the template store. Configure ADS and access the template store via service-offered UIs. To use Forms service by Adobe, you must subscribe to the application (ads-configui) and set entitlements to both, the ADS (ads) and the REST API template store (adsrestapi) service. In the Service Marketplace, find all two tiles easily by entering 'adobe' into the search field.

## Additional details

- [Documentation](https://help.sap.com/viewer/dcbea777ceb3411cb10500a1a392273e/Cloud/en-US/661c02ef20d54bfeb309d42608baeaca.html)
- [Discovery Center](https://discovery-center.cloud.sap/protected/index.html#/serviceCatalog/forms-service-by-adobe)
- [Documentation](https://adsrestapi-formsprocessing.cfapps.us10.hana.ondemand.com/swagger-ui.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  Standard  | eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |

## Sample configuration of **Forms Service by Adobe API** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **adsrestapi** by configuring your `usecase.json` file.

### Using the service plan **standard** (Standard)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "adsrestapi",
      "plan": "standard"
    }
  ]
}
```
