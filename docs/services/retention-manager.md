# **retention-manager** (Data Retention Manager)

Service category: **SERVICE**

The SAP Cloud Platform Data Retention Manager lets you block or delete personal data based on the residence and retention rules maintained.

## Additional details

- [Documentation](https://help.sap.com/viewer/p/DATA_RETENTION_MANAGER)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/sap-data-retention-manager)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  free  |  free  | us30 - US Central (IA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us10 - US East (VA)<br> eu20 - Europe (Netherlands)<br> ap10 - Australia (Sydney)<br> us21 - US East (VA)<br> us20 - US West (WA)<br> eu10 - Europe (Frankfurt)<br> ap11 - Singapore  |
|  standard  |  standard  | us30 - US Central (IA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Data Retention Manager** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **retention-manager** by configuring your `usecase.json` file.

### Using the service plan **free**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "retention-manager",
      "plan": "free"
    }
  ]
}
```

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "retention-manager",
      "plan": "standard"
    }
  ]
}
```
