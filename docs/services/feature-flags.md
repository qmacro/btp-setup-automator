# **feature-flags** (Feature Flags)

Service category: **SERVICE**

The Feature Flags service allows you to enable or disable new features at runtime without redeploying or restarting the application. You can use feature flags to control code delivery, synchronized rollout, direct shipment, and fast rollback of features.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/FEATURE_FLAGS/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/feature-flags-service)
- [Support](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5dd739823b824b539eee47b7860a00be.html)
- [Documentation](https://help.sap.com/viewer/2250efa12769480299a1acd282b615cf/Cloud/en-US/)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> jp20 - Japan (Tokyo)<br> us30 - US Central (IA)<br> ca10 - Canada (Montreal)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> ap21 - Singapore<br> ap10 - Australia (Sydney)<br> br10 - Brazil (Sao Paulo)<br> eu20 - Europe (Netherlands)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> ap11 - Singapore<br> ap12 - South Korea (Seoul)<br> ap20 - Australia (Sydney) Azure  |
|  lite  |  lite  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> jp20 - Japan (Tokyo)<br> us30 - US Central (IA)<br> ca10 - Canada (Montreal)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> ap21 - Singapore<br> ap10 - Australia (Sydney)<br> br10 - Brazil (Sao Paulo)<br> eu20 - Europe (Netherlands)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> ap11 - Singapore<br> ap12 - South Korea (Seoul)<br> ap20 - Australia (Sydney) Azure  |

## Sample configuration of **Feature Flags** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **feature-flags** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "feature-flags",
      "plan": "standard"
    }
  ]
}
```

### Using the service plan **lite**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "feature-flags",
      "plan": "lite"
    }
  ]
}
```
