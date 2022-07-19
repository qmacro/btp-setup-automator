# **ml-foundation** (SAP Leonardo ML Foundation)

Service category: **SERVICE**

SAP Leonardo Machine Learning Foundation enables you to enhance business processes and software applications with intelligence. Unlock knowledge from structured and unstructured data such as images, text, time series and tabular data. By consuming easy-to-use APIs you can detect the content of pictures, extract keywords from natural language texts or analyze and forecast time-series data. All this can be done without prior investmentintospecial hardware or expertise in machine learning. Besides using pre-trained ML services you can also deploy custom ML models or tune existing models with your own training data. This allows you to easily serve customized ML models for critical business processes in a scalable and secure manner.

## Additional details

- [Documentation](https://help.sap.com/viewer/p/SAP_LEONARDO_MACHINE_LEARNING_FOUNDATION)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/machine-learning-foundation)
- [Documentation](http://help.sap.com/mlf)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | eu11 - Europe (Frankfurt) EU Access - AWS<br> jp10 - Japan (Tokyo)<br> us30 - US Central (IA)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **SAP Leonardo ML Foundation** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **ml-foundation** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "ml-foundation",
      "plan": "standard"
    }
  ]
}
```
