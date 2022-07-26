# .upmconfig.toml Provider

A Unity Editor extension to configure the `~/.upmconfig.toml` file.

## Installation

Add the following registry to Unity's scoped registries,
and this package to the dependencies.

```json
{
  "scopedRegistries": [
    {
      "name": "npmjs",
      "url": "https://registry.npmjs.org",
      "scopes": [
        "com.kagekirin"
      ]
    }
  ],
  "dependencies": {
    "com.kagekirin.upmconfigprovider": "0.0.2"
  }
}
```
