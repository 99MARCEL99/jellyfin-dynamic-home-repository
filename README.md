# Dynamic Home – Jellyfin Plugin Repository

This public repository distributes the **Dynamic Home** server plugin for Jellyfin.

## Repository URL

Add the following URL under **Dashboard → Plugins → Repositories**:

```text
https://github.com/99MARCEL99/jellyfin-dynamic-home-repository/raw/refs/heads/main/manifest.json
```

After saving the repository, open the plugin catalog, select **Dynamic Home**, install it and restart Jellyfin.

## Compatibility

- Plugin version: `1.0.1.17`
- Jellyfin ABI: `10.11.0.0` and compatible Jellyfin 10.11 patch releases
- Package SHA-256: `3eedc4865fecdd73f96ff405c0843526347b8bada78012f2f4fe97e828d4bab9`

## Jellyfin Web integration

Version `1.0.1.17` includes a self-contained, self-healing browser client compiled against the Jellyfin `10.11.0` ABI. After installation and a Jellyfin restart, the plugin injects this client into a non-cacheable HTML response without modifying or replacing Jellyfin Web files. Surprise starts as a compact button and opens its responsive filters in an overlay, so following rows stay in place; a second click or Escape closes it again.
