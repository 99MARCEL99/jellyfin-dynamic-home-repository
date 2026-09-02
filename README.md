# Dynamic Home – Jellyfin Plugin Repository

This public repository distributes the **Dynamic Home** server plugin for Jellyfin.

## Repository URL

Add the following URL under **Dashboard → Plugins → Repositories**:

```text
https://github.com/99MARCEL99/jellyfin-dynamic-home-repository/raw/refs/heads/main/manifest.json
```

After saving the repository, open the plugin catalog, select **Dynamic Home**, install it and restart Jellyfin.

## Compatibility

- Plugin version: `1.0.1.15`
- Jellyfin ABI: `10.11.0.0` and compatible Jellyfin 10.11 patch releases
- Package SHA-256: `668fca086221dc1e54440092377a8a1f0ac37c96b05f73c74b806f07433c2013`

## Jellyfin Web integration

Version `1.0.1.15` includes a self-contained, self-healing browser client compiled against the Jellyfin `10.11.0` ABI. After installation and a Jellyfin restart, the plugin injects this client into a non-cacheable HTML response without modifying or replacing Jellyfin Web files. It shows My Media first, then whichever completed row group is ready, restores completed rows on SPA revisits, targets Jellyfin's visible home container and lazy-loads offscreen posters.
