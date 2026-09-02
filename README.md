# Dynamic Home – Jellyfin Plugin Repository

This public repository distributes the **Dynamic Home** server plugin for Jellyfin.

## Repository URL

Add the following URL under **Dashboard → Plugins → Repositories**:

```text
https://github.com/99MARCEL99/jellyfin-dynamic-home-repository/raw/refs/heads/main/manifest.json
```

After saving the repository, open the plugin catalog, select **Dynamic Home**, install it and restart Jellyfin.

## Compatibility

- Plugin version: `1.0.1.16`
- Jellyfin ABI: `10.11.0.0` and compatible Jellyfin 10.11 patch releases
- Package SHA-256: `8024d68168abef77eea6be62527fb52a0d8b8b50f6220f883b9bacee61a46527`

## Jellyfin Web integration

Version `1.0.1.16` includes a self-contained, self-healing browser client compiled against the Jellyfin `10.11.0` ABI. After installation and a Jellyfin restart, the plugin injects this client into a non-cacheable HTML response without modifying or replacing Jellyfin Web files. Episode cards in Continue Watching & Next Up use their normal series poster while retaining the episode target, progress, and deduplication behavior.
