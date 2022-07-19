# **process-automation** (SAP Process Automation)

Service category: **APPLICATION**

SAP Process Automation is a citizen development solution to adapt, improve, and innovate business processes with the low-code/no-code capabilities of SAP Workflow Management and SAP Intelligent RPA.

## Additional details

- [Documentation](https://help.sap.com/viewer/p/PROCESS_AUTOMATION)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  automation-unattended  |  automation-unattended  | jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  standard-user  |  standard-user  | jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  standard  |  Standard  | jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  automation-attended  |  automation-attended  | jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  advanced-user  |  advanced-user  | jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  free  |  Free  | jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **SAP Process Automation** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **process-automation** by configuring your `usecase.json` file.

### Using the service plan **automation-unattended**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "process-automation",
      "plan": "automation-unattended"
    }
  ]
}
```

### Using the service plan **standard-user**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "process-automation",
      "plan": "standard-user"
    }
  ]
}
```

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

### Using the service plan **automation-attended**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "process-automation",
      "plan": "automation-attended"
    }
  ]
}
```

### Using the service plan **advanced-user**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "process-automation",
      "plan": "advanced-user"
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
