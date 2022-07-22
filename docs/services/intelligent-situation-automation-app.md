# intelligent-situation-automation-app (Intelligent Situation Automation)

Intelligent Situation Automation is an extension of Situation Handling. It processes situations raised and resolves them automatically using business rules, thus reducing the time users spend on routine manual and repetitive tasks.

## Additional details
- Service category: APPLICATION
- Supported environments: N/A

- [Documentation](https://help.sap.com/viewer/product/INTELLIGENT_SITUATION_AUT/1.0/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/intelligent-situation-automation)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  free  |  Free  | eu10 - Europe (Frankfurt)  |
|  standard  |  standard  | eu10 - Europe (Frankfurt)  |
|  beta  |  Beta  | eu10 - Europe (Frankfurt)  |

## Sample configuration of **Intelligent Situation Automation** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **intelligent-situation-automation-app** by configuring your `usecase.json` file.

### Using the service plan **free** (Free)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "intelligent-situation-automation-app",
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
      "category": "APPLICATION",
      "name": "intelligent-situation-automation-app",
      "plan": "standard"
    }
  ]
}
```

### Using the service plan **beta** (Beta)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "intelligent-situation-automation-app",
      "plan": "beta"
    }
  ]
}
```
