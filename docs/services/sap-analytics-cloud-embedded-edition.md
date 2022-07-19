# **sap-analytics-cloud-embedded-edition** (SAP Analytics Cloud, embedded edition)

Service category: **SERVICE**

With SAP Analytics Cloud, embedded edition, you can build and embed reports, dashboards, and visuals into your business application to make confident decisions. Explore your business data via live connection between your SAP Analytics Cloud tenant and the remote SAP HANA database on SAP Cloud Platform.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/SAC_EMBEDDED_EDITION/1.0/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/sap-analytics-cloud-embedded-edition)
- [Support information](https://help.sap.com/viewer/7466893ec68641198fc189757dc5f7a6/1.0/en-US/ce081403aaf14feca286d7d0b4af2b86.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> ap12 - South Korea (Seoul)<br> br10 - Brazil (Sao Paulo)<br> ca10 - Canada (Montreal)<br> eu10 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu20 - Europe (Netherlands)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |

## Sample configuration of **SAP Analytics Cloud, embedded edition** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **sap-analytics-cloud-embedded-edition** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "sap-analytics-cloud-embedded-edition",
      "plan": "standard"
    }
  ]
}
```
