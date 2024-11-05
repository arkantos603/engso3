 **Descrição:** Atualiza as informações de um jogador existente. **Requer Autenticação**.
 **Parâmetro de Rota:** `id` Identificador do jogador.

**CORPO DA REQUISIÇÃO**
{
  `"nome": "string",`
  `"email": "string",`
  `"senha": "string",`
  `"categoria": "string"`
}

**200 RESPONSE OK**
"Dados alterados com sucesso"

**400 BAD RESPONSE**
Campos obrigatórios ausentes ou em formato incorreto 

**401 RESPONSE UNAUTHORIZED**
"Sem autorização"

[[Jogadores Rotas.canvas|Jogadores Rotas]]