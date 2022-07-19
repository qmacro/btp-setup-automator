# **apimanagement-devportal** (API Management, developer portal)

Service category: **SERVICE**

API Management, developer portal service simplifies sharing managed APIs and enables collaborations with customers, partners, and developers, providing a common platform for application developers to consume APIs. It offers capabilities for onboarding application developers, exploring and testing APIs, and creating and subscribing to applications.This service provides the plan which allows you to access APIs in the developer portal.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/SAP_CLOUD_PLATFORM_API_MANAGEMENT)
- [Documentation](https://help.hana.ondemand.com/apim_od/frameset.htm)
- [Support information](https://help.sap.com/viewer/66d066d903c2473f81ec33acfe2ccdb4/Cloud/en-US/e765066197904519a730c3bca40f28b0.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  devportal-apiaccess  |  devportal-apiaccess  | us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu10 - Europe (Frankfurt)<br> ap21 - Singapore<br> us21 - US East (VA)<br> ap10 - Australia (Sydney)<br> br10 - Brazil (Sao Paulo)<br> ca10 - Canada (Montreal)<br> jp10 - Japan (Tokyo)<br> jp20 - Japan (Tokyo)<br> ap11 - Singapore<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)  |

## Sample configuration of **API Management, developer portal** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **apimanagement-devportal** by configuring your `usecase.json` file.

### Using the service plan **devportal-apiaccess**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "apimanagement-devportal",
      "plan": "devportal-apiaccess"
    }
  ]
}
```
