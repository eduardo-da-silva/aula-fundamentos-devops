---
title: 'Git Básico'
description: 'Visão geral e comandos essenciais do Git'
permalink: /intro/git-basico
---

# Git básico

O Git é um sistema de controle de versão distribuído amplamente utilizado no desenvolvimento de software. Ele permite que os desenvolvedores rastreiem e gerenciem as alterações feitas no código-fonte ao longo do tempo, facilitando a colaboração em equipe e a integração contínua.

Ele foi criado por Linus Torvalds em 2005 para gerenciar o desenvolvimento do kernel do Linux e se tornou uma ferramenta essencial para desenvolvedores em todo o mundo. O Git é conhecido por sua velocidade, escalabilidade e flexibilidade, tornando-o a escolha ideal para projetos de todos os tamanhos.

## Instalação

Para instalar o Git em seu sistema, siga as instruções específicas para o seu sistema operacional:

- **Linux**: Ubuntu, Debian ou derivados: você pode instalar o Git usando o gerenciador de pacotes `apt`:

  ```bash
  sudo apt update
  sudo apt install git
  ```

- **Linux**: Manjaro, Arch Linux ou derivados: você pode instalar o Git usando o gerenciador de pacotes `pacman`:

  ```bash
  sudo pacman -S git
  ```

- **macOS**: No macOS, você pode instalar o Git usando o Homebrew, um gerenciador de pacotes para macOS:

  ```bash
  brew install git
  ```

- **Windows**: No Windows, você pode baixar o instalador do Git no site oficial e seguir as instruções de instalação:

  [Download Git for Windows](https://git-scm.com/download/win)

Após a instalação, você pode verificar se o Git foi instalado corretamente executando o comando:

```bash
git --version
```

Isso exibirá a versão do Git instalada em seu sistema.

## Configuração

Antes de começar a usar o Git, é importante configurar seu nome de usuário e endereço de e-mail. Isso é necessário para identificar as alterações feitas no código e atribuí-las corretamente a você. Você pode configurar essas informações usando os comandos:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@dominio.com"
```

Substitua `Seu Nome` pelo seu nome de usuário e `seuemail@dominio.com` pelo seu endereço de e-mail. Essas informações serão usadas nos commits que você fizer no Git.

Note que foi usada a opção `--global` para configurar essas informações globalmente, ou seja, elas serão aplicadas a todos os repositórios Git em seu sistema. Se você deseja configurar essas informações apenas para um repositório específico, remova a opção `--global`. As possíveis opções de abrangência são:

- `--global`: Aplica a configuração a todos os repositórios do usuário.
- `--local`: Aplica a configuração apenas ao repositório atual.
- `--system`: Aplica a configuração a todos os repositórios do sistema.

A configuração do Git é um passo importante para garantir que suas alterações sejam atribuídas corretamente e que você possa colaborar efetivamente com outros desenvolvedores.

## Comandos essenciais

O Git possui uma série de comandos essenciais que permitem rastrear, gerenciar e colaborar em projetos de software. Alguns dos comandos mais comuns incluem:

- `git init`: Inicializa um repositório Git em um diretório existente.
- `git clone`: Clona um repositório Git existente para o seu sistema.
- `git add`: Adiciona arquivos ao índice (staging area) para serem incluídos no próximo commit.
- `git commit`: Registra as alterações feitas nos arquivos no repositório.
- `git push`: Envia os commits locais para um repositório remoto.
- `git pull`: Atualiza o repositório local com as alterações do repositório remoto.
- `git branch`: Lista, cria ou exclui branches no repositório.
- `git merge`: Combina as alterações de um branch em outro.
- `git checkout`: Altera o branch atual ou restaura arquivos do repositório.
- `git log`: Exibe o histórico de commits do repositório.

Esses comandos são essenciais para trabalhar com o Git e colaborar em projetos de software. Ao dominar esses comandos, você poderá rastrear e gerenciar as alterações no código de forma eficiente e colaborar com outros desenvolvedores de forma eficaz.

<span style="display: flex; justify-content: space-between;"><span>[&lt; Versionamento de Código](versionamento-codigo.html 'Anterior')</span> <span>[Conventional Commits &gt;](conventional-commits.html 'Próximo')</span></span>
