**Descrição:** Cria um novo jogador.
**Observações**: Após o cadastro ser concluiído, o jogador se adequa a alguma faixa etária proposta pelo sistema baseado em sua idade.

**CORPO DA REQUISIÇÃO**
{
  `"nome": "string",`
  `"email": "string",`
  `"senha": "string",`
  `"sexo": "string",`
  `"idade": "number",`
  `"categoria": "string"`
}

**201 RESPONSE CREATED**
{
  `"id": "string",`
  `"nome": "string",`
  `"email": "string",`
  `"senha": "string",`
  `"sexo": "string",`
  `"idade": "number",`
  `"faixa_etaria": "string",`
  `"categoria": "string"`
}

**400 BAD RESPONSE**
"Usuário já cadastrado"

[[Jogadores Rotas.canvas|Jogadores Rotas]]