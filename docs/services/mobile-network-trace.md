# mobile-network-trace (Mobile Network Trace)

Service category: **SERVICE**

Mobile Network Trace

## Additional details

- [Documentation](https://help.sap.com/viewer/468990a67780424a9e66eb096d4345bb/Cloud/en-US/25b620d388d743b5880113a0fb1938d0.html)
- [Support information](https://mobile-service-cockpit-web.cfapps.us10.hana.ondemand.com)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  Mobile Network Trace collects network trace information from mobile applications for debugging  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> br10 - Brazil (Sao Paulo)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |

## Sample configuration of **Mobile Network Trace** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **mobile-network-trace** by configuring your `usecase.json` file.

### Using the service plan **standard** (Mobile Network Trace collects network trace information from mobile applications for debugging)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "mobile-network-trace",
      "plan": "standard"
    }
  ]
}
```
