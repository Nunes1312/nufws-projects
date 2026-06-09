# NuFws Projects — repositorio da nuvem

Este repositorio **publico** guarda o catalogo e os projetos do app NuFws Projects.

- `catalog.json` — lista dos projetos (o app le este arquivo).
- `projects/` — os zips de cada projeto (ex.: `projects/<id>.zip`).

O app publica/atualiza estes arquivos automaticamente (modo admin, com token) ou
voce sobe manualmente. Os usuarios recebem ao clicar em **Sincronizar** no app.

> Para a auto-atualizacao do app, publique tambem em **Releases** o instalador NSIS
> (`NuFws-Projects-Setup.exe`) e o `latest.yml` gerados pelo `npm run dist:nsis`.
