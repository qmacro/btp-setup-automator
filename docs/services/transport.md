# **transport** (Cloud Transport Management)

Service category: **SERVICE**

SAP Cloud Transport Management service lets you manage software deliverables between accounts of different environments (such as Neo and Cloud Foundry), by transporting them across various runtimes. This includes application artifacts as well as their respective application-specific content.

## Additional details

- [Documentation](https://help.sap.com/viewer/p/TRANSPORT_MANAGEMENT_SERVICE)
- [Buy Now](https://www.sapstore.com/solutions/40168/SAP-Cloud-Platform-Transport-Management)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/cloud-transport-management)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> br10 - Brazil (Sao Paulo)<br> jp10 - Japan (Tokyo)<br> ap11 - Singapore<br> ca10 - Canada (Montreal)<br> ap10 - Australia (Sydney)<br> us21 - US East (VA)<br> ap21 - Singapore<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Cloud Transport Management** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **transport** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "transport",
      "plan": "standard"
    }
  ]
}
```
