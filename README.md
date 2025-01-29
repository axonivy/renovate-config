# Renovate Presets

Shared renovate presets of ivyTeam.

https://docs.renovatebot.com/config-presets/


## default

The default preset keeps dependencies up-to-date on master and all release
branches.

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "local>axonivy/renovate-config"
  ]
}
```

## php

This preset is used to update dependencies and auto-merge dev dependencies.

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "local>axonivy/renovate-config:php"
  ]
}
```
