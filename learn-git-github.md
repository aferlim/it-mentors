# Bem vindo ao nosso minicurso de Git e GitHub

## Requisitos

- Git instalado
- Conta no Github.com

# Git

## Introdução

Exemplo ZIP

Git é diferente de GitHub

Git é um software de controle de versão - VCS Version Control System

Importância do GIT

- VCS Centralizado
- VCS Distribuido

## Vantagens

- Controle de historico
- Trabalho em equipe
- Ramificações
- Segurança
- Organização

## Hands On

Instalação

Fluxo de trabalho - Workspace / Index (Staging) / Head

Git Init - git init

Git ADD

Git Commit



# Passo a passo:

mkdir aulagit1

git init

git status - Comando para descobrir o status atual do workspace

git --help - saiba mais sobre o git

Nós criamos um novo repositório git no gitHUB, vazio
Apontamos nosso repositorio local para este, atraves do comando:

git remote add origin https://github.com/aferlim/aulagit1.git

subir para repositorio remoto: git push

## Ramificações

git branch release
git checkout -b feature

git merge nome_branch

git branch -d nome_branch - Deleta a branch

git branch - lista as branchs

## Git checkout

Troca de branch
Remove versão do workpspace

git commit -m "meu primeiro commit" - Envia objetos da index para a HEAD

git log

## Atualizando workspace

Git Clone

git remote add origin

.gitignore

# GitHub

GitHub é uma rede social para programadores

## Vantagens

Repositórios ilimitados
Hospedagem de código fonte

Características de rede social

- Conhecer pessoas e projetos novos
- Aprender a programar
- Evoluir técnicamente

GitHub Pages integrado
Colaboração

## Git Pages

No GitHub crie um novo repositório conforme padrão "username.github.io", onde username é o seu nome de usuário ou de sua corporação.

    git remote add origin https://github.com/aferlim/aferlim.github.io.git`

git branch -M main

git push -u origin main

# Links úteis

https://www.markdownguide.org/cheat-sheet/

https://gist.github.com/zeroed/cb7ec60e01cf8fb3be297b944f9da03e

https://rogerdudler.github.io/git-guide/index.pt_BR.html

# Links Inúteis

https://gist.github.com/parmentf/035de27d6ed1dce0b36a


# Desafio

## LearnGit

https://learngitbranching.js.org/

## HackerHank

https://www.hackerrank.com/
