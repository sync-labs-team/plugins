# plugins

[English](README.md) | Português | [Español](README.es.md)

![License: MIT](https://img.shields.io/badge/license-MIT-blue)

O catálogo de plugins (marketplace) da Sync Labs, com o nome `sync-labs`. Um catálogo, um comando para adicioná-lo, e cada plugin se instala pelo nome. Este repositório guarda só o catálogo: cada plugin mora no repositório dele e é baixado de lá.

## Adicionar o catálogo

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

Ou adicione pelo menu `/plugin` do Claude Code.

## Plugins

| Plugin | O que faz | Repositório |
|---|---|---|
| `sync-relay` | Mantém a sessão principal delegando e passa uma sessão longa para uma nova. Claude Code e Codex. | [sync_relay](https://github.com/Sync-Labs-team/sync_relay) |

Novos plugins entram aqui conforme saem.

## Contribuir e segurança

Só issues, sem pull request de fora: veja [CONTRIBUTING.md](CONTRIBUTING.md). Relato de segurança vai para o repositório do plugin envolvido: veja [SECURITY.md](SECURITY.md).

## Licença

MIT. Veja [LICENSE](LICENSE). Cada plugin tem a licença própria no repositório dele.
