# **apimanagement-apiportal** (API Management, API portal)

Service category: **SERVICE**

API Management, API portal service drives innovation in modern business models. Based on APIs and digital assets, the service facilitates unified access from new channels and diverse user interfaces. This is possible by enabling developer communities to connect to your enterprise information and processes securely. Here, the access to backend services and complex landscapes are simplified with easy to consume APIs while protecting your systems from threats and overloaded access.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/SAP_CLOUD_PLATFORM_API_MANAGEMENT)
- [Documentation](https://help.hana.ondemand.com/apim_od/frameset.htm)
- [Support information](https://help.sap.com/viewer/66d066d903c2473f81ec33acfe2ccdb4/Cloud/en-US/e765066197904519a730c3bca40f28b0.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  apiportal-apiaccess  |  apiportal-apiaccess  | us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us10 - US East (VA)<br> ap11 - Singapore<br> jp20 - Japan (Tokyo)<br> jp10 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap10 - Australia (Sydney)<br> us21 - US East (VA)<br> ap21 - Singapore<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> eu10 - Europe (Frankfurt)  |
|  on-premise-connectivity  |  on-premise-connectivity  | us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu10 - Europe (Frankfurt)<br> us21 - US East (VA)<br> jp20 - Japan (Tokyo)<br> jp10 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap21 - Singapore<br> ap11 - Singapore<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> ap10 - Australia (Sydney)  |
|  apim-as-route-service  |  apim-as-route-service  | us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu10 - Europe (Frankfurt)<br> us10 - US East (VA)<br> us21 - US East (VA)<br> jp20 - Japan (Tokyo)<br> jp10 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap21 - Singapore<br> ap11 - Singapore<br> us20 - US West (WA)<br> ap10 - Australia (Sydney)<br> eu20 - Europe (Netherlands)  |

## Sample configuration of **API Management, API portal** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **apimanagement-apiportal** by configuring your `usecase.json` file.

### Using the service plan **apiportal-apiaccess**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "apimanagement-apiportal",
      "plan": "apiportal-apiaccess"
    }
  ]
}
```

### Using the service plan **on-premise-connectivity**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "apimanagement-apiportal",
      "plan": "on-premise-connectivity"
    }
  ]
}
```

### Using the service plan **apim-as-route-service**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "apimanagement-apiportal",
      "plan": "apim-as-route-service"
    }
  ]
}
```
