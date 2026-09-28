# Softeca

Índice público de nomes e versões de software Windows. Sem instalador.

A varredura semanal não tem o código do site. Ela baixa estes dois arquivos.

- `indice.json` é a lista completa em 26 de setembro de 2026, já com a leva daquele dia. Não regrave este arquivo.
- `live.json` é o que mudou depois dessa data. O site publicado lê este arquivo.

Para obter a lista atual: comece por `indice.json` e aplique `live.json`.

- `versions`: id da ficha para a versão mais nova, acumulado. Não apague as semanas anteriores.
- `add`: fichas novas depois de 26/09, cada uma `[id, nome, versão, referência, seção, requisições]`.
- `bumps`: só a última leva, `[id, versão anterior, versão atual]`. Não reaplique isso em cima do índice.
- `added`: ids novos dessa mesma leva.
- `scan`: rótulo da leva, por exemplo `28 de setembro de 2026`.

`indice.json` traz `sections` (id da seção para o nome em português) e `items` com as colunas `id`, `nome`, `versao`, `referencia`, `secao`, `requisicoes`.
