# MaxMind GeoLite2 Database Hosting

This repository hosts the MaxMind GeoLite2-City database for Prism's geo-location features. The database is automatically updated weekly via GitHub Actions and distributed through GitHub Releases.

## Quick Links

**Latest Database:**

```
https://github.com/blocktrace/maxmind-geoip/releases/latest/download/GeoLite2-City.mmdb
```

**Releases:** [View all releases](https://github.com/blocktrace/maxmind-geoip/releases)

## How It Works

1. **GitHub Actions** runs every Monday at 3 AM UTC
2. Downloads the latest GeoLite2-City database from MaxMind
3. Creates a new GitHub Release with the updated `.mmdb` file
4. Deletes previous releases to keep storage clean
5. The `/releases/latest/download/` URL always points to the newest version
