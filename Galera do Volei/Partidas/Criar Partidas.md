- **Descrição:** Cria uma nova partida.
- Observação: Qualquer jogador cadastrado pode criar uma partida.
- O nome da partida será "Vôlei da galera do(a) (nome do usuário)"
- A partida pode ser pública ou privada.
- A partida deve possuir suas próprias regras na descrição.
- Quantidade de vagas e duração de partida.

**201 RESPONSE CREATED**
{
  `"data": "date",`
  `"local": "string",`
 `"horatio": "string",`
  `"tipo": "boolean",`
  `"sexo": "string ",`   ##Para tipo mista
  `"descricao": "string",`
  `"privativa": "boolean",`
  `"capacidade": "number",`
  `"duracao": "number",`
  `"categoria": "string"`
}

**400 BAD RESPONSE**
"Dados incompletos ou inválidos"

**401 RESPONSE UNAUTHORIZED**
"Sem autorização"

[[Partidas Rotas.canvas|Partidas Rotas]]