# **application-logs** (Application Logging Service)

Service category: **SERVICE**

In the Cloud Foundry environment, the SAP Application Logging service for SAP BTP lets you stream logs of bound applications to a central application logging stack. SAP Application Logging service for SAP BTP uses Elastic Stack to store and visualize your application log data. To fully leverage this service, please also consider using one of SAP&apos;s open source libraries (for example, cf-java-logging-support or cf-nodejs-logging-support). In the Neo environment, the application logging allows you to configure loggers for Java applications through the cockpit or the console client. Furthermore, you can retrieve default trace logs, HTTP access logs, and garbage collection logs for the last 7 days.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/APPLICATION_LOGGING/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/#/serviceCatalog/application-logging-service)
- [Documentation](https://help.sap.com/viewer/ee8e8a203e024bbb8c8c2d03fce527dc/Cloud/en-US/68454d44ad41458788959485a24305e2.html)
- [Support information](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5dd739823b824b539eee47b7860a00be.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  large  |  large  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> us30 - US Central (IA)<br> br10 - Brazil (Sao Paulo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  lite  |  lite  | eu11 - Europe (Frankfurt) EU Access - AWS<br> eu30 - Europe (Frankfurt)<br> jp20 - Japan (Tokyo)<br> us30 - US Central (IA)<br> ca10 - Canada (Montreal)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> ap21 - Singapore<br> ap10 - Australia (Sydney)<br> br10 - Brazil (Sao Paulo)<br> eu20 - Europe (Netherlands)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> ap11 - Singapore<br> ap12 - South Korea (Seoul)<br> ap20 - Australia (Sydney) Azure  |
|  standard  |  standard  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> jp10 - Japan (Tokyo)<br> us30 - US Central (IA)<br> br10 - Brazil (Sao Paulo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Application Logging Service** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **application-logs** by configuring your `usecase.json` file.

### Using the service plan **large**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "application-logs",
      "plan": "large"
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
      "name": "application-logs",
      "plan": "lite"
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
      "name": "application-logs",
      "plan": "standard"
    }
  ]
}
```
