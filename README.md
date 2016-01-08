# chef-wrapper-ntp-cookbook

Wrapper cookbook to set the NTP servers on a node.

## Supported Platforms

Ubuntu 14.04

## Usage

### chef-wrapper-ntp::default

Include `chef-wrapper-ntp` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[chef-wrapper-ntp::default]"
  ]
}
```

## License and Authors

Author:: Cobus Bernard (<me@cobus.io>)
