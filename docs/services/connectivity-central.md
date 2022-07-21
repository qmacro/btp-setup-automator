# connectivity-central (Connectivity (for scale-out build-out))

Connectivity (for scale-out build-out)

## Additional details
- Service category: SERVICE
- Supported environments: cloudfoundry, kymaruntime, sapbtp

- [Documentation](https://help.sap.com/viewer/cca91383641e40ffbe03bdc78f00f681/Cloud/en-US/34010ace6ac84574a4ad02f5055d3597.html)
- [Support information](https://help.sap.com/viewer/cca91383641e40ffbe03bdc78f00f681/Cloud/en-US/e5580c5dbb5710149e53c6013301a9f2.html)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  connectivity_proxy  |  Pair Connectivity Proxy with SAP CP Connectivity service for establishing secure connections to on-premise systems through SAP Cloud Connector  | eu10 - Europe (Frankfurt)  |

## Sample configuration of **Connectivity (for scale-out build-out)** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **connectivity-central** by configuring your `usecase.json` file.

### Using the service plan **connectivity_proxy** (Pair Connectivity Proxy with SAP CP Connectivity service for establishing secure connections to on-premise systems through SAP Cloud Connector)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "connectivity-central",
      "plan": "connectivity_proxy"
    }
  ]
}
```
