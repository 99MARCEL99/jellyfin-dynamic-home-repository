# Dynamic Home – Jellyfin Plugin Repository

This public repository distributes the **Dynamic Home** server plugin for Jellyfin.

## Repository URL

Add the following URL under **Dashboard → Plugins → Repositories**:

```text
https://github.com/99MARCEL99/jellyfin-dynamic-home-repository/raw/refs/heads/main/manifest.json
```

After saving the repository, open the plugin catalog, select **Dynamic Home**, install it and restart Jellyfin.

## Compatibility

- Plugin version: `1.0.1.1`
- Jellyfin ABI: `10.11.0.0` and compatible Jellyfin 10.11 patch releases
- Package SHA-256: `e070fa4954a9f876e88a06385dffc23ef5581a8600b2f14f7bf212c4ba509800`

## Jellyfin Web integration

Version `1.0.1.1` includes a self-contained browser client compiled against the Jellyfin `10.11.0` ABI. After installation and a Jellyfin restart, the plugin injects this client into the served HTML response without modifying or replacing Jellyfin Web files. A hard browser refresh may be required after upgrading from an earlier build.
