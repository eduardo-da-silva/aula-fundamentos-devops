---
title: 'Pull Requests e Code Review'
description: 'Colaboração em projetos Git com pull requests e code review.'
permalink: /collaboration/pull-requests
---

# Pull Requests

Os pull requests (ou solicitações de pull) são uma forma de colaboração em projetos Git, em que um desenvolvedor propõe as alterações feitas em um branch para serem mescladas no branch principal (ou outra branch). Eles são comumente usados em projetos colaborativos para revisar, discutir e integrar as alterações de forma estruturada.

Ao abrir um pull request, o desenvolvedor pode descrever as alterações feitas, mencionar outros colaboradores, solicitar revisões e discutir os detalhes das mudanças. Isso permite que a equipe revise o código, faça comentários, sugira melhorias e aprove as alterações antes de serem mescladas no código principal.

## Por que usar pull requests?

Os pull requests são uma prática recomendada para colaboração em projetos Git por vários motivos:

- **Revisão de código**: Os pull requests permitem que os desenvolvedores revisem o código de seus colegas, façam comentários, sugiram melhorias e identifiquem possíveis problemas antes de mesclar as alterações no código principal. Isso ajuda a garantir a qualidade do código e a identificar bugs precocemente.
- **Colaboração estruturada**: Ao abrir um pull request, os desenvolvedores podem descrever as alterações feitas, mencionar outros colaboradores, solicitar revisões e discutir os detalhes das mudanças. Isso promove uma colaboração mais estruturada e eficiente entre os membros da equipe.
- **Histórico de alterações**: Os pull requests mantêm um registro detalhado das alterações feitas no código, incluindo quem fez as alterações, quando foram feitas e quais foram as discussões realizadas. Isso é útil para auditorias, para entender o contexto das mudanças e para rastrear a evolução do código ao longo do tempo.
- **Integração contínua**: Os pull requests são uma parte fundamental da integração contínua (CI), onde o código é frequentemente integrado e testado automaticamente. Ferramentas como GitHub Actions e GitLab CI/CD permitem configurar pipelines de CI que automatizam a verificação das alterações propostas antes de serem mescladas no código principal.

## Como criar um pull request

Para criar um pull request, siga os seguintes passos:

