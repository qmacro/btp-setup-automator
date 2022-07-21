# eadesigner (SAP EA Designer, cloud edition)

SAP Enterprise Architecture Designer, Cloud Edition (SAP EA Designer) lets you capture, analyze, and present your organization's landscapes, strategies, requirements, processes, data, and other artifacts in a shared environment. Using industry-standard notations and techniques, organizations can leverage rich metadata and use models and diagrams to drive understanding and promote shared outcomes in creating innovative systems, information sets, and processes to support goals and capabilities.

## Additional details
- Service category: APPLICATION
- Supported environments: cloudfoundry, kymaruntime, sapbtp

- [Documentation](https://help.sap.com/viewer/product/EAD_CLOUD/Cloud/en-US)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  eadesigner  |  SAP Enterprise Architecture Designer, cloud edition  | eu10 - Europe (Frankfurt)  |

## Sample configuration of **SAP EA Designer, cloud edition** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **eadesigner** by configuring your `usecase.json` file.

### Using the service plan **eadesigner** (SAP Enterprise Architecture Designer, cloud edition)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "eadesigner",
      "plan": "eadesigner"
    }
  ]
}
```
