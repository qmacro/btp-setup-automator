# invoice-object-recommendation (Invoice Object Recommendation)

The Invoice Object Recommendation services provides the functionality to train a machine learning model with customer specific data that can give recommendations on G/L Accounts for incoming invoices without a purchase order reference attached. The service therefore provides a training call as described and an inference call that gives back recommendations based on a trained model to semi-automate the invoice processing in the area of accounts payable.

## Additional details
- Service category: SERVICE
- Supported environments: cloudfoundry, kymaruntime, sapbtp

- [Documentation](https://help.sap.com/viewer/product/Invoice_Object_Recommendation)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | eu10 - Europe (Frankfurt)  |

## Sample configuration of **Invoice Object Recommendation** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **invoice-object-recommendation** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "invoice-object-recommendation",
      "plan": "standard"
    }
  ]
}
```
