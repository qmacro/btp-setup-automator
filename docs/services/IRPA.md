# **IRPA** (SAP Intelligent Robotic Process Automation)

Service category: **APPLICATION**

SAP Intelligent Robotic Process Automation lets you automate enterprise business processes. Design process automations with the Desktop Studio by creating end-to-end scenarios. Import these scenarios into the cloud Factory to configure and execute them with Agents. An Agent can work as a Digital Assistant (attended automation) or as a Digital Worker (unattended automation).

## Additional details

- [Documentation](https://help.sap.com/viewer/p/IRPA)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/sap-intelligent-rpa)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  default  |  SAP Intelligent Robotic Process Automation  | us10 - US East (VA)<br> jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> eu10 - Europe (Frankfurt)  |
|  free  |  Free  | ap11 - Singapore<br> us10 - US East (VA)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)  |
|  concurrent-attended  |  concurrent-attended  | ap11 - Singapore<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)  |
|  concurrent  |  Concurrent  | ap11 - Singapore<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us10 - US East (VA)<br> jp10 - Japan (Tokyo)<br> eu10 - Europe (Frankfurt)<br> ap10 - Australia (Sydney)  |
|  concurrent-unattended  |  concurrent-unattended  | ap11 - Singapore<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us10 - US East (VA)<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **SAP Intelligent Robotic Process Automation** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **IRPA** by configuring your `usecase.json` file.

### Using the service plan **default** (SAP Intelligent Robotic Process Automation)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "IRPA",
      "plan": "default"
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
      "name": "IRPA",
      "plan": "free"
    }
  ]
}
```

### Using the service plan **concurrent-attended**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "IRPA",
      "plan": "concurrent-attended"
    }
  ]
}
```

### Using the service plan **concurrent** (Concurrent)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "IRPA",
      "plan": "concurrent"
    }
  ]
}
```

### Using the service plan **concurrent-unattended**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "IRPA",
      "plan": "concurrent-unattended"
    }
  ]
}
```
