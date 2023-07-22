The IONOS 1&1 Packer Plugin is able to create virtual machines for IONOS cloud.

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

