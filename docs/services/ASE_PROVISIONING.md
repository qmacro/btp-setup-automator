# **ASE_PROVISIONING** (SAP ASE Service)

Service category: **SERVICE**

The SAP ASE service on SAP Cloud Platform lets you consume SAP ASE databases from your applications running on SAP Cloud Platform or on-premise via Java APIs. It offers variousself-services, for example, that let you create or update databases, whileSAPis providing infrastructure and database platform operations.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/ASE_SERVICE/Cloud/en-US)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/sap-ase-service)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  XLARGE  |  ASE 640GB  | ca1 - Canada (Toronto)<br> ap2 - Australia (Sydney DR)<br> us3 - US East (Sterling)<br> us4 - US West (Colorado Springs)<br> jp1 - Japan (Tokyo)<br> eu2 - Europe (Frankfurt)<br> cn1 - China (Shanghai)<br> sa1 - KSA (Riyadh)<br> ca2 - Canada (Toronto DR)<br> us2 - US West (Chandler)<br> eu3 - Europe (Amsterdam)<br> ae1 - UAE (Dubai)<br> ap1 - Australia (Sydney)<br> us1 - US East (Ashburn)<br> br1 - Brazil (Sao Paulo)<br> ru1 - Russia (Moscow)<br> eu1 - Europe (Rot)  |
|  MEDIUM  |  ASE 160GB  | ca1 - Canada (Toronto)<br> ap2 - Australia (Sydney DR)<br> us3 - US East (Sterling)<br> us4 - US West (Colorado Springs)<br> jp1 - Japan (Tokyo)<br> eu2 - Europe (Frankfurt)<br> cn1 - China (Shanghai)<br> sa1 - KSA (Riyadh)<br> ca2 - Canada (Toronto DR)<br> us2 - US West (Chandler)<br> eu3 - Europe (Amsterdam)<br> ae1 - UAE (Dubai)<br> ap1 - Australia (Sydney)<br> us1 - US East (Ashburn)<br> br1 - Brazil (Sao Paulo)<br> ru1 - Russia (Moscow)<br> eu1 - Europe (Rot)  |
|  SMALL  |  ASE 80GB  | ca1 - Canada (Toronto)<br> ap2 - Australia (Sydney DR)<br> us3 - US East (Sterling)<br> us4 - US West (Colorado Springs)<br> jp1 - Japan (Tokyo)<br> eu2 - Europe (Frankfurt)<br> cn1 - China (Shanghai)<br> sa1 - KSA (Riyadh)<br> ca2 - Canada (Toronto DR)<br> us2 - US West (Chandler)<br> eu3 - Europe (Amsterdam)<br> ae1 - UAE (Dubai)<br> ap1 - Australia (Sydney)<br> us1 - US East (Ashburn)<br> br1 - Brazil (Sao Paulo)<br> ru1 - Russia (Moscow)<br> eu1 - Europe (Rot)  |
|  XSMALL  |  ASE 40GB  | ca1 - Canada (Toronto)<br> ap2 - Australia (Sydney DR)<br> us3 - US East (Sterling)<br> us4 - US West (Colorado Springs)<br> jp1 - Japan (Tokyo)<br> eu2 - Europe (Frankfurt)<br> cn1 - China (Shanghai)<br> sa1 - KSA (Riyadh)<br> ca2 - Canada (Toronto DR)<br> us2 - US West (Chandler)<br> eu3 - Europe (Amsterdam)<br> ae1 - UAE (Dubai)<br> ap1 - Australia (Sydney)<br> us1 - US East (Ashburn)<br> br1 - Brazil (Sao Paulo)<br> ru1 - Russia (Moscow)<br> eu1 - Europe (Rot)  |
|  LARGE  |  ASE 320GB  | ca1 - Canada (Toronto)<br> ap2 - Australia (Sydney DR)<br> us3 - US East (Sterling)<br> us4 - US West (Colorado Springs)<br> jp1 - Japan (Tokyo)<br> eu2 - Europe (Frankfurt)<br> cn1 - China (Shanghai)<br> sa1 - KSA (Riyadh)<br> ca2 - Canada (Toronto DR)<br> us2 - US West (Chandler)<br> eu3 - Europe (Amsterdam)<br> ae1 - UAE (Dubai)<br> ap1 - Australia (Sydney)<br> us1 - US East (Ashburn)<br> br1 - Brazil (Sao Paulo)<br> ru1 - Russia (Moscow)<br> eu1 - Europe (Rot)  |

## Sample configuration of **SAP ASE Service** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **ASE_PROVISIONING** by configuring your `usecase.json` file.

### Using the service plan **XLARGE** (ASE 640GB)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "ASE_PROVISIONING",
      "plan": "XLARGE"
    }
  ]
}
```

### Using the service plan **MEDIUM** (ASE 160GB)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "ASE_PROVISIONING",
      "plan": "MEDIUM"
    }
  ]
}
```

### Using the service plan **SMALL** (ASE 80GB)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "ASE_PROVISIONING",
      "plan": "SMALL"
    }
  ]
}
```

### Using the service plan **XSMALL** (ASE 40GB)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "ASE_PROVISIONING",
      "plan": "XSMALL"
    }
  ]
}
```

### Using the service plan **LARGE** (ASE 320GB)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "ASE_PROVISIONING",
      "plan": "LARGE"
    }
  ]
}
```
