# Sprint 03 — Registro 01: Planejamento do ranking, mapa e filtros

**Situação:** Registro retrospectivo de análise e planejamento. Reunião formal não comprovada.

## Data

Data da elaboração do registro: a preencher.

Período de referência da Sprint: 14/09/2026 a 27/09/2026.

## Participantes

Organização técnica individual. Participação e validação dos demais integrantes: a confirmar.

## Pauta

- Planejamento do ranking de rodovias por ocorrências.
- Organização da visualização geográfica dos acidentes.
- Análise dos filtros combinados.
- Revisão das histórias US04, US05 e US07.
- Identificação das dependências entre dados tratados e visualizações.

## Análise técnica

A Sprint 03 prevê o desenvolvimento de funcionalidades destinadas à análise comparativa e geográfica dos acidentes registrados pela Polícia Rodoviária Federal (PRF).

**US04 — Ranking de rodovias por ocorrências**

Planejar uma classificação das rodovias conforme a quantidade de acidentes, permitindo identificar aquelas com maior número de registros.

**US05 — Mapa geográfico das ocorrências**

Planejar a representação das ocorrências em um mapa, utilizando as informações geográficas disponíveis na base de dados.

**US07 — Filtros combinados**

Planejar a utilização conjunta dos filtros disponíveis, mantendo a consistência dos indicadores, gráficos, ranking e mapa.

A implementação dessas funcionalidades e sua integração com o dashboard deverão ser verificadas no código e nas evidências do projeto.

## Decisões e definições

**Propostas de organização técnica:**

- Utilizar os dados tratados pelo ETL como referência para o ranking e o mapa.
- Verificar a disponibilidade e a qualidade das coordenadas geográficas.
- Manter critérios consistentes de filtragem entre as diferentes visualizações.
- Utilizar os critérios de aceitação das histórias US04, US05 e US07 para orientar a validação.

Validação coletiva: pendente.

## Encaminhamentos

- Conferir a estrutura do protótipo existente.
- Identificar os campos necessários ao ranking de rodovias.
- Verificar a disponibilidade das informações geográficas.
- Analisar o comportamento esperado dos filtros combinados.
- Identificar funcionalidades implementadas e pendências.
- Preparar os critérios de verificação para a revisão da Sprint 03.

## Impedimentos

- Ausência de registro contemporâneo de reunião formal.
- Participação limitada da equipe.
- Necessidade de verificar o estado real das funcionalidades no protótipo.
- Possíveis limitações na qualidade dos dados geográficos, ainda não verificadas.

## Links

- `docs/requisitos.md`
- `docs/backlog.md`
- `docs/arquitetura.md`
- `sprints/sprint-03.md`
- `sprints/cronograma-sprints.md`