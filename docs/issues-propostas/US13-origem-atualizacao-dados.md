# US13 — Origem e atualização dos dados

## História de usuário

Como pesquisador ou gestor, quero consultar a origem dos dados e a data de sua última atualização, para compreender a procedência e a atualidade das informações apresentadas no dashboard.

## Requisito relacionado

**RF13:** Exibir a fonte dos dados utilizados e a data de sua última atualização.

## Prioridade

**Should** — funcionalidade importante para a transparência e confiabilidade das informações.

## Sprint proposta

Sprint 05 — 19/10/2026 a 30/11/2026.

**Situação:** proposta de implementação, condicionada à capacidade da equipe e à conclusão das funcionalidades prioritárias.

## Descrição

Disponibilizar no dashboard MAPPA informações sobre a procedência dos dados utilizados nas análises.

O sistema deverá identificar a Polícia Rodoviária Federal (PRF) como fonte dos registros de acidentes, quando essa for efetivamente a origem dos dados apresentados.

Também deverá informar a data da última atualização dos dados utilizados pelo sistema, distinguindo-a, quando necessário, da data de publicação dos arquivos pela fonte oficial.

As informações deverão ser facilmente localizadas pelo usuário.

## Critérios de aceitação

- [ ] O dashboard identifica a fonte dos dados apresentados.
- [ ] O sistema informa a data da última atualização dos dados utilizados.
- [ ] A data apresentada corresponde a uma informação verificável no processo de atualização dos dados.
- [ ] O usuário consegue localizar facilmente essas informações na interface.
- [ ] O sistema evita apresentar datas de atualização não confirmadas.
- [ ] Quando a data não estiver disponível, o dashboard informa essa limitação.
- [ ] As informações são revisadas quando os dados utilizados forem substituídos ou atualizados.

## Tarefas técnicas propostas

- [ ] Identificar a origem dos arquivos utilizados pelo MAPPA.
- [ ] Verificar quais informações de atualização estão disponíveis.
- [ ] Definir como registrar a data de atualização dos dados.
- [ ] Implementar a exibição da fonte e da data na interface Streamlit.
- [ ] Tratar situações em que a data de atualização não esteja disponível.
- [ ] Verificar a consistência das informações apresentadas.
- [ ] Registrar evidências dos testes realizados.

## Dependências

- US03 — Tratamento dos dados da PRF.
- Disponibilidade de informações confiáveis sobre a origem e a atualização dos arquivos utilizados.

## Evidências de conclusão

A conclusão deverá ser comprovada pela conferência da origem dos dados, da data informada e de sua apresentação na interface.

**Estado atual:** Issue #13 cadastrada no GitHub. Implementação não verificada.
