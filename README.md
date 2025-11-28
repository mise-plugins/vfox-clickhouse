# vfox-clickhouse

A [vfox](https://github.com/version-fox/vfox) plugin for [ClickHouse](https://clickhouse.com) - the fast, open-source column-oriented database management system.

## Installation

```bash
mise use vfox:mise-plugins/vfox-clickhouse@latest
```

Or add to your `mise.toml`:

```toml
[tools]
"vfox:mise-plugins/vfox-clickhouse" = "latest"
```

## Usage

```bash
# Start clickhouse local (no server needed)
clickhouse-local

# Start clickhouse client
clickhouse-client

# Check version
clickhouse --version
```

## Versions

This plugin installs stable and LTS releases only. Version format: `X.Y.Z.N-stable` or `X.Y.Z.N-lts`.

## Platform Support

- macOS (x86_64 and arm64)
- Linux (x86_64 and arm64)

## License

MIT
