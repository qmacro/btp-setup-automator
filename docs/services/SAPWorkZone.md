# **SAPWorkZone** (SAP Work Zone)

Service category: **APPLICATION**

SAP Work Zone centralizes access to relevant business applications, processes, information, and communication in a unified entry point that users can access from any device.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/WZ/Cloud/en-US)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  Standard  | jp10 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> ap21 - Singapore<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> br10 - Brazil (Sao Paulo)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us21 - US East (VA)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **SAP Work Zone** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **SAPWorkZone** by configuring your `usecase.json` file.

### Using the service plan **standard** (Standard)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "SAPWorkZone",
      "plan": "standard"
    }
  ]
}
```
