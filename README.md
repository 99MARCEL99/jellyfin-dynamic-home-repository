# Dynamic Home – Jellyfin Plugin Repository

This public repository distributes the **Dynamic Home** server plugin for Jellyfin.

## Repository URL

Add the following URL under **Dashboard → Plugins → Repositories**:

```text
https://github.com/99MARCEL99/jellyfin-dynamic-home-repository/raw/refs/heads/main/manifest.json
```

After saving the repository, open the plugin catalog, select **Dynamic Home**, install it and restart Jellyfin.

## Compatibility

- Plugin version: `1.0.1.4`
- Jellyfin ABI: `10.11.0.0` and compatible Jellyfin 10.11 patch releases
- Package SHA-256: `3aa427cc7dd25b44fe80437ad89bce13bc6ef436c3fff09cec0e0ce1b586b9d4`

## Jellyfin Web integration

Version `1.0.1.4` includes a self-contained browser client compiled against the Jellyfin `10.11.0` ABI. After installation and a Jellyfin restart, the plugin injects this client into the served HTML response without modifying or replacing Jellyfin Web files. It migrates the former eight-row default to 20, resets only unversioned legacy user exclusions, and takes precedence over stale legacy Dynamic Home web sections. Newly saved user choices remain persistent.
