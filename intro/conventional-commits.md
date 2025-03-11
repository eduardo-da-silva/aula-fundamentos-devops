---
title: 'Convencional Commits'
description: 'Entenda a convenção de mensagens de commit padronizada.'
permalink: /intro/conventional-commits
---

# Conventional Commits

O Conventional Commits é uma convenção de mensagens de commit padronizada que facilita a compreensão do histórico de mudanças em um repositório de código. Essa convenção define um formato consistente para as mensagens de commit, permitindo que desenvolvedores e ferramentas identifiquem rapidamente o tipo de alteração realizada.

As mensagens de commit seguem um padrão predefinido, que inclui um prefixo indicando o tipo de alteração realizada, seguido de um título descritivo. Alguns dos prefixos mais comuns incluem:

- `feat`: Para novas funcionalidades ou melhorias
- `fix`: Para correções de bugs
- `chore`: Para tarefas de manutenção ou refatoração
- `docs`: Para alterações na documentação
- `style`: Para alterações de estilo ou formatação
- `refactor`: Para refatorações de código
- `test`: Para adições ou alterações em testes
- `ci`: Para alterações em configurações de CI/CD

Por exemplo, uma mensagem de commit seguindo a convenção Conventional Commits pode ser:

```
feat: Adicionar funcionalidade de login
```

Essa mensagem indica que o commit adiciona uma nova funcionalidade de login ao projeto. Ao seguir essa convenção, os desenvolvedores podem facilmente identificar o propósito de cada commit e entender as mudanças realizadas ao longo do tempo.

Além disso, ferramentas de automação, como linters e geradores de changelog, podem ser configuradas para analisar as mensagens de commit e gerar informações úteis, como logs de alterações e notas de versão automaticamente.

A adoção do Conventional Commits é uma prática recomendada para equipes que buscam manter um histórico de mudanças claro e organizado, facilitando a colaboração e a revisão de código.

## Branches, merges e resolução de conflitos

O uso de branches (ramificações) é uma prática comum no versionamento de código que permite que os desenvolvedores trabalhem em funcionalidades ou correções de bugs isoladamente, sem interferir no código principal. Cada branch representa uma linha de desenvolvimento separada, que pode ser integrada ao branch principal (geralmente `main` ou `master`) por meio de merges.

Os branches são úteis para organizar o trabalho em equipe, facilitar a revisão de código e manter um histórico claro das alterações realizadas. Por exemplo, uma equipe de desenvolvimento pode criar branches específicos para cada funcionalidade ou tarefa, como `feature/nova-funcionalidade` ou `bugfix/correcao-bug`.

Após concluir o desenvolvimento em um branch, é comum realizar um merge para integrar as mudanças no branch principal. O merge é o processo de combinar as alterações de um branch em outro, garantindo que o código seja atualizado e os conflitos sejam resolvidos corretamente.

Durante o merge, podem ocorrer conflitos quando duas ou mais alterações entram em conflito, ou seja, modificam a mesma parte do código. Nesses casos, é necessário resolver os conflitos manualmente, escolhendo qual versão do código deve ser mantida.

As ferramentas de versionamento, como Git, oferecem suporte para resolver conflitos de forma eficiente, permitindo que os desenvolvedores comparem as versões do código, escolham as alterações desejadas e finalizem o merge com sucesso.

A resolução de conflitos é uma etapa importante no processo de desenvolvimento colaborativo, pois garante que as mudanças sejam integradas corretamente e que o código seja mantido consistente ao longo do tempo.

<span style="display: flex; justify-content: space-between;"><span>[&lt; Git Básico](git-basico.html 'Anterior')</span> <span>[Sumário &gt;](../ 'Sumário')</span></span>
