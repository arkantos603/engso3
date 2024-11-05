**Descrição:** Retorna uma lista de jogadores, com opções de filtros, ordenação e busca.

**Parâmetros de Query**
- `sexo` : Filtra jogadores por sexo ("masculino", "feminino").
- `faixa_etaria` : Filtra jogadores por faixa etária ("sub-21").
- `categoria` : Filtra jogadores por categoria ("amador", "profissional").
- `search` : Busca jogadores por nome, faixa etária ou categoria.
- `sortBy` : Define o campo para ordenar ("nome", "faixa_etaria").
- `order` : Define a ordem ("asc" para ascendente ou "desc" para descendente).

**200 RESPONSE OK**
  {
    `"id": "string",`
    `"nome": "string",`
    `"sexo": "string",`
    `"idade": "number",`
    `"faixa_etaria": "string",`
    `"categoria": "string"`
  }
[[Jogadores Rotas.canvas|Jogadores Rotas]]