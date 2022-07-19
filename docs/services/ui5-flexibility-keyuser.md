# **ui5-flexibility-keyuser** (UI5 flexibility for key users)

Service category: **SERVICE**

The UI5 flexibility service for key users lets you provide UI adaptation capabilites for your UI5 applications on Cloud Foundry. Users of your applications can change the user interface of your applications in an upgrade-safe and modification-free way, without affecting any other customer.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/UI5_FLEXIBILITY_KEY_USER/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/ui5-flexibility-for-key-users)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  free  |  free  | us20 - US West (WA)<br> us10 - US East (VA)<br> us21 - US East (VA)<br> us30 - US Central (IA)<br> ap21 - Singapore<br> ap12 - South Korea (Seoul)<br> ap11 - Singapore<br> jp20 - Japan (Tokyo)<br> jp10 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu10 - Europe (Frankfurt)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap20 - Australia (Sydney) Azure<br> ap10 - Australia (Sydney)  |
|  keyuser  |  keyuser  | in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap12 - South Korea (Seoul)<br> ca10 - Canada (Montreal)<br> jp20 - Japan (Tokyo)<br> jp10 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> ap21 - Singapore<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us30 - US Central (IA)<br> us21 - US East (VA)<br> us20 - US West (WA)<br> us10 - US East (VA)<br> eu20 - Europe (Netherlands)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **UI5 flexibility for key users** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **ui5-flexibility-keyuser** by configuring your `usecase.json` file.

### Using the service plan **free**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "ui5-flexibility-keyuser",
      "plan": "free"
    }
  ]
}
```

### Using the service plan **keyuser**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "ui5-flexibility-keyuser",
      "plan": "keyuser"
    }
  ]
}
```
