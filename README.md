# Veera Renovate Config

Shared Renovate presets for all repositories.

Configuration is based on standard Renovate config
https://docs.renovatebot.com/renovate-schema.json

## Default Usage

### Using Base configuration file
In your repo’s `renovate.json`:

```json
{
  "extends": ["github>veera-dao/renovate-configs"]

}
```

### Using language specific configuration file (Typescipt as example)
In your repo’s `renovate.json`:

```json
{
  "extends": ["github>veera-dao/renovate-configs:typescript"]

}
