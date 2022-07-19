# **ocnselfserviceagent** (Open Connectors)

Service category: **APPLICATION**

Open Connectors provides pre-built and feature-rich connectors to simplify the connectivity and seamless integration with over 150 non-SAP cloud applications. Customers benefit from connectivity to third-party APIs via harmonized RESTful APIs and can develop and map canonical data models to extend pre-built connectors. Furthermore customers can easily build API compositions across the different connectors.

## Additional details

- [Documentation](https://help.sap.com/viewer/p/OPEN_CONNECTORS)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  Standard  | us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> jp10 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> us21 - US East (VA)<br> ap21 - Singapore<br> ap11 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> ap10 - Australia (Sydney)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **Open Connectors** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **ocnselfserviceagent** by configuring your `usecase.json` file.

### Using the service plan **standard** (Standard)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "ocnselfserviceagent",
      "plan": "standard"
    }
  ]
}
```
