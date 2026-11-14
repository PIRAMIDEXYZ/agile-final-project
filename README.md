# agile-final-project

## Finalidade

Este repositório é uma **simulação acadêmica** para a atividade final de IBM Agile. O
objetivo é praticar a decomposição de um produto em histórias de usuário, a escrita
de critérios de aceitação em Gherkin, a organização de um backlog e o planejamento
de uma Sprint.

> **Aviso:** este projeto não contém software funcional. Os itens abaixo representam
> requisitos e atividades de planejamento; não há API, banco de dados, interface,
hospedagem ou pipeline de implantação implementados neste repositório.

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

## Sprint simulada

A milestone **Sprint duas semanas** representa o período de **14/11/2026 a
28/11/2026**. Somente as histórias 1 a 4 foram associadas a essa milestone; as
histórias 5 a 10 permanecem no backlog sem Sprint atribuída.

## Critérios de aceitação

Cada issue segue o formato de história com as seções `As a`, `I need` e `So that`,
detalhes e premissas, além de cenários Gherkin com `Given`, `When` e `Then`. Os
cenários descrevem o comportamento esperado em uma futura implementação, mas não
constituem evidência de que o comportamento já exista.

## Artefatos de controle

O arquivo [`github_state.json`](github_state.json) registra o mapa dos números e URLs
das issues, a milestone, as etiquetas e os vínculos planejados no momento da
configuração. O template em
[`.github/ISSUE_TEMPLATE/user-story.md`](.github/ISSUE_TEMPLATE/user-story.md)
mantém o padrão para novas histórias.
