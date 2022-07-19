# **sap-identity-services-onboarding** (Cloud Identity Services)

Service category: **APPLICATION**

Cloud Identity Services provide basic capabilities for user authentication.

## Additional details

- [Documentation](https://help.sap.com/viewer/p/IDENTITY_AUTHENTICATION)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  default  |  default  | ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> us30 - US Central (IA)<br> us21 - US East (VA)<br> us20 - US West (WA)<br> jp20 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> ap21 - Singapore<br> us10 - US East (VA)<br> jp10 - Japan (Tokyo)<br> eu10 - Europe (Frankfurt)<br> br10 - Brazil (Sao Paulo)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)  |
|  additional-tenant  |  additional-tenant  | ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> us30 - US Central (IA)<br> us21 - US East (VA)<br> us20 - US West (WA)<br> jp20 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> ap21 - Singapore<br> us10 - US East (VA)<br> jp10 - Japan (Tokyo)<br> eu10 - Europe (Frankfurt)<br> br10 - Brazil (Sao Paulo)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)  |
|  connectivity  |  connectivity  | ap12 - South Korea (Seoul)<br> us20 - US West (WA)<br> ca10 - Canada (Montreal)<br> us10 - US East (VA)<br> jp10 - Japan (Tokyo)<br> eu10 - Europe (Frankfurt)<br> br10 - Brazil (Sao Paulo)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)  |

## Sample configuration of **Cloud Identity Services** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **sap-identity-services-onboarding** by configuring your `usecase.json` file.

### Using the service plan **default**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "sap-identity-services-onboarding",
      "plan": "default"
    }
  ]
}
```

### Using the service plan **additional-tenant**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "sap-identity-services-onboarding",
      "plan": "additional-tenant"
    }
  ]
}
```

### Using the service plan **connectivity**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "sap-identity-services-onboarding",
      "plan": "connectivity"
    }
  ]
}
```
