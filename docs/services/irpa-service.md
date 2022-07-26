# irpa-service (SAP Intelligent Robotic Process Automation)

SAP Intelligent Robotic Process Automation (SAP Intelligent RPA) lets you automate enterprise business processes. Design process automations with the Desktop Studio by creating end-to-end scenarios. Import these scenarios into the cloud Factory powered by SAP Cloud Platform to configure and execute them with Agents. Agents running on workstations can work as a Digital Assistant (attended automation) or as a Digital Worker (unattended automation).	

## Additional details
- Service category: SERVICE
- Supported environments: cloudfoundry

- [Documentation](https://help.sap.com/viewer/p/IRPA)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/sap-intelligent-rpa)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> eu10 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu20 - Europe (Netherlands)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |

## Sample configuration of **SAP Intelligent Robotic Process Automation** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **irpa-service** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "irpa-service",
      "plan": "standard"
    }
  ]
}
```
