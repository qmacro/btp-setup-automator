# **mobile-app-update** (Mobile App Update)

Service category: **SERVICE**

Mobile App Update

## Additional details

- [Documentation](https://help.sap.com/viewer/468990a67780424a9e66eb096d4345bb/Cloud/en-US/fb0364cb13b44f84803657a386811f2a.html)
- [Support information](https://mobile-service-cockpit-web.cfapps.us10.hana.ondemand.com)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  Mobile App Update Service is used to update new versions of an App Modeler application  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> br10 - Brazil (Sao Paulo)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |

## Sample configuration of **Mobile App Update** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **mobile-app-update** by configuring your `usecase.json` file.

### Using the service plan **standard** (Mobile App Update Service is used to update new versions of an App Modeler application)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "mobile-app-update",
      "plan": "standard"
    }
  ]
}
```
