 **Descrição:** Retorna uma lista de partidas, com filtros para tipo de partida (Mista ou Específica) e categoria.
- **Parâmetros de Query:**
    - `tipo`: Filtra partidas pelo tipo. Valores possíveis: "mista" (sem restrição de sexo) ou "especifica" (com restrição de sexo).
    - `sexo`: Define o sexo permitido para partidas do tipo "especifica" ("masculino" ou "feminino"). Ignorado se o tipo for "mista".
    - `categoria`: Filtra partidas por categoria ("amador", "profissional").
    - `em_andamento`: Filtra partidas que já estejam em andamento ou que estejam sendo agendadas.


**200 RESPONSE OK**
  {
    `"id": "string",`
    `"data": "date",`
    `"horario": "string",`
    `"local": "string",`
    `"tipo": "boolean",`
    `"sexo": "string",`  ##Para tipo mista
    `"em_andamento": "boolean",`
    `"descricao": "string",`
	`"privativa": "boolean",`
	`"capacidade": "number",`
	`"duracao": "number",`
    `"categoria": "string"`
  }
  
[[Partidas Rotas.canvas|Partidas Rotas]]
