# plugins

[English](README.md) | [Português](README.pt-BR.md) | Español

![License: MIT](https://img.shields.io/badge/license-MIT-blue)

El catálogo de plugins (marketplace) de Sync Labs, con el nombre `sync-labs`. Un catálogo, un comando para añadirlo, y cada plugin se instala por su nombre. Este repositorio guarda solo el catálogo: cada plugin vive en su propio repositorio y se descarga desde allí.

## Añadir el catálogo

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

## Instalar desde el menú

Claude Code: escribe `/plugin`, abre **Marketplaces**, elige **Add marketplace** e introduce `sync-labs-team/plugins`. Después abre **Discover**, elige un plugin y el ámbito de instalación.

Codex: en la app, abre el directorio de plugins, elige el marketplace `Sync Labs` e instala desde allí.

## Plugins

| Plugin | Qué hace | Repositorio |
|---|---|---|
| `sync-relay` | Mantiene la sesión principal delegando y pasa una sesión larga a una nueva. Claude Code y Codex. | [sync_relay](https://github.com/Sync-Labs-team/sync_relay) |

Los plugins nuevos se añaden aquí según salgan.

## Contribuir y seguridad

Solo issues, sin pull requests externos: mira [CONTRIBUTING.md](CONTRIBUTING.md). Los avisos de seguridad van al repositorio del plugin afectado: mira [SECURITY.md](SECURITY.md).

## Licencia

MIT. Mira [LICENSE](LICENSE). Cada plugin tiene su propia licencia en su repositorio.
