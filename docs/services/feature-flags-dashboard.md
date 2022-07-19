# **feature-flags-dashboard** (Feature Flags)

Service category: **APPLICATION**

View and manage Feature Flags Service instances. Get information about flags status, usage and history. Also perform tasks, such as enabling, disabling, adding and removing flags.

## Additional details


## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  dashboard  |  Dashboard  | ch20 - cf-ch20<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> jp20 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)<br> ap21 - Singapore<br> ap10 - Australia (Sydney)<br> us20 - US West (WA)<br> us21 - US East (VA)<br> ap11 - Singapore<br> ap12 - South Korea (Seoul)<br> us30 - US Central (IA)<br> ca10 - Canada (Montreal)<br> jp10 - Japan (Tokyo)<br> br10 - Brazil (Sao Paulo)<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> eu20 - Europe (Netherlands)<br> ap20 - Australia (Sydney) Azure  |

## Sample configuration of **Feature Flags** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **feature-flags-dashboard** by configuring your `usecase.json` file.

### Using the service plan **dashboard** (Dashboard)

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "APPLICATION",
      "name": "feature-flags-dashboard",
      "plan": "dashboard"
    }
  ]
}
```
