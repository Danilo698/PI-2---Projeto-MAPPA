# 0001 — Estrutura do repositório (docs/, entregas/, sprints/ + fluxo Issue→Branch→PR)

**Status:** Aceita
**Data:** 2026-09-17
**Responsáveis:** João Vitor Velozo, Danilo Lisboa, Igor Cavalcante

## Contexto
O grupo precisava organizar, em um único repositório, as entregas de múltiplas disciplinas do Projeto Integrador II (Artefatos 1, 2, 3 e 5), seguindo o padrão institucional do template `CAMPUSCEUB/MAPPA` — que já define as pastas `docs/` (com `decisoes/` e `reunioes/`), `entregas/` e `sprints/`, além de templates de issue por categoria (`bug`, `documentacao`, `pesquisa`, `requisito`) e um `PULL_REQUEST_TEMPLATE.md`.

## Decisão
Adotar a estrutura do template institucional sem subdivisão por unidade/disciplina:
- `docs/` — arquivos de documentação viva direto na raiz da pasta (`requisitos.md`, `backlog.md`, `cronograma-sprints.md`, `eap.md`, `analise-usuario.md`, `arquitetura.md`), acompanhados dos artefatos formais (.docx) correspondentes.
- `docs/decisoes/` — registros de decisão (este arquivo é o primeiro).
- `docs/reunioes/` — atas de reunião.
- `sprints/` — um arquivo por sprint (`sprint-01.md`, `sprint-02.md`, ...), seguindo `template-sprint.md`, linkado a milestone, issues e PRs.
- `entregas/` — registros de entrega seguindo `template-entrega.md`.
- Issues do backlog categorizadas conforme `.github/MODELO_DE_PROBLEMA/` (majoritariamente como `requisito`), vinculadas a Milestones por sprint; merge somente via Pull Request revisado.

## Alternativas consideradas
- Estrutura própria `docs/Un1...Un5/` dividida por disciplina: descartada após comparação direta com o template institucional (`CAMPUSCEUB/MAPPA`), que usa pasta plana `docs/` sem divisão por unidade.
- Guardar os `.docx` de cada artefato em uma pasta separada por entrega: descartada em favor de mantê-los junto ao `.md` correspondente dentro de `docs/`, reduzindo saltos entre pastas.

## Consequências
- A documentação fica mais enxuta de navegar (tudo em `docs/`), ao custo de depender só do nome do arquivo para saber a que artefato/disciplina ele pertence.
- A equipe precisa manter os arquivos de `sprints/` e `entregas/` atualizados seguindo exatamente os templates institucionais, para preservar a rastreabilidade exigida pelo Guia dos Estudantes.
