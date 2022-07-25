# workflow (Workflow)

SAP Workflow service allows you to build, run, and manage workflows, from simple approvals to end-to-end processes that span across different organizations and applications. With an inbox application and custom-built user interfaces, you involve end users into business processes for decision making and data entry. The workflow service comes with web-based tools for workflow modeling, APIs for consumption in custom applications, monitoring tools, and a set of Fiori-based applications for end-user access. You can use JavaScript to embed custom business logic.

## Additional details
- Service category: SERVICE
- Supported environments: cloudfoundry

- [Documentation](https://help.sap.com/viewer/p/WORKFLOW_SERVICE)
- [Support information](https://help.sap.com/viewer/e157c391253b4ecd93647bf232d18a83/Cloud/en-US/fab405aa1ec64d6e9880761a31b0cd06.html)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> ap12 - South Korea (Seoul)<br> ap20 - Australia (Sydney) Azure<br> ap21 - Singapore<br> br10 - Brazil (Sao Paulo)<br> ca10 - Canada (Montreal)<br> eu10 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu20 - Europe (Netherlands)<br> eu30 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> jp20 - Japan (Tokyo)<br> us10 - US East (VA)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> us30 - US Central (IA)  |

## Sample configuration of **Workflow** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **workflow** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "workflow",
      "plan": "standard", 
      "parameters" : { 
        "authorities": null,
        "defaultCollectionQueryFilter": null
      }
    }
  ]
}
```
