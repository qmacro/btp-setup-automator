# **theming** (UI Theme Designer)

Service category: **SERVICE**

The UI theme designer lets you apply your corporate branding to applications built with SAP UI technologies. You can make changes to theme templates supplied by SAP to create custom themes that use your own color scheme, background images, and company logo. You can apply a custom theme to various SAP UI clients and technologies. Additionally, you can include your own custom CSS files without having to modify any of your applications.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/UI_THEME_DESIGNER/Cloud/en-US)
- [SAP Community](http://www.sap.com/community/topic/ui-theme-designer.html)
- [Documentation](https://help.sap.com/viewer/09f6818d8e064537973102d6289e2aca/Cloud)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> us30 - US Central (IA)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **UI Theme Designer** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **theming** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "theming",
      "plan": "standard"
    }
  ]
}
```
