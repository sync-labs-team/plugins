# plugins

English | [Português](README.pt-BR.md) | [Español](README.es.md)

![License: MIT](https://img.shields.io/badge/license-MIT-blue)

The plugin catalog (marketplace) from Sync Labs, named `sync-labs`. One catalog, one command to add it, then you install each plugin by name. This repository holds only the catalog: each plugin lives in its own repository and is fetched from there.

## Add the catalog

Claude Code:

```sh
claude plugin marketplace add sync-labs-team/plugins
claude plugin install sync-relay@sync-labs
```

Codex:

```sh
codex plugin marketplace add sync-labs-team/plugins
codex plugin add sync-relay@sync-labs
```

Or add it from the `/plugin` menu in Claude Code.

## Plugins

| Plugin | What it does | Repository |
|---|---|---|
| `sync-relay` | Keeps the main session delegating and hands a long session over to a fresh one. Claude Code and Codex. | [sync_relay](https://github.com/Sync-Labs-team/sync_relay) |

More plugins are added here as they are released.

## Contributing and security

Issues only, no outside pull requests: see [CONTRIBUTING.md](CONTRIBUTING.md). Security reports go to the repository of the plugin involved: see [SECURITY.md](SECURITY.md).

## License

MIT. See [LICENSE](LICENSE). Each plugin has its own license in its repository.