1. **Crie um branch**: Antes de abrir um pull request, crie um branch a partir do branch principal (geralmente `main` ou `master) para desenvolver suas alterações. Por exemplo, você pode criar um branch `feature/nova-funcionalidade` para implementar uma nova funcionalidade.
2. **Faça as alterações**: Faça as alterações desejadas no seu branch, adicione, modifique ou remova arquivos conforme necessário.
3. **Commit e push**: Após fazer as alterações, faça commits locais e envie as alterações para o repositório remoto usando `git push`.
4. **Abra o pull request**: No GitHub ou GitLab, vá até a página do repositório, clique no botão "New pull request" e selecione o branch que contém as alterações que você deseja mesclar.
5. **Descreva as alterações**: Escreva uma descrição detalhada das alterações feitas, mencione outros colaboradores, solicite revisões e discuta os detalhes das mudanças.
6. **Solicite revisões**: Se desejar, solicite revisões de outros colaboradores para revisar o código, fazer comentários e sugerir melhorias.
7. **Aguarde a aprovação**: Aguarde a revisão e a aprovação dos colaboradores antes de mesclar as alterações no código principal.
8. **Resolva os comentários**: Caso haja comentários ou sugestões de melhorias, faça as alterações necessárias e atualize o pull request.
9. **Mescle as alterações**: Após a aprovação e resolução dos comentários, mescle as alterações no branch principal clicando no botão "Merge pull request".

Alguns times de desenvolvimento podem ter regras específicas para a abertura e aprovação de pull requests, como a obrigatoriedade de revisão por pares, a execução de testes automatizados ou a integração com ferramentas de CI/CD. Certifique-se de seguir as práticas adotadas pela sua equipe ao criar e revisar pull requests.

Um estratégia muito comum é delimitar qual usuário pode fazer o merge do pull request, evitando que o próprio autor do pull request faça o merge, garantindo assim uma revisão por pares.

# Code Review

O code review (ou revisão de código) é uma prática essencial para garantir a qualidade do código, identificar possíveis problemas e promover a colaboração em equipe. Durante o code review, os desenvolvedores revisam o código de seus colegas, fazem comentários, sugerem melhorias e verificam se as boas práticas de desenvolvimento foram seguidas.

Em geral, o code review é realizado por meio de ferramentas de controle de versão, como GitHub e GitLab, que permitem que os desenvolvedores visualizem as alterações, façam comentários linha a linha e discutam as mudanças propostas. Essa prática ajuda a identificar bugs, melhorar a legibilidade do código e promover a troca de conhecimento entre os membros da equipe.

Na prática, em equipes bem organizadas, o code review é uma etapa obrigatória antes de mesclar as alterações em um projeto. Ele garante que o código seja revisado por pares, que possíveis problemas sejam identificados e que a qualidade do código seja mantida ao longo do tempo.

## Benefícios do code review

O code review traz diversos benefícios para equipes de desenvolvimento, incluindo:

- **Identificação de bugs**: Durante o code review, os desenvolvedores podem identificar bugs, problemas de lógica e falhas de segurança no código antes que ele seja mesclado no projeto principal. Isso ajuda a garantir a qualidade do software e a reduzir o número de bugs em produção.
- **Melhoria da qualidade do código**: O code review promove a troca de conhecimento entre os membros da equipe, permitindo que os desenvolvedores aprendam uns com os outros, compartilhem boas práticas e melhorem a qualidade do código. Comentários construtivos e sugestões de melhorias ajudam a elevar o nível técnico da equipe.
- **Conformidade com padrões e boas práticas**: Durante o code review, os desenvolvedores podem verificar se o código segue os padrões de codificação, as boas práticas de desenvolvimento e as diretrizes do projeto. Isso ajuda a manter a consistência do código, facilita a manutenção e evita problemas futuros.
- **Aprendizado contínuo**: O code review é uma oportunidade para os desenvolvedores aprenderem novas técnicas, ferramentas e abordagens de desenvolvimento. Ao revisar o código de seus colegas, os desenvolvedores podem expandir seu conhecimento e aprimorar suas habilidades técnicas.
- **Promoção da colaboração**: O code review promove a colaboração e a comunicação entre os membros da equipe, criando um ambiente de trabalho mais colaborativo e produtivo. Comentários construtivos, sugestões de melhorias e discussões técnicas ajudam a fortalecer o trabalho em equipe.

## Boas práticas de code review

Para obter os melhores resultados com o code review, é importante seguir algumas boas práticas:

- **Seja construtivo**: Ao fazer comentários no código de seus colegas, seja construtivo e respeitoso. Evite críticas negativas ou ataques pessoais e concentre-se em fornecer feedback útil e construtivo.
- **Seja específico**: Ao identificar problemas ou sugerir melhorias, seja específico e forneça exemplos claros. Explique o motivo por trás das sugestões e forneça orientações sobre como corrigir os problemas.
- **Mantenha o foco**: Durante o code review, mantenha o foco nos objetivos da revisão. Evite discutir questões não relacionadas ao código ou aprofundar-se em detalhes irrelevantes.
- **Respeite o tempo**: Respeite o tempo dos seus colegas e evite sobrecarregá-los com revisões extensas ou desnecessárias. Priorize os comentários mais relevantes e úteis para melhorar o código.
- **Aprenda com o feedback**: Encare o code review como uma oportunidade de aprendizado e crescimento. Esteja aberto a receber feedback, aprender com os comentários dos seus colegas e aprimorar suas habilidades técnicas.

<span style="display: flex; justify-content: space-between;"><span>[&lt; Estratégias de Branching](estrategias-branching.html 'Anterior')</span> <span>[Sumário &gt;](../ 'Sumário')</span></span>
