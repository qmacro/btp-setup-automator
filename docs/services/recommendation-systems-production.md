# **recommendation-systems-production** (Personalized Recommendation)

Service category: **SERVICE**

Personalized Recommendation is a generic reusable service. It uses state-of-the-art machine learning techniques to give visitors to your website highly personalized recommendations based on their browsing history and/or item description. Train and use machine learning models to deliver these recommendations across a wide range of business scenarios. Personalized Recommendation is part of the SAP AI Business Services portfolio.

## Additional details

- [Documentation](https://help.sap.com/pr)
- [Support](https://help.sap.com/docs/Personalized_Recommendation/2c2078b9efa84566ac19d44df9625c65/c9cb13e6510248bdbb60ab0ea799d046.html)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | eu11 - Europe (Frankfurt) EU Access - AWS<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  free  |  free  | eu11 - Europe (Frankfurt) EU Access - AWS<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Personalized Recommendation** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **recommendation-systems-production** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "recommendation-systems-production",
      "plan": "standard"
    }
  ]
}
```

### Using the service plan **free**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "recommendation-systems-production",
      "plan": "free"
    }
  ]
}
```
