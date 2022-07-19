# **hana-cloud** (SAP HANA Cloud)

Service category: **SERVICE**

SAP HANA Cloud provides a single place to access, store, and process all enterprise data in real time. It is a cloud-native platform that reduces the complexity of multi-cloud or hybrid system landscapes. SAP HANA Cloud provides all of the advanced SAP HANA technologies for multi-model data processing in-memory or on disk. You can benefit from cloud qualities such as automatic software updates, elasticity, and low total cost of ownership by using SAP HANA Cloud either as a stand-alone solution or as an extension to your existing on-premise environment.

## Additional details

- [Documentation](https://help.sap.com/viewer/p/HANA_CLOUD)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/sap-hana-cloud)
- [Support](https://help.sap.com/viewer/db19c7071e5f4101837e23f06e576495/cloud/en-US/4f8dabb4d8214d5d93b98dd5f2ad76c9.html)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  relational-data-lake-free  |  relational-data-lake-free  | ap10 - Australia (Sydney)<br> ap20 - Australia (Sydney) Azure<br> eu20 - Europe (Netherlands)<br> jp20 - Japan (Tokyo)<br> ap21 - Singapore<br> ap11 - Singapore<br> jp10 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> us10 - US East (VA)<br> us21 - US East (VA)<br> ap12 - South Korea (Seoul)<br> us20 - US West (WA)  |
|  adaptive-server-enterprise-replication  |  adaptive-server-enterprise-replication  | ap20 - Australia (Sydney) Azure<br> us21 - US East (VA)<br> eu20 - Europe (Netherlands)  |
|  hana-cloud-connection-free  |  hana-cloud-connection-free  | ap10 - Australia (Sydney)<br> ap20 - Australia (Sydney) Azure<br> eu20 - Europe (Netherlands)<br> jp20 - Japan (Tokyo)<br> ap21 - Singapore<br> ap11 - Singapore<br> jp10 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> us10 - US East (VA)<br> us21 - US East (VA)<br> ap12 - South Korea (Seoul)<br> us20 - US West (WA)  |
|  hana  |  hana  | in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> ap20 - Australia (Sydney) Azure<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap12 - South Korea (Seoul)<br> ap11 - Singapore<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us21 - US East (VA)<br> jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  hana-free  |  hana-free  | ap10 - Australia (Sydney)<br> ap20 - Australia (Sydney) Azure<br> eu20 - Europe (Netherlands)<br> jp20 - Japan (Tokyo)<br> ap21 - Singapore<br> ap11 - Singapore<br> jp10 - Japan (Tokyo)<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> us10 - US East (VA)<br> us21 - US East (VA)<br> ap12 - South Korea (Seoul)<br> us20 - US West (WA)  |
|  hana-cloud-connection  |  hana-cloud-connection  | eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> ap11 - Singapore<br> ca10 - Canada (Montreal)<br> br10 - Brazil (Sao Paulo)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us21 - US East (VA)<br> jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  adaptive-server-enterprise  |  adaptive-server-enterprise  | ap20 - Australia (Sydney) Azure<br> us21 - US East (VA)<br> eu20 - Europe (Netherlands)  |
|  relational-data-lake  |  relational-data-lake  | eu30 - Europe (Frankfurt)<br> us30 - US Central (IA)<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> br10 - Brazil (Sao Paulo)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ap20 - Australia (Sydney) Azure<br> ap12 - South Korea (Seoul)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us21 - US East (VA)<br> jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **SAP HANA Cloud** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **hana-cloud** by configuring your `usecase.json` file.

### Using the service plan **relational-data-lake-free**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hana-cloud",
      "plan": "relational-data-lake-free", 
      "parameters" : { 
        "data": null,
        "metadata": null
      }
    }
  ]
}
```

### Using the service plan **adaptive-server-enterprise-replication**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hana-cloud",
      "plan": "adaptive-server-enterprise-replication"
    }
  ]
}
```

### Using the service plan **hana-cloud-connection-free**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hana-cloud",
      "plan": "hana-cloud-connection-free", 
      "parameters" : { 
        "data": null
      }
    }
  ]
}
```

### Using the service plan **hana**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hana-cloud",
      "plan": "hana", 
      "parameters" : { 
        "data": null,
        "metadata": null
      }
    }
  ]
}
```

### Using the service plan **hana-free**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hana-cloud",
      "plan": "hana-free", 
      "parameters" : { 
        "data": null,
        "metadata": null
      }
    }
  ]
}
```

### Using the service plan **hana-cloud-connection**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hana-cloud",
      "plan": "hana-cloud-connection", 
      "parameters" : { 
        "data": null
      }
    }
  ]
}
```

### Using the service plan **adaptive-server-enterprise**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hana-cloud",
      "plan": "adaptive-server-enterprise"
    }
  ]
}
```

### Using the service plan **relational-data-lake**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hana-cloud",
      "plan": "relational-data-lake", 
      "parameters" : { 
        "data": null,
        "metadata": null
      }
    }
  ]
}
```
