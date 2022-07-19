# **identity** (Cloud Identity Services)

Service category: **SERVICE**

Cloud Identity Services provide basic capabilities for user authentication.

## Additional details

- [Documentation](https://help.sap.com/viewer/p/IDENTITY_PROVISIONING)
- [Documentation](https://help.sap.com/IAS)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  application  |  application  | ch20 - cf-ch20<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap20 - Australia (Sydney) Azure<br> us30 - US Central (IA)<br> us10 - US East (VA)<br> us20 - US West (WA)<br> ap21 - Singapore<br> us21 - US East (VA)<br> eu20 - Europe (Netherlands)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap11 - Singapore<br> jp10 - Japan (Tokyo)<br> jp20 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> eu10 - Europe (Frankfurt)<br> ap12 - South Korea (Seoul)  |

## Sample configuration of **Cloud Identity Services** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **identity** by configuring your `usecase.json` file.

### Using the service plan **application**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "identity",
      "plan": "application"
    }
  ]
}
```
