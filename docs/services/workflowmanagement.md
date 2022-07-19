# **workflowmanagement** (Workflow Management)

Service category: **SERVICE**

Digitize workflows, manage decisions and gain end-to-end process visibility

## Additional details

- [Documentation](https://help.sap.com/viewer/product/WORKFLOW_MANAGEMENT/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/workflow-management)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  workflow  |  workflow  | eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap12 - South Korea (Seoul)<br> ca10 - Canada (Montreal)<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> eu20 - Europe (Netherlands)<br> ap21 - Singapore<br> br10 - Brazil (Sao Paulo)<br> ap11 - Singapore<br> jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Workflow Management** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **workflowmanagement** by configuring your `usecase.json` file.

### Using the service plan **workflow**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "workflowmanagement",
      "plan": "workflow", 
      "parameters" : { 
        
      }
    }
  ]
}
```
