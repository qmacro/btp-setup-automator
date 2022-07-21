# PersonalDataManagerApp (Personal Data Manager)

SAP Personal Data Manager provides the capability to generate reports showing the personal data stored in an application point of view with the help of a CSR. The reports can be generated and exported either in machine readable form (JSON) or human readable form (PDF). Data subjects can request the correction and deletion of personal data that is stored in an application point of view.

## Additional details
- Service category: APPLICATION


- [Documentation](https://help.sap.com/viewer/product/PERSONAL_DATA_MANAGER/SHIP/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/personal-data-manager)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> ap21 - Singapore<br> eu10 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> us20 - US West (WA)<br> us21 - US East (VA)  |

## Sample configuration of **Personal Data Manager** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **PersonalDataManagerApp** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "PersonalDataManagerApp",
      "plan": "standard"
    }
  ]
}
```
