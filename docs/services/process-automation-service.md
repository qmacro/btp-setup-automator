# **process-automation-service** (SAP Process Automation)

Service category: **SERVICE**

SAP Process Automation is a citizen development solution to adapt, improve, and innovate business processes with the low-code/no-code capabilities of SAP Workflow Management and SAP Intelligent RPA.

## Additional details

- [Documentation](https://help.sap.com/viewer/p/PROCESS_AUTOMATION)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **SAP Process Automation** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **process-automation-service** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "process-automation-service",
      "plan": "standard"
    }
  ]
}
```
