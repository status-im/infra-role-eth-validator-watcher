# Description

This role deploys [Eth Validator Watcher](https://github.com/kilnfi/eth-validator-watcher?tab=readme-ov-file), a program made to monitor Ethereum validators .

# Configuration

```yaml
eth_val_watcher_bn_network: 'beacon_network'
eth_val_watcher_bn_url: 'http://beacon:5051/'
eth_val_watcher_validators:
  - public_key: '0x...'
    labels: ['nimbus', 'stable']
  - public_key: '0x...'
    labels: ['nimbus', 'testing']
```
