# Dynamic Home – Jellyfin Plugin Repository

This public repository distributes the **Dynamic Home** server plugin for Jellyfin.

## Repository URL

Add the following URL under **Dashboard → Plugins → Repositories**:

```text
https://github.com/99MARCEL99/jellyfin-dynamic-home-repository/raw/refs/heads/main/manifest.json
```

After saving the repository, open the plugin catalog, select **Dynamic Home**, install it and restart Jellyfin.

## Compatibility

- Plugin version: `1.0.1.0`
- Jellyfin ABI: `10.11.0.0` and compatible Jellyfin 10.11 patch releases
- Package SHA-256: `1f123c74ccb05cded508c9e9cf1d354864652f64d006743183643112b0dc7fef`

## Jellyfin Web integration

Version `1.0.1.0` includes a self-contained browser client. After installation and a Jellyfin restart, the plugin injects this client into the served HTML response without modifying or replacing Jellyfin Web files. A hard browser refresh may be required after upgrading from `1.0.0.0`.
