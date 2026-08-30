# Dynamic Home – Jellyfin Plugin Repository

This public repository distributes the **Dynamic Home** server plugin for Jellyfin.

## Repository URL

Add the following URL under **Dashboard → Plugins → Repositories**:

```text
https://raw.githubusercontent.com/99MARCEL99/jellyfin-dynamic-home-repository/main/manifest.json
```

After saving the repository, open the plugin catalog, select **Dynamic Home**, install it and restart Jellyfin.

## Compatibility

- Plugin version: `1.0.0.0`
- Jellyfin ABI: `10.11.6.0` and compatible Jellyfin 10.11 patch releases
- Package SHA-256: `813c0bdf4b6e6f63e1c358e532928542d8a51b70b1b4b4bcc95eae41ae90023d`

## Jellyfin Web integration

The catalog installs the server plugin. The custom Dynamic Home rows currently also require the matching Jellyfin Web integration. Jellyfin's plugin catalog does not install or replace Jellyfin Web files. Without that integration, the plugin and its API are installed, but the additional rows are not rendered on the home screen.

The source and version-specific integration patches are maintained separately in the private development repository.
