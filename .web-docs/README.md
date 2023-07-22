The 1&1 Packer Plugin is able to create virtual machines for [1&1](https://www.1and1.com/). The plugin
comes with a single builder:

### Installation

Packer v1.7.0 and later

```hcl
packer {
  required_plugins {
    name = {
      version = "~> 1"
      source  = "github.com/hashicorp/oneandone"
    }
  }
}
```

### Components

#### Builders
- [1&1 Builder](/packer/integrations/BrandonRomano/oneandone/latest/components/builder/oneandone)

