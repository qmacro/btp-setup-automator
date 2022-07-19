# **integrationsuite** (Integration Suite)

Service category: **APPLICATION**

SAP Integration Suite helps you to quickly develop and manage reliable communication between applications, services, and systems across heterogeneous landscapes.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/SAP_CLOUD_PLATFORM_INTEGRATION_SUITE)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  free  |  Free  | us30 - US Central (IA)<br> jp20 - Japan (Tokyo)<br> us21 - US East (VA)<br> ap21 - Singapore<br> ap20 - Australia (Sydney) Azure<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> jp10 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> ap12 - South Korea (Seoul)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  enterprise_agreement  |  Enterprise Agreement  | us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> jp10 - Japan (Tokyo)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> us21 - US East (VA)<br> us20 - US West (WA)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> eu20 - Europe (Netherlands)  |
|  messages  |  Integration Suite Messages  | jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap21 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> br10 - Brazil (Sao Paulo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> us21 - US East (VA)  |

## Sample configuration of **Integration Suite** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **integrationsuite** by configuring your `usecase.json` file.

### Using the service plan **free** (Free)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "integrationsuite",
      "plan": "free"
    }
  ]
}
```

### Using the service plan **enterprise_agreement** (Enterprise Agreement)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "integrationsuite",
      "plan": "enterprise_agreement"
    }
  ]
}
```

### Using the service plan **messages** (Integration Suite Messages)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "integrationsuite",
      "plan": "messages"
    }
  ]
}
```
