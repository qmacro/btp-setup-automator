# **personal-data-manager-service** (Personal Data Manager)

Service category: **SERVICE**

SAP Personal Data Manager provides the capability to generate reports showing the personal data stored in an application point of view with the help of a CSR. The reports can be generated and exported either in machine readable form (JSON) or human readable form (PDF). Data subjects can request the correction and deletion of personal data that is stored in an application point of view.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/PERSONAL_DATA_MANAGER/SHIP/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/personal-data-manager)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)
- [Support information](https://help.sap.com/viewer/620a3ea6aaf64610accdd05cca9e3de2/SHIP/en-US/392fff93d1de4d168d320010ddc3b803.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  free  |  free  | us30 - US Central (IA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us20 - US West (WA)<br> us10 - US East (VA)<br> eu20 - Europe (Netherlands)<br> eu10 - Europe (Frankfurt)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us21 - US East (VA)  |
|  standard  |  standard  | us30 - US Central (IA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us21 - US East (VA)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Personal Data Manager** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **personal-data-manager-service** by configuring your `usecase.json` file.

### Using the service plan **free**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "personal-data-manager-service",
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
      "name": "personal-data-manager-service",
      "plan": "standard"
    }
  ]
}
```
