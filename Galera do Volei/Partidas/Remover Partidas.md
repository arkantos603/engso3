- **Descrição:** Remove uma partida do sistema. **Requer Autenticação**.
- Observação: A partida só pode ser removida pelo seu dono ou pelo sistema, caso a mesma viole alguma regra.

DELETE/`partidas/{id}`

**204 RESPONSE NO CONTENT**
"A operação de exclusão foi bem-sucedida, e não há conteúdo adicional para retornar"

**400 RESPONSE UNAUTHORIZED**
"A requisição contém parâmetros inválidos. Isso pode ocorrer se, por exemplo, o ID da partida não estiver no formato esperado ou não for encontrado."

**401 RESPONSE UNAUTHORIZED**
"Sem autorização"

[[Partidas Rotas.canvas|Partidas Rotas]]