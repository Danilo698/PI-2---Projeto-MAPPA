# US12 — Identificação de trechos críticos de acidentes

## História de usuário

Como gestor de segurança viária, quero identificar os trechos de rodovias com maior concentração de acidentes, para apoiar a definição de prioridades de prevenção e fiscalização.

## Requisito relacionado

**RF12:** Identificar e destacar trechos rodoviários com concentração de acidentes nos dados analisados.

## Prioridade

**Could** — funcionalidade desejável para evolução do produto, não obrigatória para o MVP.

## Planejamento

Evolução futura do MAPPA, sem Sprint de implementação definida.

**Situação:** proposta de funcionalidade, sujeita à avaliação técnica e à disponibilidade da equipe.

## Descrição

Desenvolver um recurso que permita identificar segmentos de rodovias federais com maior concentração de acidentes registrados nos dados da Polícia Rodoviária Federal (PRF).

A análise deverá considerar a rodovia, a localização dos acidentes e o período selecionado, utilizando critérios de agrupamento documentados.

Os trechos identificados poderão ser apresentados em tabela, ranking ou mapa, conforme a viabilidade técnica.

A concentração de acidentes não deverá ser apresentada automaticamente como medida de risco, pois isso exigiria considerar outros fatores, como o volume de tráfego.

## Critérios de aceitação

- [ ] O sistema permite identificar trechos com maior quantidade de acidentes.
- [ ] O critério utilizado para delimitar os trechos está documentado.
- [ ] O usuário consegue consultar a rodovia e a localização dos trechos identificados.
- [ ] A análise considera o período selecionado.
- [ ] Os resultados apresentam a quantidade de acidentes por trecho.
- [ ] Os trechos são apresentados em ordem de concentração de acidentes.
- [ ] O sistema informa quando não existem dados suficientes para a análise.
- [ ] As limitações da identificação dos trechos críticos são apresentadas ao usuário.

## Tarefas técnicas propostas

- [ ] Verificar a disponibilidade e a qualidade dos dados de localização da PRF.
- [ ] Definir o critério de segmentação das rodovias.
- [ ] Implementar o agrupamento dos acidentes por trecho.
- [ ] Calcular a quantidade de acidentes em cada segmento.
- [ ] Criar uma visualização dos resultados.
- [ ] Integrar a análise aos filtros existentes.
- [ ] Validar os resultados com amostras dos dados.
- [ ] Documentar as limitações e registrar evidências dos testes.

## Dependências

- US01 — Consulta e filtros.
- US03 — Tratamento dos dados da PRF.
- US05 — Mapa geográfico, caso seja adotada visualização cartográfica.

## Evidências de conclusão

A conclusão deverá ser comprovada por testes de agrupamento, conferência das quantidades de acidentes e registros da visualização desenvolvida.

**Estado atual:** Issue #12 cadastrada no GitHub. Implementação não verificada.
