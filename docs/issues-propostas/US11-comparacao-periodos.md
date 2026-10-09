# US11 — Comparação de indicadores entre períodos

## História de usuário

Como pesquisador ou gestor, quero comparar indicadores de acidentes entre dois períodos selecionados, para identificar mudanças e tendências na segurança viária.

## Requisito relacionado

**RF11:** Permitir a comparação dos indicadores de acidentes entre dois períodos selecionados pelo usuário.

## Prioridade

**Should** — funcionalidade importante, mas não indispensável para o MVP.

## Sprint proposta

Sprint 05 — 19/10/2026 a 30/11/2026.

**Situação:** proposta de implementação, condicionada à capacidade da equipe e à conclusão das funcionalidades prioritárias.

## Descrição

Disponibilizar no dashboard MAPPA um recurso para selecionar dois períodos distintos e comparar os principais indicadores de acidentes registrados nos dados da Polícia Rodoviária Federal (PRF).

A comparação deverá facilitar a identificação de aumentos, reduções e tendências, respeitando os filtros disponíveis no sistema.

## Critérios de aceitação

- [ ] O usuário consegue selecionar dois períodos para comparação.
- [ ] O dashboard apresenta os indicadores correspondentes a cada período.
- [ ] O sistema calcula a diferença absoluta entre os indicadores comparados.
- [ ] O sistema apresenta a variação percentual quando o cálculo for aplicável.
- [ ] Os filtros de rodovia e localização são considerados na comparação.
- [ ] O sistema informa quando não existem dados para um dos períodos.
- [ ] A apresentação permite identificar claramente qual resultado pertence a cada período.

## Tarefas técnicas propostas

- [ ] Definir os indicadores que poderão ser comparados.
- [ ] Implementar a seleção dos dois períodos.
- [ ] Aplicar os filtros aos dados de cada período.
- [ ] Calcular diferenças absolutas e percentuais.
- [ ] Implementar a visualização comparativa no Streamlit.
- [ ] Tratar períodos sem registros e situações de divisão por zero.
- [ ] Testar os cálculos e registrar evidências.

## Dependências

- US01 — Consulta e filtros.
- US02 — Indicadores consolidados.
- US03 — Tratamento dos dados da PRF.

## Evidências de conclusão

A conclusão deverá ser comprovada por testes dos cálculos, verificação dos indicadores apresentados e registros da interface comparativa.

**Estado atual:** Issue #11 cadastrada no GitHub. Implementação não verificada.
