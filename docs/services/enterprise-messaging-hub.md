# **enterprise-messaging-hub** (Event Mesh)

Service category: **APPLICATION**

The SAP Event Mesh service decouples communication and allows for event-driven business processes.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/SAP_ENTERPRISE_MESSAGING/Cloud/en-US)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  Event Mesh Hub  | in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> jp10 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> ap10 - Australia (Sydney)<br> ap11 - Singapore<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Event Mesh** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **enterprise-messaging-hub** by configuring your `usecase.json` file.

### Using the service plan **standard** (Event Mesh Hub)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "enterprise-messaging-hub",
      "plan": "standard"
    }
  ]
}
```
