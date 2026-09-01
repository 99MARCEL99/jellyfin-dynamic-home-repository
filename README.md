# Dynamic Home – Jellyfin Plugin Repository

This public repository distributes the **Dynamic Home** server plugin for Jellyfin.

## Repository URL

Add the following URL under **Dashboard → Plugins → Repositories**:

```text
https://github.com/99MARCEL99/jellyfin-dynamic-home-repository/raw/refs/heads/main/manifest.json
```

After saving the repository, open the plugin catalog, select **Dynamic Home**, install it and restart Jellyfin.

## Compatibility

- Plugin version: `1.0.1.13`
- Jellyfin ABI: `10.11.0.0` and compatible Jellyfin 10.11 patch releases
- Package SHA-256: `ef06b0456ffaf87abd19ffbc693209f77eb2fc634906a874b32c043661f0618a`

## Jellyfin Web integration

Version `1.0.1.13` includes a self-contained, self-healing browser client compiled against the Jellyfin `10.11.0` ABI. After installation and a Jellyfin restart, the plugin injects this client into a non-cacheable HTML response without modifying or replacing Jellyfin Web files. It preserves mounts requested during navigation, retries temporary failures, applies every admin section switch and exits cleanly when Dynamic Home is globally disabled.
