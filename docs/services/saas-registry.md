# **saas-registry** (SaaS Provisioning Service)

Service category: **SERVICE**

Service for application providers to register multitenant applications and services.

## Additional details

- [Documentation](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5e8a2b74e4f2442b8257c850ed912f48.html)
- [Discovery Center](https://discovery-center.cloud.sap/#/serviceCatalog/saas-provisioning-service?service_plan=application&region=all)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  application  |  application  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us20 - US West (WA)<br> us10 - US East (VA)<br> us21 - US East (VA)<br> us30 - US Central (IA)<br> ap21 - Singapore<br> ap12 - South Korea (Seoul)<br> ap11 - Singapore<br> jp20 - Japan (Tokyo)<br> jp10 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> eu10 - Europe (Frankfurt)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap20 - Australia (Sydney) Azure<br> ap10 - Australia (Sydney)  |

## Sample configuration of **SaaS Provisioning Service** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **saas-registry** by configuring your `usecase.json` file.

### Using the service plan **application**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "saas-registry",
      "plan": "application"
    }
  ]
}
```
