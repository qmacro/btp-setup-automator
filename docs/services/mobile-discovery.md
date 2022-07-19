# **mobile-discovery** (Mobile Discovery)

Service category: **SERVICE**

Mobile Discovery

## Additional details

- [Documentation](https://help.sap.com/viewer/468990a67780424a9e66eb096d4345bb/Cloud/en-US/063c131a022e4432ae4f21022c90a178.html)
- [Support information](https://mobile-service-cockpit-web.cfapps.us10.hana.ondemand.com)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  Mobile Discovery service stores and facilitates retrieval of application configuration data  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> br10 - Brazil (Sao Paulo)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |

## Sample configuration of **Mobile Discovery** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **mobile-discovery** by configuring your `usecase.json` file.

### Using the service plan **standard** (Mobile Discovery service stores and facilitates retrieval of application configuration data)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "mobile-discovery",
      "plan": "standard"
    }
  ]
}
```
