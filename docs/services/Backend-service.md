# **Backend-service** (Backend Service)

Service category: **APPLICATION**

With SAP Cloud Platform Backed service you can build robust, scalable and enterprise-ready APIs/services to serve your applications and extensions in a serverless environment. It is a fully managed API service that helps you build, run, and manage APIs in a serverless environment [BETA]

## Additional details

- [Documentation](https://help.sap.com/viewer/70dea311943a4ab99f903ccc584225f6/Cloud/en-US)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  SAP Cloud Platform Backend service  | eu10 - Europe (Frankfurt)  |

## Sample configuration of **Backend Service** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **Backend-service** by configuring your `usecase.json` file.

### Using the service plan **standard** (SAP Cloud Platform Backend service)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "Backend-service",
      "plan": "standard"
    }
  ]
}
```
