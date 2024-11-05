**Descrição:** Remove um jogador do sistema. **Requer Autenticação**.
Observação: Somente o jogador pode remover sua conta, ou o próprio sistema por motivos diversos.

DELETE/`jogadores/{id}`

**204 RESPONSE NO CONTENT**
"A operação de exclusão foi bem-sucedida, e não há conteúdo adicional para retornar"

**400 RESPONSE UNAUTHORIZED**
"A requisição contém parâmetros inválidos. Isso pode ocorrer se, por exemplo, o ID do jogador não estiver no formato esperado ou não for encontrado."

**401 RESPONSE UNAUTHORIZED**
"Sem autorização"

[[Jogadores Rotas.canvas|Jogadores Rotas]]