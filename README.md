# mesa-comanda-app-releases

Repositório de **releases** do app `mesa-comanda` do PDV.AI.

Não contém código: só os binários publicados pela pipeline do GitLab
(`umbu.tech/pdv.ai/mesa-comanda-app.pdv`), com uma release por tag.

A Central de Apps (admin.pdv.ai) importa daqui — catálogo, canal e régua de
versão mínima são gerenciados por lá, nunca editando este repositório à mão.

## Convenção de tag

| Tag | Canal |
|---|---|
| `v1.2.3` | produção |
| `v1.2.3-rc` | homologação |
| `v1.2.3-dev` | desenvolvimento |

Este commit existe porque o GitHub recusa criar release em repositório vazio
(`422 Repository is empty`).
