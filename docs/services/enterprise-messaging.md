# **enterprise-messaging** (Event Mesh)

Service category: **SERVICE**

The SAP Event Mesh service decouples communication and allows for event-driven business processes.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/SAP_ENTERPRISE_MESSAGING/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/event-mesh)
- [Support](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5dd739823b824b539eee47b7860a00be.html)
- [Documentation](https://help.sap.com/viewer/bf82e6b26456494cbdd197057c09979f/Cloud/en-US/df532e8735eb4322b00bfc7e42f84e8d.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  event-mesh-connectivity  |  Event Mesh Connectivity  | eu10 - Europe (Frankfurt)  |
|  event-mesh-connectivity-beta  |  event-mesh-connectivity-beta  | us20 - US West (WA)<br> eu10 - Europe (Frankfurt)  |
|  default  |  default  | in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> ap11 - Singapore<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Event Mesh** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **enterprise-messaging** by configuring your `usecase.json` file.

### Using the service plan **event-mesh-connectivity** (Event Mesh Connectivity)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "enterprise-messaging",
      "plan": "event-mesh-connectivity"
    }
  ]
}
```

### Using the service plan **event-mesh-connectivity-beta**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "enterprise-messaging",
      "plan": "event-mesh-connectivity-beta"
    }
  ]
}
```

### Using the service plan **default**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "enterprise-messaging",
      "plan": "default"
    }
  ]
}
```
