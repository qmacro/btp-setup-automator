# **mobile-services** (Mobile Services)

Service category: **SERVICE**

Use Mobile Services to provide mobile access to enterprise information. Key features include app content lifecycle management, push notifications and support for offline apps, app security, app monitoring and usage reporting. Mobile Services can be used for native built apps, Mobile Development Kit apps and SAP Mobile Cards. Get started by clicking on the Support link below.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/SAP_MOBILE_SERVICES/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/mobile-services)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)
- [Mobile Services Consolidated Documentation (Cloud Foundry)](https://developers.sap.com/mobile)
- [Support information](https://mobile-service-cockpit-web.cfapps.us10.hana.ondemand.com)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  free  |  free  | eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> ap21 - Singapore<br> us21 - US East (VA)<br> ap12 - South Korea (Seoul)<br> ca10 - Canada (Montreal)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> br10 - Brazil (Sao Paulo)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  b2c  |  b2c  | eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> ca10 - Canada (Montreal)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap12 - South Korea (Seoul)<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)  |
|  standard  |  standard  | eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> ca10 - Canada (Montreal)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap12 - South Korea (Seoul)<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)  |

## Sample configuration of **Mobile Services** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **mobile-services** by configuring your `usecase.json` file.

### Using the service plan **free**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "mobile-services",
      "plan": "free"
    }
  ]
}
```

### Using the service plan **b2c**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "mobile-services",
      "plan": "b2c"
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
      "name": "mobile-services",
      "plan": "standard"
    }
  ]
}
```
