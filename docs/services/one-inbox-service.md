# **one-inbox-service** (SAP Task Center)

Service category: **SERVICE**

The SAP Task Center service only enables, but does not include the integration implementation from the supported SAP solutions. The SAP Task Center service enables integration with SAP applications to provide a single entry point for end users to access all their assigned workflow tasks. The tasks can be accessed by end users through the SAP Task Center Web application.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/TASK_CENTER/Cloud/en-US)
- [Support](https://help.sap.com/viewer/08cbda59b4954e93abb2ec85f1db399d/Cloud/en-US/9693186f1fe54cbe801085d6bdfe8287.html)
- [View APIs](https://cloudintegration.int.sap.eu2.hana.ondemand.com/package/SAPTaskCenter)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | jp20 - Japan (Tokyo)<br> eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> eu20 - Europe (Netherlands)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap20 - Australia (Sydney) Azure<br> us21 - US East (VA)<br> us20 - US West (WA)<br> ca10 - Canada (Montreal)<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **SAP Task Center** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **one-inbox-service** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "one-inbox-service",
      "plan": "standard", 
      "parameters" : { 
        "authorities": null,
        "defaultCollectionQueryFilter": null
      }
    }
  ]
}
```
