# Requisitos — MAPPA

> Extraído do Artefato 2 (Documento de Software V2). Cada requisito é referenciado no [Backlog](./backlog.md) e no [Cronograma em Sprints](./cronograma-sprints.md).

## Requisitos Funcionais (RF)

| Código | Descrição | Prioridade | História relacionada |
|---|---|---|---|
| RF01 | Permitir consulta dos dados de acidentes por ano, rodovia, município, causa e severidade. | Alta | [US01](./backlog.md#us01) |
| RF02 | Exibir indicadores consolidados de acidentes, feridos e mortos. | Alta | [US02](./backlog.md#us02) |
| RF03 | Gerar gráficos de distribuição por rodovia, período, causa e faixa horária. | Alta | [US06](./backlog.md#us06) |
| RF04 | Exibir ranking de rodovias/trechos com maior número de ocorrências. | Média | [US04](./backlog.md#us04) |
| RF05 | Exibir mapa geográfico das ocorrências no recorte DF e Entorno. | Média | [US05](./backlog.md#us05) |
| RF06 | Executar o pipeline de ETL (extração, limpeza, padronização e transformação) sobre os arquivos CSV da PRF. | Alta | [US03](./backlog.md#us03) |
| RF07 | Permitir a aplicação de filtros combinados (ex.: rodovia + período + causa). | Alta | [US07](./backlog.md#us07) |
| RF08 | Criar variáveis derivadas, como faixa horária e nível de severidade, durante o ETL. | Média | [US03](./backlog.md#us03) |
| RF09 | Aplicar o recorte geográfico definido para o projeto (BR-020, 040, 060, 070, 080). | Alta | [US03](./backlog.md#us03) |
| RF10 | Permitir a exportação dos dados resultantes dos filtros aplicados para arquivo CSV. | Alta | [US10](./backlog.md#us10) |
| RF11 | Permitir a comparação de indicadores de acidentes entre dois períodos selecionados pelo usuário. | Alta | [US11](./backlog.md#us11) |
| RF12 | Identificar e destacar trechos rodoviários com maior concentração de acidentes, conforme critérios definidos. | Média | [US12](./backlog.md#us12) |
| RF13 | Exibir a origem dos dados e a data de atualização da base utilizada pelo dashboard. | Alta | [US13](./backlog.md#us13) |
| RF14 | Permitir a exportação dos gráficos apresentados no dashboard como arquivos de imagem. | Média | [US14](./backlog.md#us14) |

## Requisitos Não Funcionais (RNF)

| Código | Descrição | Prioridade | História relacionada |
|---|---|---|---|
| RNF01 | Usabilidade: interface simples e intuitiva, utilizável por perfis não técnicos (gestores, supervisores). | Alta | — |
| RNF02 | Desempenho: tempo de resposta aceitável do dashboard mesmo com grande volume de dados. | Alta | [US08](./backlog.md#us08) |
| RNF03 | Portabilidade: aplicação acessível via navegador, executada em Streamlit. | Média | — |
| RNF04 | Manutenibilidade: código em Python/Pandas modularizado, favorecendo evolução incremental. | Alta | [US09](./backlog.md#us09) |
| RNF05 | Confiabilidade dos dados: tratamento consistente e rastreável das bases públicas da PRF. | Alta | [US03](./backlog.md#us03) |
| RNF06 | Escalabilidade: capacidade de incorporar novas rodovias ou regiões ao recorte geográfico. | Média | — |
| RNF07 | Disponibilidade: aplicação estável durante demonstrações e uso acadêmico contínuo. | Média | — |

---
📄 Documentos completos: [Artefato 1](../entregas/Artefato_1_MAPPA_PI_II.docx) · [Artefato 2](../entregas/Artefato_2_MAPPA_PI_II.docx)
