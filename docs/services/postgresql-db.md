# **postgresql-db** (PostgreSQL, hyperscaler option)

Service category: **SERVICE**

The PostgreSQL service on SAP BTP provides a way to directly consume the PostgreSQL service provided by the infrastructure providers such as AWS and Azure.

## Additional details

- [Documentation](https://help.sap.com/viewer/c92112ee69784c3383a0fb8361156a6f/Cloud/en-US/b045b64925a544689dd839266a23c89b.html)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/postgresql-hyperscaler-option)
- [Support](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5dd739823b824b539eee47b7860a00be.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  storage_ha  |  storage_ha  | ch20 - cf-ch20<br> us20 - US West (WA)<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> us10 - US East (VA)<br> ap11 - Singapore<br> jp10 - Japan (Tokyo)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu10 - Europe (Frankfurt)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap10 - Australia (Sydney)  |
|  standard  |  standard  | ch20 - cf-ch20<br> ap12 - South Korea (Seoul)<br> us10 - US East (VA)<br> ap11 - Singapore<br> jp10 - Japan (Tokyo)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu10 - Europe (Frankfurt)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap10 - Australia (Sydney)  |
|  premium  |  premium  | ch20 - cf-ch20<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us21 - US East (VA)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> ap11 - Singapore<br> jp10 - Japan (Tokyo)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu10 - Europe (Frankfurt)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap10 - Australia (Sydney)  |
|  storage  |  storage  | ch20 - cf-ch20<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us21 - US East (VA)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> ap11 - Singapore<br> jp10 - Japan (Tokyo)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu10 - Europe (Frankfurt)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap10 - Australia (Sydney)  |
|  free  |  Free  | us10 - US East (VA)<br> ap12 - South Korea (Seoul)<br> ap11 - Singapore<br> jp10 - Japan (Tokyo)<br> eu10 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap10 - Australia (Sydney)  |

## Sample configuration of **PostgreSQL, hyperscaler option** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **postgresql-db** by configuring your `usecase.json` file.

### Using the service plan **storage_ha**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql-db",
      "plan": "storage_ha"
    }
  ]
}
```

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql-db",
      "plan": "standard", 
      "parameters" : { 
        "audit_log_level": ["ROLE", "DDL"],
        "engine_version": "12",
        "locale": "en_US",
        "maintenance_window": null,
        "memory": 2,
        "multi_az": true,
        "storage": 5
      }
    }
  ]
}
```

### Using the service plan **premium**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql-db",
      "plan": "premium", 
      "parameters" : { 
        "audit_log_level": ["ROLE", "DDL"],
        "engine_version": "12",
        "locale": "en_US",
        "maintenance_window": null,
        "memory": 8,
        "multi_az": true,
        "storage": 5
      }
    }
  ]
}
```

### Using the service plan **storage**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql-db",
      "plan": "storage"
    }
  ]
}
```

### Using the service plan **free** (Free)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql-db",
      "plan": "free", 
      "parameters" : { 
        "engine_version": "12",
        "locale": "en_US"
      }
    }
  ]
}
```
