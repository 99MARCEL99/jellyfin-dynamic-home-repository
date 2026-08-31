# Dynamic Home – Jellyfin Plugin Repository

This public repository distributes the **Dynamic Home** server plugin for Jellyfin.

## Repository URL

Add the following URL under **Dashboard → Plugins → Repositories**:

```text
https://github.com/99MARCEL99/jellyfin-dynamic-home-repository/raw/refs/heads/main/manifest.json
```

After saving the repository, open the plugin catalog, select **Dynamic Home**, install it and restart Jellyfin.

## Compatibility

- Plugin version: `1.0.1.8`
- Jellyfin ABI: `10.11.0.0` and compatible Jellyfin 10.11 patch releases
- Package SHA-256: `de36ded126a4b09584a5aff35212740da16a705da2e34bd0ab3a6d71be72fa16`

## Jellyfin Web integration

Version `1.0.1.8` includes a self-contained browser client compiled against the Jellyfin `10.11.0` ABI. After installation and a Jellyfin restart, the plugin injects this client into the served HTML response without modifying or replacing Jellyfin Web files. The home customization control is anchored directly below the banner and remains the first plugin element when the banner is disabled.
