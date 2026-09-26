# Softeca

Índice público de nomes e versões de software Windows. Sem instalador.

O site lê `live.json`. Esse arquivo guarda só o que mudou depois de 26 de setembro de 2026.

- `versions`: id da ficha para a versão mais nova
- `add`: fichas novas, cada uma `[id, nome, versão, referência, seção, requisições]`
- `bumps`: só a última leva, `[id, versão anterior, versão atual]`
- `added`: ids novos dessa mesma leva
- `scan`: rótulo da leva, por exemplo `26 de setembro de 2026`
