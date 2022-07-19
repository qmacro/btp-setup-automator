# **intercompany-reconciliation** (Intelligent Intercompany Reconciliation)

Service category: **SERVICE**

Intelligent Intercompany Reconciliation is introduced to speed up your intercompany reconciliation process from company close to corporate close. The service is based on Artificial Intelligence in order to reconcile your financial data with high accuracy.

## Additional details

- [Documentation](https://help.sap.com/viewer/0fa84c9d9c634132b7c4abb9ffdd8f06/2108.501/en-US/b0b3b968f7c943c88ebc6e94d114564e.html)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | eu10 - Europe (Frankfurt)  |

## Sample configuration of **Intelligent Intercompany Reconciliation** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **intercompany-reconciliation** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "intercompany-reconciliation",
      "plan": "standard"
    }
  ]
}
```
