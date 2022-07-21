# sap-graph (SAP Graph)

SAP Graph is a new unified API for SAP, using modern open standards like OData v4. With SAP Graph, developers access SAP-managed business data as a single semantically connected data graph, spanning the suite of SAP products. Targeting SAP's ecosystem of developers and customers, SAP Graph's one API and Business Data Graph reduce the cost and complexity of creating and deploying reusable extension applications. The unified API exposes a unified graph-like model of business objects (entities) and relationships. As a BTP service, SAP Graph is compatible with SAP Cloud Application Programming (CAP) extension solutions, events managed via SAP Event Mesh, and No-Code/Low-Code applications like SAP AppGyver. SAP Graph uses open standards, such as OData v.4 and OAuth, thus allowing you to easily build applications and extensions for the SAP Intelligent Enterprise.

## Additional details
- Service category: **SERVICE**
- Supported environments: **cloudfoundry**, **kymaruntime**, **sapbtp**

- [Documentation](https://graph.sap/docs/beta/)
- [Discovery Center](https://discovery-center.cloud.sap/#/serviceCatalog/sap-graph)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)
- [Documentation](https://explore.dev.graph.sap/docs/beta)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  free  |  Free  | eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |

## Sample configuration of **SAP Graph** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **sap-graph** by configuring your `usecase.json` file.

### Using the service plan **free** (Free)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "sap-graph",
      "plan": "free"
    }
  ]
}
```
