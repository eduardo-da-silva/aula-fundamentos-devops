---
title: 'Estratégias de Branching'
description: 'Branches, merges e resolução de conflitos no Git.'
permalink: /collaboration/estrategias-branching
---

# Estratégias de Branching

O uso de branches (ramificações) é uma prática comum no versionamento de código que permite que os desenvolvedores trabalhem em funcionalidades ou correções de bugs isoladamente, sem interferir no código principal. Cada branch representa uma linha de desenvolvimento separada, que pode ser integrada ao branch principal (geralmente `main` ou `master`) por meio de merges.

Os branches são úteis para organizar o trabalho em equipe, facilitar a revisão de código e manter um histórico claro das alterações realizadas. Por exemplo, uma equipe de desenvolvimento pode criar branches específicos para cada funcionalidade ou tarefa, como `feature/nova-funcionalidade` ou `bugfix/correcao-bug`.

Após concluir o desenvolvimento em um branch, é comum realizar um merge para integrar as mudanças no branch principal. O merge é o processo de combinar as alterações de um branch em outro, garantindo que o código seja atualizado e os conflitos sejam resolvidos corretamente.

## Resolução de Conflitos

Durante o merge, podem ocorrer conflitos quando duas ou mais alterações entram em conflito, ou seja, modificam a mesma parte do código. Nesses casos, é necessário resolver os conflitos manualmente, escolhendo qual versão do código deve ser mantida.

As ferramentas de versionamento, como Git, oferecem suporte para resolver conflitos de forma eficiente, permitindo que os desenvolvedores comparem as versões do código, escolham as alterações desejadas e finalizem o merge com sucesso.

A resolução de conflitos é uma etapa importante no processo de desenvolvimento colaborativo, pois garante que as mudanças sejam integradas corretamente e que o código seja mantido consistente ao longo do tempo.

## GitFlow

O GitFlow é um modelo de branching amplamente utilizado que define um fluxo de trabalho com branches específicos para features, releases, hotfixes e versões. Ele propõe a utilização de branches como `feature/`, `release/`, `hotfix/` e `develop` para organizar o desenvolvimento de forma estruturada e facilitar a colaboração em equipe.

O GitFlow é baseado em algumas premissas fundamentais:

- `master`: Branch principal que contém o código em produção.
- `develop`: Branch de desenvolvimento contínuo, onde as features são integradas.
- `feature/`: Branches para o desenvolvimento de novas funcionalidades.
- `release/`: Branches para preparar novas versões para produção.
- `hotfix/`: Branches para corrigir bugs críticos em produção.

O GitFlow é uma estratégia eficaz para organizar o desenvolvimento de software, facilitar a colaboração em equipe e manter um histórico claro das alterações realizadas.

Para implementar o GitFlow existe um aplicativo, chamado git-flow, que facilita a utilização dessa estratégia.

Por exemplo, usando o git-flow, você pode criar um novo branch de feature com o comando:

```bash
git flow feature start nova-funcionalidade
```

E finalizar a feature com o comando:

```bash
git flow feature finish nova-funcionalidade
```

O git-flow automatiza o processo de criação e finalização de branches, facilitando o uso do GitFlow em projetos de desenvolvimento de software.

Contudo, nem sempre é necessário usar essa ferramenta, pois o GitFlow pode ser implementado manualmente, sem a necessidade de uma ferramenta específica. O que importa é seguir o fluxo de trabalho proposto pelo GitFlow para organizar o desenvolvimento de forma eficiente.

Existem outras estratégias de branching, como o trunk-based development, que propõem abordagens diferentes para organizar o desenvolvimento de software. Cada equipe pode escolher a estratégia que melhor se adapta às suas necessidades e ao seu fluxo de trabalho.

<span style="display: flex; justify-content: space-between;"><span>[&lt; Plataformas de Hospedagem Git](plataformas-git.html 'Anterior')</span> <span>[Pull Requests e Code Review &gt;](pull-requests.html 'Próximo')</span></span>
