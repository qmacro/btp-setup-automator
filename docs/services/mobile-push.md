# **mobile-push** (Mobile Push Notification)

Service category: **SERVICE**

Mobile Push Notification

## Additional details

- [Documentation](https://help.sap.com/viewer/468990a67780424a9e66eb096d4345bb/Cloud/en-US/82864e6309d84aed9566436b766e63ef.html)
- [Support information](https://mobile-service-cockpit-web.cfapps.us10.hana.ondemand.com)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  Mobile Push Notification Service is used to send out push messages to mobile devices  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> br10 - Brazil (Sao Paulo)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |

## Sample configuration of **Mobile Push Notification** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **mobile-push** by configuring your `usecase.json` file.

### Using the service plan **standard** (Mobile Push Notification Service is used to send out push messages to mobile devices)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "mobile-push",
      "plan": "standard"
    }
  ]
}
```
