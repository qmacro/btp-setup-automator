# hyperledger-fabric (Hyperledger Fabric)

The Hyperledger Fabric service on SAP BTP lets you provision a Hyperledger Fabric node and join it to a network of nodes. Hyperledger Fabric supports Enterprise ready blockchain with smart contracts.

## Additional details
- Service category: SERVICE
- Supported environments: cloudfoundry, kymaruntime, sapbtp

- [Documentation](https://help.sap.com/viewer/p/HYPERLEDGER_FABRIC/)
- [Support](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5dd739823b824b539eee47b7860a00be.html)

## Service availability in data centers

| Plan name | Display name | Data center availability  |
|------|----------------|---------------------------|
|  testnet  |  testnet  | eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |
|  dev  |  dev  | eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |
|  backbone  |  backbone  | eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |
|  cyon  |  cyon  | eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |
|  node  |  node  | eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |
|  channel  |  channel  | eu10 - Europe (Frankfurt)<br> us10 - US East (VA)  |

## Sample configuration of **Hyperledger Fabric** for btp-setup-automator

The [btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) helps you setting up your SAP BTP account for a specific use case. Each use case is defined inside a `usecase.json` file listing all the services necessary to cover that use case. You can find a list of released use cases in the [usecase folder of bpt-setup-automator](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases).

You can setup a service instance for **hyperledger-fabric** by configuring your `usecase.json` file.

### Using the service plan **testnet**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hyperledger-fabric",
      "plan": "testnet"
    }
  ]
}
```

### Using the service plan **dev**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hyperledger-fabric",
      "plan": "dev"
    }
  ]
}
```

### Using the service plan **backbone**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hyperledger-fabric",
      "plan": "backbone"
    }
  ]
}
```

### Using the service plan **cyon**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hyperledger-fabric",
      "plan": "cyon", 
      "parameters" : { 
        "consortium": "\u003c name of the consortium \u003e",
        "ordererAdmin": {"certificate": "\u003c (optional) orderer user certificate\u003e ", "key": "\u003c (optional) orderer user key \u003e"},
        "ordererOrg": "\u003c (optional) orderer org name \u003e",
        "ordererTlsCaCertificate": "\u003c TLS CA certificate of the orderer org \u003e",
        "orderers": ["\u003c (optional) orderer url:port \u003e"],
        "peerAdmin": {"certificate": "\u003c peer user certificate\u003e ", "key": "\u003c peer user key \u003e"},
        "peerCaCertificate": "\u003c (optional) peer ca certificate \u003e",
        "peerCertificateAuthority": {"certificate": "\u003c (optional) certificate authority certificate\u003e ", "certificateChain": "\u003c (optional) certificate authority certificate chain \u003e", "key": "\u003c (optional) certificate authority private key \u003e"},
        "peerOrg": "\u003c peer org name \u003e",
        "peerTlsCaCertificate": "\u003c TLS CA certificate of the peer org \u003e",
        "peers": ["\u003c peer url:port \u003e"]
      }
    }
  ]
}
```

### Using the service plan **node**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hyperledger-fabric",
      "plan": "node"
    }
  ]
}
```

### Using the service plan **channel**

```json
{
  "$schema": "https://raw.githubusercontent.com/SAP-samples/btp-setup-automator/main/libs/btpsa-usecase.json",
  "services": [
    {
      "category": "SERVICE",
      "name": "hyperledger-fabric",
      "plan": "channel", 
      "parameters" : { 
        "channelId": "\u003c the channel that should be imported \u003e",
        "channelSecret": "\u003c the channel secret \u003e",
        "comment": "\u003c user defined comment \u003e"
      }
    }
  ]
}
```
