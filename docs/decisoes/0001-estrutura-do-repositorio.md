# 0001 — Estrutura do repositório (docs/, entregas/, sprints/ + fluxo Issue→Branch→PR)

**Status:** Registrada no repositório; validação coletiva a confirmar
**Data:** 2026-09-17
**Equipe indicada no projeto:** João Vitor Velozo, Danilo Lisboa, Igor Cavalcante. A autoria e a aprovação coletiva desta decisão devem ser confirmadas.

## Contexto
O grupo precisava organizar, em um único repositório, as entregas de múltiplas disciplinas do Projeto Integrador II (Artefatos 1, 2, 3 e 5), seguindo o padrão institucional do template `CAMPUSCEUB/MAPPA` — que já define as pastas `docs/` (com `decisoes/` e `reunioes/`), `entregas/` e `sprints/`, além de templates de issue por categoria (`bug`, `documentacao`, `pesquisa`, `requisito`) e um `PULL_REQUEST_TEMPLATE.md`.

## Decisão
Adotar a estrutura do template institucional sem subdivisão por unidade/disciplina:
- `docs/` — arquivos de documentação viva direto na raiz da pasta (`requisitos.md`, `backlog.md`, `cronograma-sprints.md`, `eap.md`, `analise-usuario.md`, `arquitetura.md`), com referências aos artefatos formais (.docx) armazenados em `entregas/`.
- `docs/decisoes/` — registros de decisão (este arquivo é o primeiro).
- `docs/reunioes/` — pautas, registros retrospectivos e atas, quando houver reunião formal comprovada.
- `sprints/` — um arquivo por sprint (`sprint-01.md`, `sprint-02.md`, ...), seguindo `template-sprint.md`, linkado a milestone, issues e PRs.
- `entregas/` — registros de entrega seguindo `template-entrega.md`.
- Issues do backlog categorizadas conforme `.github/MODELO_DE_PROBLEMA/` (majoritariamente como `requisito`), vinculadas a Milestones por sprint; merge somente via Pull Request revisado.

## Alternativas consideradas
- Estrutura própria `docs/Un1...Un5/` dividida por disciplina: descartada após comparação direta com o template institucional (`CAMPUSCEUB/MAPPA`), que usa pasta plana `docs/` sem divisão por unidade.
- Manter os `.docx` dentro de `docs/`: alternativa não adotada na organização atual; os arquivos formais estão em `entregas/`, com links a partir de `docs/`.

## Consequências
- A documentação de trabalho fica em `docs/` e os artefatos formais em `entregas/`; links entre eles facilitam a navegação.
- A equipe precisa manter os arquivos de `sprints/` e `entregas/` atualizados seguindo exatamente os templates institucionais, para preservar a rastreabilidade exigida pelo Guia dos Estudantes.
