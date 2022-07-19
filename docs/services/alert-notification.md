# **alert-notification** (Alert Notification)

Service category: **SERVICE**

SAP Cloud Platform Alert Notification offers a common API for providers to publish alerts and for consumers to subscribe to these alerts. It is designed to send automatically real-time notifications and alerts about SAP Cloud events that may be of interest to the business and operations.<br/><br/>SAP does not support EU Access for this service. By activating the service, you are accepting this limitation.

## Additional details

- [SAP Cloud Platform Alert Notification @SAP Help Portal](https://help.sap.com/viewer/p/ALERT_NOTIFICATION)
- [SAP Cloud Platform Alert Notification @SAP Cloud Platform Discovery Center](https://discovery-center.cloud.sap/#/serviceCatalog/alert-notification)
- [SAP Cloud Platform Alert Notification @SAP Community](https://blogs.sap.com/tags/73555000100800001401/)
- [SAP Cloud Platform Alert Notification @SAP API Business Hub](https://api.sap.com/package/AlertNotification?section=Artifacts)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us30 - US Central (IA)<br> ap11 - Singapore<br> eu20 - Europe (Netherlands)<br> jp10 - Japan (Tokyo)<br> ap21 - Singapore<br> us21 - US East (VA)<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> br10 - Brazil (Sao Paulo)<br> ap10 - Australia (Sydney)<br> ca10 - Canada (Montreal)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  free  |  free  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> us20 - US West (WA)<br> us10 - US East (VA)<br> us21 - US East (VA)<br> us30 - US Central (IA)<br> ap21 - Singapore<br> ap12 - South Korea (Seoul)<br> ap11 - Singapore<br> jp20 - Japan (Tokyo)<br> jp10 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu10 - Europe (Frankfurt)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap10 - Australia (Sydney)  |

## Sample configuration of **Alert Notification** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **alert-notification** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "alert-notification",
      "plan": "standard"
    }
  ]
}
```

### Using the service plan **free**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "alert-notification",
      "plan": "free"
    }
  ]
}
```
