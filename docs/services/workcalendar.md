# workcalendar (Work Calendar)

Get details of factory calendar such as weekday, holiday, workday for a country.

## Additional details
- Service category: **SERVICE**
- Supported environments: **cloudfoundry**

- [Documentation](https://help.sap.com/docs/WORK_CALENDAR)
- [Discovery Center](https://discovery-center.cloud.sap/serviceCatalog/work-calendar)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  default  |  default  | eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |

## Sample configuration of **Work Calendar** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **workcalendar** by configuring your `usecase.json` file.

### Using the service plan **default**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "workcalendar",
      "plan": "default"
    }
  ]
}
```
