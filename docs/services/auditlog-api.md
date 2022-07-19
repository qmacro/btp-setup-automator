# **auditlog-api** (Audit Log Service API)

Service category: **SERVICE**

SAP Audit Log service API

## Additional details

- [Documentation](https://help.sap.com/products/BTP/65de2977205c403bbc107264b8eccf4b/f92c86ab11f6474ea5579d839051c334.html)
- [Discovery Center](https://discovery-center.cloud.sap/#/serviceCatalog/audit-log-service)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  default  |  default  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> br10 - Brazil (Sao Paulo)<br> us30 - US Central (IA)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Audit Log Service API** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **auditlog-api** by configuring your `usecase.json` file.

### Using the service plan **default**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "auditlog-api",
      "plan": "default"
    }
  ]
}
```
