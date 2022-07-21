# jobscheduler (Job Scheduling Service)

The Job Scheduling Service allows you to define and manage jobs that run once or on recurring schedules. Use this runtime-agnostic service to schedule REST endpoint actions in your application or to schedule long-running processes using Cloud Foundry tasks. Use REST APIs to schedule your jobs, including long-running jobs asynchronously, and create multiple schedule formats for both simple and complex recurring schedules. The service dashboard is a web interface that lets you manage jobs and schedules.

## Additional details
- Service category: **SERVICE**
- Supported environments: **cloudfoundry**, **kymaruntime**, **sapbtp**

- [Documentation](https://help.sap.com/viewer/product/JOB_SCHEDULER/Cloud/en-US)
- [Support](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5dd739823b824b539eee47b7860a00be.html)
- [Buy Now](https://www.sapstore.com/solutions/40166/SAP-Cloud-Platform-Job-Scheduler)
- [Documentation](https://help.sap.com/viewer/07b57c2f4b944bcd8470d024723a1631/Cloud/en-US/22c2df4d22cb4a05af4c9502a67597ae.html)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> ap12 - South Korea (Seoul)<br> ap20 - Australia (Sydney) Azure<br> ap21 - Singapore<br> br10 - Brazil (Sao Paulo)<br> ca10 - Canada (Montreal)<br> ch20 - cf-ch20<br> eu10 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu20 - Europe (Netherlands)<br> eu30 - Europe (Frankfurt)<br> in30 - India (Mumbai)<br> jp10 - Japan (Tokyo)<br> jp20 - Japan (Tokyo)<br> us10 - US East (VA)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> us30 - US Central (IA)  |

## Sample configuration of **Job Scheduling Service** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **jobscheduler** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "jobscheduler",
      "plan": "standard"
    }
  ]
}
```
