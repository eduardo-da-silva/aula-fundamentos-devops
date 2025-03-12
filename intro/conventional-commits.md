---
title: 'Convencional Commits'
description: 'Entenda a convenção de mensagens de commit padronizada.'
permalink: /intro/conventional-commits
---

# Conventional Commits

O Conventional Commits é uma convenção de mensagens de commit padronizada que facilita a compreensão do histórico de mudanças em um repositório de código. Essa convenção define um formato consistente para as mensagens de commit, permitindo que desenvolvedores e ferramentas identifiquem rapidamente o tipo de alteração realizada.

Um bom local de consulta é o [site oficial do Conventional Commits](https://www.conventionalcommits.org/), que fornece informações detalhadas sobre a convenção, exemplos de mensagens de commit e recomendações de uso. Ele é mantido pela comunidade e é uma referência útil para quem deseja adotar a convenção em seus projetos. O projeto foi inspirado em outras convenções de mensagens de commit, em especial o Angular Commit Message Guidelines.

Em linhas gerais, as mensagens de commit seguem um padrão predefinido, que inclui um prefixo indicando o tipo de alteração realizada, seguido de um título descritivo. Alguns dos prefixos mais comuns incluem:

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
feat: adiciona funcionalidade de login
```

Essa mensagem indica que o commit adiciona uma nova funcionalidade de login ao projeto. Ao seguir essa convenção, os desenvolvedores podem facilmente identificar o propósito de cada commit e entender as mudanças realizadas ao longo do tempo.

Além disso, ferramentas de automação, como linters e geradores de changelog, podem ser configuradas para analisar as mensagens de commit e gerar informações úteis, como logs de alterações e notas de versão automaticamente.

A adoção do Conventional Commits é uma prática recomendada para equipes que buscam manter um histórico de mudanças claro e organizado, facilitando a colaboração e a revisão de código.

## Ferramentas para auxiliar no cumprimento da convenção

Para facilitar o uso do Conventional Commits, você pode instalar extensões no Visual Studio Code que fornecem suporte para a convenção. Essas extensões ajudam a formatar as mensagens de commit de acordo com a convenção, garantindo consistência e facilitando a leitura do histórico de mudanças.

Uma extensão popular para o Visual Studio Code é o [Conventional Commits](https://marketplace.visualstudio.com/items?itemName=vivaxy.vscode-conventional-commits), que fornece recursos como autocompletar, validação e formatação das mensagens de commit de acordo com a convenção.

Caso você não tenha interesse em fazer os commits dentro do VS Code, você pode utilizar ferramentas como o [Commitizen](https://commitizen.github.io/cz-cli/) para auxiliar na criação de mensagens de commit seguindo a convenção. O Commitizen é uma ferramenta de linha de comando que fornece um assistente interativo para criar mensagens de commit padronizadas.

Ainda, é possível utilizar ferramentas como o Commitlint e o Husky para validar as mensagens de commit automaticamente durante o processo de commit, garantindo que todas as mensagens sigam a convenção corretamente.

<span style="display: flex; justify-content: space-between;"><span>[&lt; Git Básico](git-basico.html 'Anterior')</span> <span>[Sumário &gt;](../ 'Sumário')</span></span>
