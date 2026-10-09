# Modelador Analítico Para Prevenção de Acidentes (MAPPA)

## Identificação do repositório

| Campo | Informação |
| --- | --- |
| Instituição | CEUB |
| Organização no GitHub | CampusCEUB |
| Professor(a) responsável pela criação: | Adriana Falcomer Pontes |
| Equipe | [João Vitor](https://github.com/Jvvelozo), [Danilo Lisboa](https://github.com/Danilo698), [Igor Cavalcante](https://github.com/igorcavalcanteee) |
| IDProjeto | Informar o ID do Projeto conforme consta no Portfólio de Projetos de TI do CEUB|

## Problema

Acidentes em rodovias federais são um problema público recorrente, com destaque para os corredores que ligam o Distrito Federal ao seu Entorno e a outros estados. Os dados oficiais sobre essas ocorrências existem, mas estão dispersos, em formato bruto e técnico, o que dificulta identificar rapidamente quais rodovias e trechos concentram maior criticidade, em quais horários e causas predominam, e como priorizar ações de fiscalização, sinalização ou estudo acadêmico. Essa lacuna limita o uso analítico, educacional e preventivo dessas informações.
## Solução proposta

O MAPPA é um sistema analítico que consolida bases públicas de acidentes em uma leitura organizada e filtrável por rodovia, período, causa, horário e gravidade, com foco nas rodovias federais ligadas ao DF e Entorno. O público atendido inclui gestores técnicos de mobilidade, supervisores de fiscalização, segurança viária, pesquisadores, estudantes e, indiretamente, os condutores que utilizam essas rodovias diariamente. O valor esperado é reduzir o tempo de tratamento manual dos dados e apoiar decisões preventivas baseadas em evidências, por meio de um dashboard interativo com ranking de trechos críticos, indicadores de severidade e visualizações por causa e faixa horária.

## Estrutura deste repositório

| Item | Link |
| --- | --- |
| Backlog | [docs/backlog.md](docs/backlog.md) |
| Sprints | [sprints/README.md](sprints/README.md) |
| Entregas | [entregas/README.md](entregas/README.md) |
| Requisitos | [docs/requisitos.md](docs/requisitos.md) |
| Arquitetura | [docs/arquitetura.md](docs/arquitetura.md) |


---

## Executando o aplicativo MAPPA

O MAPPA PI II possui um painel interativo desenvolvido em Python,
utilizando Streamlit, Pandas e Plotly.

### Requisitos

- Python 3.11 ou superior
- Bibliotecas listadas em `requirements.txt`

### Instalação

No terminal, dentro da pasta do projeto, execute:

```bash
python -m pip install -r requirements.txt
```

### Iniciar o aplicativo

```bash
python -m streamlit run app.py
```

Abra no navegador o endereço informado pelo Streamlit,
normalmente `http://localhost:8501`.

### Dados utilizados

Os 11 arquivos CSV necessários estão na pasta `saida_dashboard/`.

O aplicativo carrega essa pasta automaticamente. Também é possível
selecionar outra pasta de dados no menu lateral.

### Fonte dos dados

Polícia Rodoviária Federal (PRF).

Os arquivos CSV utilizados no painel foram previamente processados
para fins acadêmicos. Os resultados devem ser interpretados
considerando as limitações dos dados disponíveis.

## Continuidade técnica do MAPPA

O MAPPA PI II dá continuidade ao Projeto Integrador I (PI I), aproveitando o processo de tratamento dos dados da PRF e a estrutura do dashboard desenvolvidos anteriormente.

No PI I, a equipe era composta por cinco integrantes. No PI II, passou a contar com três participantes: João Vitor, Danilo Lisboa e Igor Cavalcante.

O código original do ETL foi preservado na pasta `etl/`, permitindo consultar o processamento utilizado para preparar os dados do painel.

- [Documentação do ETL](etl/README.md)
- [Código ETL original](etl/etl_mappa_v3.py)

Entre as evoluções analíticas trabalhadas no PI II estão a comparação entre períodos e a identificação de trechos rodoviários com maior concentração de acidentes.
