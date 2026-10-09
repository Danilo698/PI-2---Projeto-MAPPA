# ETL do MAPPA — Processamento dos dados da PRF

## Origem

O arquivo `etl_mappa_v3.py` foi desenvolvido no MAPPA PI I e incorporado ao repositório do MAPPA PI II para preservar a continuidade técnica do projeto.

O código foi copiado sem alterações em relação à versão original.

## Finalidade

O ETL prepara os dados públicos de acidentes da Polícia Rodoviária Federal (PRF) para utilização no dashboard MAPPA.

Suas principais atividades são:

1. Ler e reunir arquivos CSV da PRF.
2. Padronizar nomes de colunas e valores.
3. Tratar datas, horários e campos numéricos.
4. Calcular indicadores de feridos e classificar a severidade.
5. Aplicar o recorte geográfico definido pelo projeto.
6. Remover ocorrências duplicadas.
7. Gerar arquivos CSV tratados para gráficos, indicadores e mapas.

## Recorte geográfico

O processamento considera, por padrão:

- Rodovias: BR-020, BR-040, BR-060, BR-070 e BR-080.
- Unidades federativas: DF, GO e MG.

Os registros devem atender aos filtros de rodovia e unidade federativa.

## Execução

O script utiliza Python e a biblioteca Pandas.

A partir da pasta principal do projeto, com as dependências instaladas:

```powershell
python etl/etl_mappa_v3.py --input dados_prf --output saida_dashboard
```

A pasta `dados_prf` deve conter os arquivos CSV originais da PRF.

**Atenção:** executar esse comando pode substituir arquivos já existentes em `saida_dashboard`. Antes de reprocessar os dados, preserve uma cópia dos resultados atuais.

## Relação com o PI II

O dashboard do PI II utiliza os arquivos tratados pelo ETL original e incorpora análises adicionais, incluindo comparação entre períodos e identificação de trechos críticos.

A inclusão deste script permite documentar e preservar o processamento herdado do PI I.

## Limitações

- Os arquivos CSV brutos da PRF não estão incluídos nesta pasta.
- A reprodução dos resultados depende da utilização dos arquivos de entrada correspondentes.
- A presença do script não significa que um novo processamento tenha sido executado no PI II.
