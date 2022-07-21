# data-intelligence (SAP Data Intelligence)

SAP Data Intelligence is the all-in-one data orchestration solution to discover, refine, enriche and govern any type, variety, and volume of data across your entire distributed data landscape. Deliver on the promise of AI with enterprise scale, trust, and transparency driving significant new business value and insights.

## Additional details
- Service category: SERVICE
- Supported environments: **cloudfoundry*

- [Documentation](https://help.sap.com/viewer/product/SAP_DATA_INTELLIGENCE/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/sap-data-intelligence)
- [Support information](https://launchpad.support.sap.com/#/notes/2820555)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  enterprise  |  enterprise  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> eu10 - Europe (Frankfurt)<br> eu20 - Europe (Netherlands)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> us20 - US West (WA)  |
|  dedicated  |  Dedicated  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> eu10 - Europe (Frankfurt)<br> eu20 - Europe (Netherlands)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> us20 - US West (WA)  |
|  tenant  |  Tenant  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> eu10 - Europe (Frankfurt)<br> eu20 - Europe (Netherlands)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> us20 - US West (WA)  |

## Sample configuration of **SAP Data Intelligence** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **data-intelligence** by configuring your `usecase.json` file.

### Using the service plan **enterprise**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "data-intelligence",
      "plan": "enterprise", 
      "parameters" : { 
        "adminPassword": null,
        "adminUsername": null,
        "hibernationSchedules": null,
        "keyRef": null,
        "maxNodes": null,
        "minNodes": null,
        "useCMK": null,
        "vpcCIDR": null
      }
    }
  ]
}
```

### Using the service plan **dedicated** (Dedicated)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "data-intelligence",
      "plan": "dedicated", 
      "parameters" : { 
        "adminPassword": null,
        "adminUsername": null,
        "hibernationSchedules": null,
        "keyRef": null,
        "maxNodes": null,
        "minNodes": null,
        "useCMK": null,
        "vpcCIDR": null
      }
    }
  ]
}
```

### Using the service plan **tenant** (Tenant)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "data-intelligence",
      "plan": "tenant", 
      "parameters" : { 
        "adminPassword": null,
        "adminUsername": null,
        "clusterName": null,
        "resourceQuotas": null,
        "tenantName": null
      }
    }
  ]
}
```
