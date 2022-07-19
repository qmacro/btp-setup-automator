# **document-translation** (Document Translation)

Service category: **SERVICE**

Provides an API that allows you to translate documents of various formats into multiple languages.

## Additional details

- [Documentation](https://help.sap.com/viewer/9f73362817cd48339dd8a6acba160f7f/Cloud/en-US/c07bd4ee447b477b9ccb31b3abf5dae3.html)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)
- [Support information](https://help.sap.com/viewer/ed6ce7a29bdd42169f5f0d7868bce6eb/Cloud/en-US/b33a4ed0f6914c7291cf788752a977ac.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  default  |  Default  | us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  free  |  Free  | us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Document Translation** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **document-translation** by configuring your `usecase.json` file.

### Using the service plan **default** (Default)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "document-translation",
      "plan": "default"
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
      "name": "document-translation",
      "plan": "free"
    }
  ]
}
```
