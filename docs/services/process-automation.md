# process-automation (SAP Process Automation)

SAP Process Automation is a citizen development solution to adapt, improve, and innovate business processes with the low-code/no-code capabilities of SAP Workflow Management and SAP Intelligent RPA.

## Additional details
- Service category: APPLICATION
- Supported environments: tbd

- [Documentation](https://help.sap.com/viewer/p/PROCESS_AUTOMATION)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  Standard  | ap10 - Australia (Sydney)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |
|  free  |  Free  | ap10 - Australia (Sydney)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |

## Sample configuration of **SAP Process Automation** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **process-automation** by configuring your `usecase.json` file.

### Using the service plan **standard** (Standard)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "process-automation",
      "plan": "standard"
    }
  ]
}
```

### Using the service plan **free** (Free)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "process-automation",
      "plan": "free"
    }
  ]
}
```
