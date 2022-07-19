# **rabbitmq** (RabbitMQ)

Service category: **SERVICE**

RabbitMQ on SAP BTP includes a message broker that implements message queues for application-to-application messaging. Supports Advanced Message Queuing Protocol (AMQP).

## Additional details

- [Documentation](https://help.sap.com/viewer/product/RabbitMQ/Cloud/en-US)
- [Tutorial](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/bf757994794445ed904b97bf1907812a.html)
- [Support](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5dd739823b824b539eee47b7860a00be.html)
- [Support information](https://www.rabbitmq.com/community.html)

## Service availability

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  virtualhost  |  virtualhost  | ap11 - Singapore<br> us20 - US West (WA)<br> ca10 - Canada (Montreal)<br> jp10 - Japan (Tokyo)<br> ap10 - Australia (Sydney)<br> eu20 - Europe (Netherlands)<br> br10 - Brazil (Sao Paulo)<br> us30 - US Central (IA)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  large  |  large  | ch20 - cf-ch20<br> ap20 - Australia (Sydney) Azure<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)  |
|  xsmall  |  xsmall  | ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us30 - US Central (IA)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  medium  |  medium  | ch20 - cf-ch20<br> ap20 - Australia (Sydney) Azure<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)  |
|  xsmall  |  xsmall  | br10 - Brazil (Sao Paulo)  |
|  small  |  small  | br10 - Brazil (Sao Paulo)  |
|  medium  |  medium  | br10 - Brazil (Sao Paulo)  |
|  large  |  large  | br10 - Brazil (Sao Paulo)  |
|  small  |  small  | ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us30 - US Central (IA)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  medium  |  medium  | in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us30 - US Central (IA)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |
|  xsmall  |  xsmall  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)  |
|  small  |  small  | ch20 - cf-ch20<br> in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap20 - Australia (Sydney) Azure<br> us21 - US East (VA)<br> ap21 - Singapore<br> jp20 - Japan (Tokyo)<br> us20 - US West (WA)<br> eu20 - Europe (Netherlands)  |
|  large  |  large  | in30 - India (Mumbai)<br> eu30 - Europe (Frankfurt)<br> ap12 - South Korea (Seoul)<br> eu11 - Europe (Frankfurt) EU Access - AWS<br> ca10 - Canada (Montreal)<br> ap11 - Singapore<br> ap10 - Australia (Sydney)<br> us30 - US Central (IA)<br> jp10 - Japan (Tokyo)<br> us10 - US East (VA)<br> eu10 - Europe (Frankfurt)  |

## Sample configuration of **RabbitMQ** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **rabbitmq** by configuring your `usecase.json` file.

### Using the service plan **virtualhost**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "rabbitmq",
      "plan": "virtualhost"
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
      "name": "rabbitmq",
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
      "name": "rabbitmq",
      "plan": "xsmall"
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
      "name": "rabbitmq",
      "plan": "medium"
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
      "name": "rabbitmq",
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
      "name": "rabbitmq",
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
      "name": "rabbitmq",
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
      "name": "rabbitmq",
      "plan": "large"
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
      "name": "rabbitmq",
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
      "name": "rabbitmq",
      "plan": "medium"
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
      "name": "rabbitmq",
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
      "name": "rabbitmq",
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
      "name": "rabbitmq",
      "plan": "large"
    }
  ]
}
```
