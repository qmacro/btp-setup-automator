# c4-distributed-order-management (SAP Order Management Foundation)

The SAP Order Management foundation solution, including the application and service, provides order management functionality along with business configuration settings that allow you to create a customized solution. You can also integrate various systems and solutions to support your order management processes. This allows you to leverage, for example, your existing master data, order capture, and fulfillment systems while consolidating all of your orders and order-related data in a convenient cloud-based solution.

## Additional details
- Service category: SERVICE
- Supported environments: cloudfoundry, kymaruntime, sapbtp

- [Documentation](https://help.sap.com/docs/SAP_Order_Management_Foundation?version=Cloud&locale=en-US)
- [Support](https://help.sap.com/docs/SAP_Order_Management_Foundation/d91676a7fa624c31b7b1c526d7787e2f/ca6630612cf741ed8927d60fabe13929.html?locale=en-US&version=Cloud)
- [Documentation](https://help.sap.com/viewer/product/SAP_Order_Management_Foundation/)
- [Support information](https://help.sap.com/docs/SAP_Order_Management_Foundation/d91676a7fa624c31b7b1c526d7787e2f/ca6630612cf741ed8927d60fabe13929.html)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  default  |  default  | eu10 - Europe (Frankfurt)<br> eu20 - Europe (Netherlands)  |

## Sample configuration of **SAP Order Management Foundation** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **c4-distributed-order-management** by configuring your `usecase.json` file.

### Using the service plan **default**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "c4-distributed-order-management",
      "plan": "default"
    }
  ]
}
```
