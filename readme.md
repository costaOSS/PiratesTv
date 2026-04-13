# India Only IPTV - PiratesTV Fork

Automated India-only IPTV playlist that syncs from upstream sources.

## Playlist URL

```
https://raw.githubusercontent.com/costaOSS/PiratesTv/main/combined_playlist.m3u
```

## Features

- Filters only Indian channels from PiratesTV upstream
- Removes Bangladeshi, Pakistani, Arabic, and other non-Indian channels
- Combines India streams from iptv-org/iptv
- Auto-updates daily at 02:00 UTC via GitHub Actions

## Sources

Primary upstream: https://github.com/FunctionError/PiratesTv
Additional: https://github.com/iptv-org/iptv (India streams only)

## Automation

- Runs daily at 02:00 UTC via GitHub Actions
- Can be manually triggered via workflow_dispatch

## License

AGPL v3