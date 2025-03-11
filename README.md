---
title: 'Fundamentos de DevOps - Bacharelado em Sistemas de Informação'
permalink: /
---

# Informações preliminares

Essas são notas de aula para o uso nas disciplinas de Fundamentos de DevOps do curso de Bacharelado em Sistemas de Informação do [IFc - Campus Araquari](https://bsi.araquari.ifc.edu.br/). O conteúdo foi desenvolvido pelo [Prof. Dr. Eduardo da Silva](https://github.com/eduardo-da-silva/).

Esse material ainda está em construção e o seu conteúdo é melhor absorvido durante as atividades realizadas em sala de aula.

# Ementa do curso

Conceitos de versionamento de código, repositórios de código e suas ferramentas. Introdução à metodologia DevOps e ferramentas que auxiliam no processo de entrega, desenvolvimento e gerenciamento de sistemas computacionais ao longo do ciclo de vida de desenvolvimento de sistemas em organizações. Introdução à abordagem integração contínua (CI) e entrega contínua (CD). Técnicas de automação de pipeline e ferramentas. Introdução à containers e sua utilização em ambientes de desenvolvimento e produção. Introdução à aspectos de segurança em DevOps.

# Objetivos da disciplina

Capacitar os alunos nos fundamentos e práticas de DevOps, com ênfase em versionamento de código, metodologias ágeis e ferramentas de gerenciamento de repositórios.

Os alunos aprenderão a implementar pipelines de integração contínua (CI) e entrega contínua (CD).

Além disso, desenvolverão habilidades em conteinerização e práticas de segurança.

A disciplina fornece uma base sólida para que os estudantes possam automatizar processos de desenvolvimento, gerenciar infraestrutura como código e promover a colaboração efetiva entre equipes de desenvolvimento e operações.

# Conteúdo programático e cronograma

### Semana 1-2: Introdução ao DevOps e Versionamento de Código

- Fundamentos de DevOps e sua importância
- Git básico: instalação, configuração e comandos essenciais
- Branches, merges e resolução de conflitos
- Práticas de versionamento e conventional commits

### Semana 3-4: Gestão de Repositórios e Colaboração

- GitHub/GitLab: funcionalidades e boas práticas
- Pull requests e code review
- Estratégias de branching (GitFlow, trunk-based)
- Projetos práticos em equipe

### Semana 5-6: Automação e CI/CD

- Introdução à integração contínua
- Configuração de pipelines CI/CD
- GitHub Actions e GitLab CI
- Automação de testes e builds

### Semana 7-8: Containers e Docker

- Fundamentos de containerização
- Docker: conceitos básicos e comandos
- Dockerfile e Docker Compose
- Práticas com containers em desenvolvimento

### Semana 9-10: Orquestração de Containers

- Introdução ao Kubernetes
- Pods, services e deployments
- Gerenciamento de configurações
- Práticas de orquestração

### Semana 11-12: Infraestrutura como Código (IaC)

- Conceitos de IaC
- Terraform: fundamentos e práticas
- Ansible: automação de configuração
- Implementação de infraestrutura automatizada

### Semana 13-14: Monitoramento e Observabilidade

- Fundamentos de monitoramento
- Prometheus e Grafana
- Logs e tracing distribuído
- Práticas de observabilidade

### Semana 15-16: DevSecOps

- Segurança em pipelines CI/CD
- Análise estática de código
- Scanning de vulnerabilidades
- Práticas de segurança em containers

### Semana 17-18: Projeto Final e Revisão

- Desenvolvimento de projeto completo em equipe
- Implementação de pipeline completo
- Apresentações dos projetos
- Revisão geral e conclusão do curso

**Carga Horária:**

- 18 semanas x 2 encontros semanais
- Aulas de 50 minutos
- Total: 60 horas

## Sumário

1. [Aula 1 - Introdução ao DevOps e Versionamento de Código](intro/intro.md)
2. [Aula 2 - O conceito de PWA](aplicacoes-pwa/intro.md)  
   2.1 [PWA com Vite e VueJS](aplicacoes-pwa/pwa-com-vite-e-vuejs.md)  
   2.2 [Criando uma primeira aplicação Vue](aplicacoes-pwa/criando-aplicacao-vue.md)  
   2.3 [Configuração do VueJs com PWA](aplicacoes-pwa/configuracao-vue-com-pwa.md)  
   2.4 [Deploy da aplicação](aplicacoes-pwa/deploy-aplicacao.md)
3. [Aula 3 - A API FakeStore](listagem-produtos/intro.md)  
   3.1 [Listagem de produtos](listagem-produtos/listagem-de-produtos.md)  
   3.2 [Estilização básica](listagem-produtos/estilizacao-basica.md)  
   3.3 [Menu Superior Responsivo](listagem-produtos/menu-superior-responsivo.md)
4. [Aula 4 - Composables](composables-responsividade/intro.md)  
   4.1 [Criando o primeiro composable](composables-responsividade/criando-um-composable.md)  
   4.2 [Uso nos componentes](composables-responsividade/uso-nos-componentes.md)  
   4.3 [Desafio](composables-responsividade/desafio.md)  
   4.4 [Correção do desafio](composables-responsividade/correcao.md)
5. [Aula 5 - Responsividade com componentes dinâmicos](componentes-dinamicos/intro.md)  
   5.1 [Criando os arquivos de menu superior](componentes-dinamicos/criando-arquivos-menu-superior.md)  
   5.2 [Editando o HomeView](componentes-dinamicos/editando-homeview.md)  
   5.3 [Configurando o composable de responsividade](componentes-dinamicos/configurando-composable-responsividade.md)  
   5.4 [Finalizando o uso dos componentes dinâmicos](componentes-dinamicos/finalizando-uso-componentes-dinamicos.md)  
   5.5 [Desafio](componentes-dinamicos/desafio.md)  
   5.6 [Correção do desafio](componentes-dinamicos/correcao.md)
6. [Aula 6 - Projeto da Loja Virtual - Tutorial](loja-virtual/intro.md)  
   6.1 [Organização do Layout](loja-virtual/layout.md)  
   6.2 [Ajustes finos na organização do layout](loja-virtual/layout-grid.md)  
   6.3 [Listagem de produtos](loja-virtual/listagem-produtos.md)  
   6.4 [Ajustes no cabeçalho e rodapé](loja-virtual/cabecalho-rodape.md)  
   6.5 [Preparando a tela de login](loja-virtual/preparando-login.md)
7. [Aula 7 - Autenticação em PWA](autenticacao/intro.md)  
   7.1 [Configuração do Passage](autenticacao/configuracao-passage.md)  
   7.2 [Configuração no Vue](autenticacao/configuracao-no-vue.md)
8. [Aula 8 - Loja virtual - adicionando produtos e categorias](loja-virtual-adicionar-produtos/intro.md)  
   8.1 [Camada de serviço](loja-virtual-adicionar-produtos/camada-servico.md)  
   8.2 [Camada de armazenamento](loja-virtual-adicionar-produtos/camada-armazenamento.md)  
   8.3 [Modal de criação de categorias](loja-virtual-adicionar-produtos/modal-criacao-categorias.md)  
   8.4 [Formulário de criação de produtos](loja-virtual-adicionar-produtos/formulario-criacao-produtos.md)  
   8.5 [Ajustes na listagem de produtos](loja-virtual-adicionar-produtos/ajustes-listagem-produtos.md)
