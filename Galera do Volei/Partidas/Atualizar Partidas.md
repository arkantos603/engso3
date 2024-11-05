- **Descrição:** Atualiza as informações de uma partida. **Requer Autenticação**.
- - **Parâmetro de Rota:** `id` Identificador único da partida.
- **Observação:** Apartida só pode ser atualizada pelo seu dono.

**CORPO DA REQUISIÇÃO**
{
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
  
**200 RESPONSE OK**
"Dados alterados com sucesso"

**400 BAD RESPONSE**
Campos obrigatórios ausentes ou em formato incorreto 

**401 RESPONSE UNAUTHORIZED**
"Sem autorização"

[[Partidas Rotas.canvas|Partidas Rotas]]