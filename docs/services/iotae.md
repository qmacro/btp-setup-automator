# iotae (SAP IoT)

Service category: **SERVICE**

SAP IoT business services allow you to put raw sensor data into business object context and then use query models, rules, events and actions to leverage the data near real-time in analytical or transactional business applications.

## Additional details

- [Documentation](https://help.sap.com/viewer/p/SAP_Leonardo_IoT)
- [Documentation](https://help.sap.com/viewer/p/SAP_IoT)
- [Support information](https://answers.sap.com/tags/73554900100800002247)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | eu10 - Europe (Frankfurt)<br> eu20 - Europe (Netherlands)  |
|  default  |  default  | eu10 - Europe (Frankfurt)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> us20 - US West (WA)  |

## Sample configuration of **SAP IoT** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **iotae** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "iotae",
      "plan": "standard"
    }
  ]
}
```

### Using the service plan **default**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "iotae",
      "plan": "default"
    }
  ]
}
```
