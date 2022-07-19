# **sdm-web** (Document Management Service, Application Option)

Service category: **APPLICATION**

Benefit from the standalone, ready-to-use web application of SAP Document Management service that provides document management capabilities.

## Additional details

- [Documentation](https://help.sap.com/viewer/p/DOCUMENT_MANAGEMENT)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  Document Management, application option  | ap20 - Australia (Sydney) Azure<br> eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap12 - South Korea (Seoul)<br> ap21 - Singapore<br> ca10 - Canada (Montreal)<br> us21 - US East (VA)<br> jp20 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> jp10 - Japan (Tokyo)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Document Management Service, Application Option** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **sdm-web** by configuring your `usecase.json` file.

### Using the service plan **standard** (Document Management, application option)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "sdm-web",
      "plan": "standard"
    }
  ]
}
```
