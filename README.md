A [ublacklist](https://github.com/iorate/ublacklist) config.

# Usage

- Click "Backup" in the extension setting to obtain the json, and save it to `config.json`.
- Click "Restore" and choose `config.json` to write it back.

# Utilities

## Dependencies

- sh
- [Taskfile](https://taskfile.dev)
- jq
- wget

## Tasks

`task download`
: download all lists to inspect locally.

`task clean`
: delete all downloaded lists.

# References

[Subscriptions | uBlacklist](https://iorate.github.io/ublacklist/subscriptions)
