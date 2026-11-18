# eventos-industriais

Agenda de palestras, webinars e treinamentos de formação técnica para a indústria brasileira, com as fontes que os promovem. Cada item mostra um selo de acesso: Gratuito, Inscrição, Seletivo, Restrito ou A verificar.

Site: https://projetoindustrial.github.io/eventos-industriais/

## Arquivos
- `index.html`: página única (Agenda, Fontes, Sobre).
- `fontes.json`: 106 fontes de programação (instituição, tema, vertical, formato, selo de acesso, link).
- `eventos.json`: eventos com data. Começa vazio e é preenchido por rodadas de coleta.

## Formato de `eventos.json`
```json
[{
  "id": "evt-0001",
  "fonte_id": "ID da fonte em fontes.json",
  "titulo": "Nome do evento",
  "inicio": "2026-11-20T19:00:00-03:00",
  "fim": "2026-11-20T20:30:00-03:00",
  "modo": "online",
  "cidade": "Cidade/UF (só presencial ou híbrido)",
  "link": "https://página-do-evento",
  "selo": "gratuito",
  "vertical": "Automação",
  "verificado_em": "2026-11-18"
}]
```
`modo`: online, presencial ou hibrido. `selo`: gratuito, inscricao, seletivo, restrito, pago ou verificar. Eventos passados somem da Agenda sozinhos.

Nomes e links pertencem às instituições citadas. Confirme data, horário e vagas na página oficial.
