# **auditlog-viewer** (Audit Log Viewer Service)

Service category: **APPLICATION**

SAP Audit Log Viewer service for SAP BTP helps to view and manage audit logs.

## Additional details

- [Documentation](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/e3baa5f1a0c64c44aac8ab3ea3d1b500.html)
- [Discovery Center](https://discovery-center.cloud.sap/#/serviceCatalog/audit-log-service)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  free  |  Audit Log Viewer  | ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> us30 - US Central (IA)<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Audit Log Viewer Service** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **auditlog-viewer** by configuring your `usecase.json` file.

### Using the service plan **free** (Audit Log Viewer)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "auditlog-viewer",
      "plan": "free"
    }
  ]
}
```
