# **sap-workzone** (SAP Work Zone)

Service category: **SERVICE**

SAP Work Zone centralizes access to relevant business applications, processes, information, and communication in a unified entry point that users can access from any device.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/WZ/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/sap-work-zone)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | eu30 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> ap11 - Singapore<br> jp20 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> ap21 - Singapore<br> us20 - US West (WA)<br> eu10 - Europe (Frankfurt)<br> us10 - US East (VA)<br> us30 - US Central (IA)<br> us21 - US East (VA)<br> ca10 - Canada (Montreal)  |

## Sample configuration of **SAP Work Zone** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **sap-workzone** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "sap-workzone",
      "plan": "standard"
    }
  ]
}
```
