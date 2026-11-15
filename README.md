# agile-final-project

## Finalidade

Este repositório é uma **simulação acadêmica** para a atividade final de IBM Agile. O
objetivo é praticar a decomposição de um produto em histórias de usuário, a escrita
de critérios de aceitação em Gherkin, a organização de um backlog e o planejamento
de uma Sprint.

> **Aviso:** este projeto não contém software funcional. Os itens abaixo representam
> requisitos e atividades de planejamento; não há API, banco de dados, interface,
> hospedagem ou pipeline de implantação implementados neste repositório.

## Backlog simulado

O backlog contém dez issues abertas, em português e na ordem dos requisitos:

1. Criar produto
2. Recuperar produto
3. Atualizar produto
4. Excluir produto
5. Curtir produto
6. Descurtir produto
7. Listar todos os produtos
8. Consultar subconjunto de produtos
9. Hospedar a aplicação na nuvem
10. Automatizar a implantação

As histórias 1 a 8 usam a etiqueta `enhancement`. As histórias 9 e 10 usam a
etiqueta `technical debt`, por representarem preocupações técnicas de infraestrutura
e entrega. Todas estão atribuídas a `PIRAMIDEXYZ` para fins de avaliação da rubrica.

### Tradução das etiquetas

| Etiqueta no GitHub | Tradução/uso em português | Histórias |
| --- | --- | --- |
| `enhancement` | Melhoria ou funcionalidade | 1 a 8 |
| `technical debt` | Dívida técnica | 9 e 10 |

## Sprint simulada

A milestone **GitHub #1 — Sprint** representa o ciclo de **09/11/2026 a
22/11/2026**, que é o ciclo nativo do ZenHub. Seu vencimento no GitHub é
**22/11/2026**. A descrição da milestone registra que o planejamento e a execução
foram simulados em **14/11/2026**. A milestone associa as histórias 1 a 4; as
histórias 5 a 10 permanecem sem milestone no GitHub.

O nome exibido pelo Sprint nativo do ZenHub é **Sprint: Nov 9 - Nov 22, 2026**.
O quadro abaixo é uma fotografia documental da simulação realizada nessa data: as
colunas do ZenHub não alteram o estado das issues no GitHub.

### Tradução das colunas e estado final simulado

| Coluna ZenHub | Tradução/uso em português | Issues no quadro | Observação |
| --- | --- | --- | --- |
| **Icebox** | Itens em espera / não priorizados | #7, #8 | Ainda fora da priorização da Sprint |
| **Product Backlog** | Backlog do produto | #5, #6, #9, #10 | Priorizadas para trabalho futuro |
| **Sprint Backlog** | Backlog da Sprint | #4 | Selecionada para a Sprint |
| **In Progress** | Em andamento | #3 | Trabalho simulado em andamento |
| **Review/QA** | Revisão / garantia de qualidade | Nenhuma | Coluna vazia na simulação |
| **Done** | Concluído | #1, #2 | Concluído **somente no quadro simulado** |

Todas as dez issues continuam **abertas no GitHub** e atribuídas a `PIRAMIDEXYZ`,
inclusive #1 e #2 que aparecem em **Done**. Essa posição é uma simulação de quadro
e não significa que as issues foram fechadas ou que o software tenha sido
implementado.

### Pontos planejados e burndown

A estimativa planejada para a Sprint é de **10 pontos**:

| Issue | História | Pontos planejados |
| --- | --- | ---: |
| #1 | Criar produto | 3 |
| #2 | Recuperar produto | 2 |
| #3 | Atualizar produto | 3 |
| #4 | Excluir produto | 2 |
| **Total** |  | **10** |

O burndown nativo usa **Done** como *burn pipeline*: **5 pontos completos**, **5
pontos restantes** e **10 pontos no total**. Em quantidade de issues, **2 de 4**
foram concluídas apenas na simulação do quadro; as quatro issues da Sprint (#1 a
#4) continuam abertas no GitHub.

### Links do workspace ZenHub

- Workspace/quadro: <https://app.zenhub.com/workspaces/projeto-final-6af881d4f5439b0016cfa1a3/board>
- Burndown: <https://app.zenhub.com/workspaces/projeto-final-6af881d4f5439b0016cfa1a3/reports/burndown?milestoneId=Z2lkOi8vcmFwdG9yL1NwcmludC81Mzk4MTE3&selectedPipelines=Z2lkOi8vcmFwdG9yL1BpcGVsaW5lLzM2MDU1MDA>

## Critérios de aceitação

Cada issue segue o formato de história com as seções `As a`, `I need` e `So that`,
detalhes e premissas, além de cenários Gherkin com `Given`, `When` e `Then`. Os
cenários descrevem o comportamento esperado em uma futura implementação, mas não
constituem evidência de que o comportamento já exista.

## Artefatos de controle

O arquivo [`github_state.json`](github_state.json) registra o mapa dos números e URLs
das issues, a milestone, as etiquetas, o estado simulado do quadro ZenHub, as
estimativas e os vínculos planejados no momento da configuração. O template em
[`.github/ISSUE_TEMPLATE/user-story.md`](.github/ISSUE_TEMPLATE/user-story.md)
mantém o padrão para novas histórias.

### Sobre o material e autoria
Este repositório registra uma simulação acadêmica concluída como atividade final de um curso da IBM sobre Agile e Scrum. O exercício praticou histórias de usuário, critérios de aceitação em Gherkin, organização de backlog, estimativas e planejamento simulado de Sprint com GitHub e ZenHub. É um registro de estudo: não contém software funcional, não é material oficial nem endossado pela IBM e não comprova experiência profissional em produção.

Autor do exercício: Caio Viana (@PIRAMIDEXYZ).

O repositório está público para consulta como registro do exercício. Não é oferecido sob uma licença aberta de reutilização. A visualização e os forks no GitHub continuam sujeitos aos termos da plataforma; outros usos devem ser autorizados pelo titular.

### Nota sobre o quadro ZenHub
A distribuição de issues descrita neste README é uma fotografia da simulação registrada em 14/11/2026. Na consulta de 15/11/2026, o Work Tracker mostrou 0 issues em todas as colunas; portanto, a tabela histórica não representa o estado atual confirmado do quadro.
