# ai-launchpad (SAP AI Launchpad)

SAP AI Launchpad is an application layer for AI Foundation. It is a one-stop-shop to access tooling around ML lifecycle management & Data Science activity. It is a container to access both SAP and open sourced integrated apps and tools. It is connected to a number of ML runtimes with an AI API. It allows users to get an overview over all ML Scenarios in all connected ML runtimes and manage the lifecycle of these.

## Additional details
- Service category: APPLICATION
- Supported environments: cloudfoundry, kymaruntime, sapbtp

- [Documentation](https://help.sap.com/viewer/product/AI_LAUNCHPAD/INTERNAL/en-US)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  Standard  | ap10 - Australia (Sydney)<br> eu10 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |

## Sample configuration of **SAP AI Launchpad** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **ai-launchpad** by configuring your `usecase.json` file.

### Using the service plan **standard** (Standard)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "ai-launchpad",
      "plan": "standard"
    }
  ]
}
```
