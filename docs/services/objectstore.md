# **objectstore** (Object Store)

Service category: **SERVICE**

Object Store on SAP BTP provisions an object storage space that can be used by applications to store and manage objects.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/ObjectStore/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/object-store)
- [Support](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5dd739823b824b539eee47b7860a00be.html)
- [Documentation](https://help.sap.com/viewer/2ee77ef7ea4648f9ab2c54ee3aef0a29/Cloud/en-US)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  azure-standard  |  azure-standard  | ch20 - cf-ch20<br> ap20 - Australia (Sydney) Azure<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)  |
|  s3-standard  |  s3-standard  | br10 - Brazil (Sao Paulo)  |
|  s3-standard  |  s3-standard  | ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  gcs-standard  |  gcs-standard  | in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)  |

## Sample configuration of **Object Store** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **objectstore** by configuring your `usecase.json` file.

### Using the service plan **azure-standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "objectstore",
      "plan": "azure-standard"
    }
  ]
}
```

### Using the service plan **s3-standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "objectstore",
      "plan": "s3-standard"
    }
  ]
}
```

### Using the service plan **s3-standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "objectstore",
      "plan": "s3-standard"
    }
  ]
}
```

### Using the service plan **gcs-standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "objectstore",
      "plan": "gcs-standard"
    }
  ]
}
```
