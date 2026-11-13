# Ponto Solidário

Solução digital da CitizenTech para apoiar cidadãos em situação de vulnerabilidade.

## Problema e proposta
[2 ou 3 frases: muitas pessoas não sabem onde encontrar abrigos, bancos de alimentos e pontos de doação. O Ponto Solidário reúne esses locais numa página simples, acessível pelo celular.]

## Integrantes
| Nome | RM | Turma |
|------|----|-------|
| Isabella Francisco Heder | RM561300 | 2TSC |
| João Victor D'Alessio Miranda | RM561050 | 2TSC |

## Origem do projeto
Criado do zero pela equipe para a Global Solution 02/2026.

## Tecnologias
HTML, CSS, Node.js (htmlhint, para validação), GitHub, GitHub Actions e GitHub Pages.

### Como executar localmente
Abra o `index.html` no navegador. Para validar o HTML: `npm install` e `npm test`.

## Como usamos o GitHub
- **Project:** [(https://github.com/Dalessio71/ponto-solidario/pulls?q=is%3Aclosed)]. 1 história (#1) e 2 tarefas (#2, #3), com responsável e status Todo → In Progress → Done.
- **Issues:** #1 (história), #2 (personalizar página), #3 (workflow de build e publicação).
- **Branches:** `main`, `feature/personalizar-pagina`, `feature/workflow-ci`, `fix/corrige-html`, `feature/deploy-pages`, `feature/novo-ponto-apoio`.
- **Pull Requests:** #4, #5, #6, #7 e [https://github.com/Dalessio71/ponto-solidario/pulls?q=is%3Aclosed], todos com merge.

## Workflows (GitHub Actions)
- **CI (`.github/workflows/ci.yml`):** roda em push e pull request para a `main`. Baixa o código, instala o Node.js 20, instala as dependências e valida o HTML com o htmlhint.
- **Deploy (`.github/workflows/deploy.yml`):** roda em push na `main`. Copia `index.html` e `style.css`, envia o artefato e publica no GitHub Pages.

## Nuvem
- **Provedor:** GitHub Pages.
- **Aplicação publicada:** https://dalessio71.github.io/ponto-solidario/
- **Observação:** tentamos primeiro o Azure Static Web Apps, mas a assinatura Azure for Students bloqueou a criação (erro `RequestDisallowedByAzure`). Por isso migramos para o GitHub Pages.

## Evidências
Os prints estão na documentação enviada
- Project e status: `01`, `02`, `03`
- CI com erro e correção: `04`, `05`
- Site antes e depois: `06`, `09`
- Pull Request e deploy final: `07`, `08`
- Histórico, branches e estrutura: `10`, `11`, `12`

Links: [Issues](https://github.com/Dalessio71/ponto-solidario/issues?q=is%3Aissue) · [Pull requests](https://github.com/Dalessio71/ponto-solidario/pulls?q=is%3Aclosed) · [Actions](https://github.com/Dalessio71/ponto-solidario/actions)
