# US14 — Exportação de gráficos como imagem

## História de usuário

Como pesquisador ou gestor, quero exportar os gráficos do dashboard como imagens, para utilizá-los em relatórios, apresentações e estudos sobre acidentes rodoviários.

## Requisito relacionado

**RF14:** Permitir a exportação dos gráficos do dashboard como arquivos de imagem.

## Prioridade

**Could** — funcionalidade desejável para evolução do produto, não obrigatória para o MVP.

## Planejamento

Evolução futura do MAPPA, sem Sprint de implementação definida.

**Situação:** proposta de funcionalidade, sujeita à avaliação técnica e à disponibilidade da equipe.

## Descrição

Disponibilizar uma opção para exportar os gráficos apresentados no dashboard MAPPA como arquivos de imagem, preferencialmente no formato PNG.

A exportação deverá preservar as informações exibidas no gráfico, incluindo títulos, legendas e dados correspondentes aos filtros selecionados.

O recurso deverá facilitar a utilização das visualizações em documentos acadêmicos, relatórios técnicos e apresentações.

## Critérios de aceitação

- [ ] O usuário consegue exportar os gráficos contemplados pela funcionalidade como imagens.
- [ ] O arquivo exportado apresenta o gráfico correspondente aos filtros aplicados.
- [ ] Títulos, legendas e informações relevantes permanecem legíveis.
- [ ] A imagem possui resolução adequada para inclusão em relatórios.
- [ ] O arquivo exportado pode ser aberto em visualizadores de imagem.
- [ ] O sistema apresenta uma mensagem apropriada quando não existem dados para gerar o gráfico.
- [ ] Os gráficos compatíveis com a exportação estão identificados.

## Tarefas técnicas propostas

- [ ] Identificar as bibliotecas utilizadas para gerar os gráficos do MAPPA.
- [ ] Verificar as possibilidades de exportação de imagens.
- [ ] Definir os gráficos que terão suporte à exportação.
- [ ] Implementar a geração dos arquivos de imagem.
- [ ] Adicionar a opção de download à interface Streamlit.
- [ ] Testar a exportação com diferentes filtros.
- [ ] Verificar a legibilidade das imagens geradas.
- [ ] Registrar evidências dos testes.

## Dependências

- US02 — Indicadores consolidados.
- US06 — Gráficos de acidentes.
- Disponibilidade de recursos de exportação nas bibliotecas gráficas utilizadas.

## Evidências de conclusão

A conclusão deverá ser comprovada pela geração e conferência de arquivos de imagem dos gráficos, acompanhadas de registros dos testes realizados.

**Estado atual:** Issue #14 cadastrada no GitHub. Implementação não verificada.
