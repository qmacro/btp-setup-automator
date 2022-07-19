# **xsuaa** (Authorization and Trust Management Service)

Service category: **SERVICE**

The Authorization and Trust Management service lets you manage user authorizations and trust to identity providers. Identity providers are the user base for applications. You can use an identity authentication tenant, an SAP on-premise system, or a custom corporate identity provider. User authorizations are managed using technical roles at the application level, which can be aggregated into business-level groups and role collections for large-scale cloud scenarios.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/CP_AUTHORIZ_TRUST_MNG/Cloud/en-US)
- [REST API Documentation](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/dbea343ebe184c26b6067daaabaa9ac6.html)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/authorization-and-trust-management-service)
- [Documentation](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/6373bb7a96114d619bfdfdc6f505d1b9.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  application  |  application  | ch20 - cf-ch20<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> jp20 - Japan (Tokyo)<br> us30 - US Central (IA)<br> ca10 - Canada (Montreal)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> ap21 - Singapore<br> ap10 - Australia (Sydney)<br> br10 - Brazil (Sao Paulo)<br> eu20 - Europe (Netherlands)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> ap11 - Singapore<br> ap12 - South Korea (Seoul)<br> ap20 - Australia (Sydney) Azure  |
|  broker  |  broker  | ch20 - cf-ch20<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> jp20 - Japan (Tokyo)<br> us30 - US Central (IA)<br> ca10 - Canada (Montreal)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> ap21 - Singapore<br> ap10 - Australia (Sydney)<br> br10 - Brazil (Sao Paulo)<br> eu20 - Europe (Netherlands)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> ap11 - Singapore<br> ap12 - South Korea (Seoul)<br> ap20 - Australia (Sydney) Azure  |
|  apiaccess  |  apiaccess  | ch20 - cf-ch20<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> jp20 - Japan (Tokyo)<br> us30 - US Central (IA)<br> ca10 - Canada (Montreal)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> ap21 - Singapore<br> ap10 - Australia (Sydney)<br> br10 - Brazil (Sao Paulo)<br> eu20 - Europe (Netherlands)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> ap11 - Singapore<br> ap12 - South Korea (Seoul)<br> ap20 - Australia (Sydney) Azure  |
|  space  |  space  | ch20 - cf-ch20<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> jp20 - Japan (Tokyo)<br> us30 - US Central (IA)<br> ca10 - Canada (Montreal)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> ap21 - Singapore<br> ap10 - Australia (Sydney)<br> br10 - Brazil (Sao Paulo)<br> eu20 - Europe (Netherlands)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> ap11 - Singapore<br> ap12 - South Korea (Seoul)<br> ap20 - Australia (Sydney) Azure  |

## Sample configuration of **Authorization and Trust Management Service** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **xsuaa** by configuring your `usecase.json` file.

### Using the service plan **application**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "xsuaa",
      "plan": "application"
    }
  ]
}
```

### Using the service plan **broker**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "xsuaa",
      "plan": "broker"
    }
  ]
}
```

### Using the service plan **apiaccess**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "xsuaa",
      "plan": "apiaccess"
    }
  ]
}
```

### Using the service plan **space**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "xsuaa",
      "plan": "space"
    }
  ]
}
```
