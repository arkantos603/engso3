**Descrição:** Dono ou moderador expulsa um jogador de uma partida. **Requer Autenticação e Permissão**.

**200 RESPONSE OK**
{
  `"message": "Jogador removido da partida.",`
  `"jogador_id": "string",`
  `"partida_id": "string"`
}

**400 RESPONSE UNAUTHORIZED**
"A requisição contém parâmetros inválidos. Isso pode ocorrer se, por exemplo, o ID do jogador não estiver no formato esperado ou não for encontrado."

**401 RESPONSE UNAUTHORIZED**
"Sem autorização"

[[Lobby Rotas.canvas|Lobby Rotas]]