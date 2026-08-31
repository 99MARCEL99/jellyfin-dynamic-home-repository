# Dynamic Home – Jellyfin Plugin Repository

This public repository distributes the **Dynamic Home** server plugin for Jellyfin.

## Repository URL

Add the following URL under **Dashboard → Plugins → Repositories**:

```text
https://github.com/99MARCEL99/jellyfin-dynamic-home-repository/raw/refs/heads/main/manifest.json
```

After saving the repository, open the plugin catalog, select **Dynamic Home**, install it and restart Jellyfin.

## Compatibility

- Plugin version: `1.0.1.10`
- Jellyfin ABI: `10.11.0.0` and compatible Jellyfin 10.11 patch releases
- Package SHA-256: `1cc514c5ee8a87d2077e1c6dcfb3f741f924cdaac0cf031e73c4be76dff5847c`

## Jellyfin Web integration

Version `1.0.1.10` includes a self-contained browser client compiled against the Jellyfin `10.11.0` ABI. After installation and a Jellyfin restart, the plugin injects this client into the served HTML response without modifying or replacing Jellyfin Web files. The client now also exits cleanly when Dynamic Home is globally disabled, without hiding Jellyfin's original home or creating a request loop.
