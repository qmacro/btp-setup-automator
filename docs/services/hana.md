# **hana** (SAP HANA Schemas & HDI Containers)

Service category: **SERVICE**

Use the SAP HANA schemas & HDI containers service to create service instances on SAP HANA databases and bind them to cloud applications. To create schemas and HDI containers, an SAP HANA database must be available in your space. The SAP HANA schemas & HDI containers service is part of the SAP HANA service.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/HANA_CLOUD/cloud/en-US)
- [Documentation](https://help.sap.com/viewer/a36ee1aa073e4e8e840573fb30a72d95/Cloud/en-US/1e9a6cb47e1b44f990a917b4bf8c2e19.html)
- [Support information](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5dd739823b824b539eee47b7860a00be.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  hdi-shared  |  hdi-shared  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> eu20 - Europe (Netherlands)<br> us30 - US Central (IA)<br> br10 - Brazil (Sao Paulo)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  schema  |  schema  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> eu20 - Europe (Netherlands)<br> us30 - US Central (IA)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  sbss  |  sbss  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> eu20 - Europe (Netherlands)<br> us30 - US Central (IA)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  securestore  |  securestore  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> us30 - US Central (IA)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **SAP HANA Schemas & HDI Containers** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **hana** by configuring your `usecase.json` file.

### Using the service plan **hdi-shared**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hana",
      "plan": "hdi-shared"
    }
  ]
}
```

### Using the service plan **schema**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hana",
      "plan": "schema"
    }
  ]
}
```

### Using the service plan **sbss**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hana",
      "plan": "sbss"
    }
  ]
}
```

### Using the service plan **securestore**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hana",
      "plan": "securestore"
    }
  ]
}
```
