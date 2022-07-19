# **privatelink** (Private Link Service)

Service category: **SERVICE**

The SAP Private Link service (BETA) establishes a private connection between selected SAP BTP services and selected services in your own IaaS provider accounts. By reusing the private link functionality of our partner IaaS providers, it lets you access your services through private network connections to avoid data transfer via the public Internet.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/PRIVATE_LINK/CLOUD/en-US)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  standard  |  standard  | ap21 - Singapore<br> ap20 - Australia (Sydney) Azure<br> jp20 - Japan (Tokyo)<br> us21 - US East (VA)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)  |

## Sample configuration of **Private Link Service** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **privatelink** by configuring your `usecase.json` file.

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "privatelink",
      "plan": "standard"
    }
  ]
}
```
