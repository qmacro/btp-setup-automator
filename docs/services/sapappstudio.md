# **sapappstudio** (SAP Business Application Studio)

Service category: **APPLICATION**

SAP Business Application Studio is the next generation of SAP Web IDE, offering a modular development environment tailored for efficient development of business applications for the SAP Intelligent Enterprise. It provides pre-configured environments where you can develop, build, test and run using pre-installed runtimes and tools tailored for key scenarios such as: S/4HANA extensions, full stack business applications, Fiori applications and more. It supports quick integration with SAP solutions and services to allow building smarter and more intelligent applications.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/SAP%20Business%20Application%20Studio/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/business-application-studio)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard-edition  |  standard-edition  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> ap12 - South Korea (Seoul)<br> ap20 - Australia (Sydney) Azure<br> ap21 - Singapore<br> br10 - Brazil (Sao Paulo)<br> ca10 - Canada (Montreal)<br> eu10 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu20 - Europe (Netherlands)<br> jp10 - Japan (Tokyo)<br> jp20 - Japan (Tokyo)<br> us10 - US East (VA)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> us30 - US Central (IA)  |
|  free  |  Free  | ap10 - Australia (Sydney)<br> ap11 - Singapore<br> ap12 - South Korea (Seoul)<br> ap20 - Australia (Sydney) Azure<br> ap21 - Singapore<br> br10 - Brazil (Sao Paulo)<br> ca10 - Canada (Montreal)<br> eu10 - Europe (Frankfurt)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> eu20 - Europe (Netherlands)<br> jp10 - Japan (Tokyo)<br> jp20 - Japan (Tokyo)<br> us10 - US East (VA)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> us30 - US Central (IA)  |

## Sample configuration of **SAP Business Application Studio** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **sapappstudio** by configuring your `usecase.json` file.

### Using the service plan **standard-edition**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "sapappstudio",
      "plan": "standard-edition"
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
      "category": "APPLICATION",
      "name": "sapappstudio",
      "plan": "free"
    }
  ]
}
```
