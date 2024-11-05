**Descrição:** Mostra os detalhes de uma partida específica, incluindo lista de jogadores confirmados.

**200 RESPONSE OK**
{
  `"id": "string",`
  `"data": "string",`
  `"hora": "string",`
  `"local": "string",`
  `"status": "string", // ex: "agendada", "em_curso"`
   `"tipo": "boolean",`
  `"sexo": "string ",`   ##Para tipo mista
  `"categoria": "string",`
  "jogadores_confirmados": [
    {
	  `"nome": "string",`
	  `"sexo": "string",`
	  `"idade": "number",`
	  `"faixa_etaria": "string",`
	  `"categoria": "string"`
    }
  ]
}

[[Lobby Rotas.canvas|Lobby Rotas]]