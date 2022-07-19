# **postgresql** (PostgreSQL)

Service category: **SERVICE**

PostgreSQL on SAP BTP offers an object-relational database management system with many advanced features, such as user-defined types, table inheritance, foreign key referential integrity, Multiversion Concurrency Control (MVCC), and so on.

## Additional details

- [Documentation](https://help.sap.com/viewer/product/PostgreSQL/Cloud/en-US)
- [Tutorial](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/314e0968334d45ab855924497759671b.html)
- [Support](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5dd739823b824b539eee47b7860a00be.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  large  |  large  | in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us30 - US Central (IA)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  xxsmall  |  xxsmall  | in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us30 - US Central (IA)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  xsmall  |  xsmall  | ch20 - cf-ch20<br> ap20 - Australia (Sydney) Azure<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)  |
|  small  |  small  | ch20 - cf-ch20<br> ap20 - Australia (Sydney) Azure<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)  |
|  medium  |  medium  | ch20 - cf-ch20<br> ap20 - Australia (Sydney) Azure<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)  |
|  large  |  large  | ch20 - cf-ch20<br> ap20 - Australia (Sydney) Azure<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)  |
|  medium  |  medium  | in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us30 - US Central (IA)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  small  |  small  | br10 - Brazil (Sao Paulo)  |
|  medium  |  medium  | br10 - Brazil (Sao Paulo)  |
|  xxsmall  |  xxsmall  | br10 - Brazil (Sao Paulo)  |
|  xsmall  |  xsmall  | br10 - Brazil (Sao Paulo)  |
|  small  |  small  | in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us30 - US Central (IA)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  large  |  large  | br10 - Brazil (Sao Paulo)  |
|  xsmall  |  xsmall  | in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us30 - US Central (IA)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  xxsmall  |  xxsmall  | ch20 - cf-ch20<br> ap20 - Australia (Sydney) Azure<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)  |

## Sample configuration of **PostgreSQL** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **postgresql** by configuring your `usecase.json` file.

### Using the service plan **large**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "large"
    }
  ]
}
```

### Using the service plan **xxsmall**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "xxsmall"
    }
  ]
}
```

### Using the service plan **xsmall**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "xsmall"
    }
  ]
}
```

### Using the service plan **small**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "small"
    }
  ]
}
```

### Using the service plan **medium**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "medium"
    }
  ]
}
```

### Using the service plan **large**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "large"
    }
  ]
}
```

### Using the service plan **medium**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "medium"
    }
  ]
}
```

### Using the service plan **small**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "small"
    }
  ]
}
```

### Using the service plan **medium**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "medium"
    }
  ]
}
```

### Using the service plan **xxsmall**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "xxsmall"
    }
  ]
}
```

### Using the service plan **xsmall**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "xsmall"
    }
  ]
}
```

### Using the service plan **small**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "small"
    }
  ]
}
```

### Using the service plan **large**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "large"
    }
  ]
}
```

### Using the service plan **xsmall**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "xsmall"
    }
  ]
}
```

### Using the service plan **xxsmall**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "postgresql",
      "plan": "xxsmall"
    }
  ]
}
```
