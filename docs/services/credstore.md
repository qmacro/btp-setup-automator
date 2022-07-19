# **credstore** (Credential Store)

Service category: **SERVICE**

The Credential Store provides a secure repository for passwords and keys to applications that are running on SAP Cloud Platform. It enables the applications to retrieve credentials and use them for authentication to external services, or to perform cryptographic operations and TLS communication. 

## Additional details

- [Documentation](https://help.sap.com/viewer/product/CREDENTIAL_STORE/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/credential-store)
- [Support](https://help.sap.com/viewer/601525c6e5604e4192451d5e7328fa3c/Cloud/en-US/c6ebd580c0a642e9a99dbb8ae5c6c562.html)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)
- [Documentation](https://help.sap.com/viewer/601525c6e5604e4192451d5e7328fa3c/Cloud/en-US/ad63368e8e6f44a1b3ac336e8d1c32b8.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  free  |  free  | ch20 - cf-ch20<br> eu30 - Europe (Frankfurt)<br> in30 - India (Mumbai)<br> us20 - US West (WA)<br> us10 - US East (VA)<br> us21 - US East (VA)<br> us30 - US Central (IA)<br> ap21 - Singapore<br> ap12 - South Korea (Seoul)<br> ap11 - Singapore<br> jp20 - Japan (Tokyo)<br> jp10 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu10 - Europe (Frankfurt)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap20 - Australia (Sydney) Azure<br> ap10 - Australia (Sydney)  |
|  standard  |  standard  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap21 - Singapore<br> us30 - US Central (IA)<br> jp20 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> us20 - US West (WA)<br> ap11 - Singapore<br> jp10 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> ap10 - Australia (Sydney)<br> br10 - Brazil (Sao Paulo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  proxy  |  proxy  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> eu20 - Europe (Netherlands)<br> br10 - Brazil (Sao Paulo)<br> us30 - US Central (IA)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Credential Store** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **credstore** by configuring your `usecase.json` file.

### Using the service plan **free**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "credstore",
      "plan": "free"
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
      "name": "credstore",
      "plan": "standard"
    }
  ]
}
```

### Using the service plan **proxy**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "credstore",
      "plan": "proxy"
    }
  ]
}
```
