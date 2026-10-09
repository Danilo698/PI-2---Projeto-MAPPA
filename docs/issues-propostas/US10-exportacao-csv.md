# US10 — Exportação dos resultados filtrados em CSV

## História de usuário

Como pesquisador, quero exportar os resultados filtrados em CSV, para utilizar os dados em análises e relatórios.

## Requisito relacionado

**RF10:** Permitir a exportação dos dados resultantes dos filtros aplicados para arquivo CSV.

## Prioridade

**Should** — funcionalidade importante, mas não indispensável para o MVP.

## Sprint proposta

Sprint 05 — 19/10/2026 a 30/11/2026.

**Situação:** proposta de implementação, condicionada à capacidade da equipe e à conclusão das funcionalidades prioritárias.

## Descrição

Adicionar ao dashboard MAPPA uma opção para baixar os dados correspondentes aos filtros selecionados pelo usuário.

O arquivo deverá utilizar o formato CSV, permitindo sua abertura em ferramentas de análise de dados e planilhas eletrônicas.

## Critérios de aceitação

- [ ] O dashboard apresenta uma opção para exportar os resultados em CSV.
- [ ] O arquivo exportado contém apenas os registros correspondentes aos filtros aplicados.
- [ ] Os nomes das colunas são apresentados de forma compreensível.
- [ ] O arquivo pode ser aberto em uma ferramenta de planilhas.
- [ ] A exportação funciona corretamente quando diferentes filtros são combinados.
- [ ] O sistema informa quando não existem registros disponíveis para exportação.

## Tarefas técnicas propostas

- [ ] Identificar o conjunto de dados utilizado pelo dashboard após a aplicação dos filtros.
- [ ] Implementar a geração do arquivo CSV.
- [ ] Adicionar o recurso de download à interface Streamlit.
- [ ] Verificar a codificação e a estrutura do arquivo exportado.
- [ ] Testar a exportação com filtros individuais e combinados.
- [ ] Registrar evidências do funcionamento.

## Dependências

- US01 — Consulta e filtros.
- US03 — Tratamento dos dados da PRF.
- US07 — Filtros combinados.

## Evidências de conclusão

A conclusão deverá ser comprovada por testes de exportação e pela verificação do conteúdo dos arquivos CSV gerados.

**Estado atual:** Issue #10 cadastrada no GitHub. Implementação não verificada.
