# abap (ABAP environment)

Access an instance to build custom ABAP cloud apps, leveraging newest innovations powered by SAP HANA.

## Additional details
- Service category: SERVICE
- Supported environments: tbd

- [Documentation](https://help.sap.com/viewer/3504ec5ef16548778610c7e89cc0eac3/Cloud/en-US/11d62652aa2b4600a0fa136de0789648.html)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/abap-environment)
- [Business Technology Platform Supplemental Terms and Conditions](https://www.sap.com/about/trust-center/agreements/cloud/cloud-services.html?tag=language:english&search=Supplement%20Business%20Technology%20Platform&sort=latest_desc)
- [Documentation](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/e34a329acc804c0e874496548183682f.html)
- [Support information](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5dd739823b824b539eee47b7860a00be.html)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  abap_compute_unit  |  16 GB ABAP Compute Unit  | eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |
|  hana_compute_unit  |  16 GB HANA Compute Unit  | eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |
|  16_abap_64_db  |  16_abap_64_db  | eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |
|  free  |  free  | eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |
|  standard  |  standard  | eu10 - Europe (Frankfurt)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)  |

## Sample configuration of **ABAP environment** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **abap** by configuring your `usecase.json` file.

### Using the service plan **abap_compute_unit** (16 GB ABAP Compute Unit)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "abap",
      "plan": "abap_compute_unit"
    }
  ]
}
```

### Using the service plan **hana_compute_unit** (16 GB HANA Compute Unit)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "abap",
      "plan": "hana_compute_unit"
    }
  ]
}
```

### Using the service plan **16_abap_64_db**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "abap",
      "plan": "16_abap_64_db", 
      "parameters" : { 
        "admin_email": null,
        "description": null,
        "is_development_allowed": true,
        "sapsystemname": "H01"
      }
    }
  ]
}
```

### Using the service plan **free**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "abap",
      "plan": "free", 
      "parameters" : { 
        "admin_email": null,
        "description": null,
        "sapsystemname": "H01"
      }
    }
  ]
}
```

### Using the service plan **standard**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "abap",
      "plan": "standard", 
      "parameters" : { 
        "admin_email": null,
        "description": null,
        "is_development_allowed": true,
        "sapsystemname": "H01",
        "size_of_persistence": 4,
        "size_of_runtime": 1
      }
    }
  ]
}
```
