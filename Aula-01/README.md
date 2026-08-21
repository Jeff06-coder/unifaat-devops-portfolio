# Aula 01 — Fundamentos de Git e Docker

## Dificuldades encontradas

- [Descreva dificuldades e como resolveu]

Tive dificuldade inicialmente para entender a organização das pastas e executar os comandos do Docker no local correto. Também tive algumas dúvidas sobre o funcionamento de branches, commits e merge no Git.

## O que aprendi

- [Descreva 3-5 conceitos que aprendeu sobre Git]

Aprendi a criar e utilizar branches para organizar o desenvolvimento.

Aprendi a fazer commits para registrar as alterações do projeto.

Aprendi a fazer merge para juntar as alterações da branch com a main.

- [Descreva 3-5 conceitos que aprendeu sobre Docker]

Aprendi a criar uma imagem utilizando um Dockerfile.

Aprendi a executar uma aplicação dentro de um container.

Aprendi a utilizar o mapeamento de portas para acessar a aplicação.

## Comandos Git praticados

- [Liste os comandos Git que utilizou]

git init — inicializar um repositório Git.

git add — adicionar arquivos para o próximo commit.

git commit — registrar uma alteração no histórico.

git status — verificar o estado dos arquivos do repositório.

git branch — visualizar e trabalhar com branches.

git checkout — trocar de branch.

git merge — juntar as alterações de uma branch em outra.

git log — consultar o histórico de commits.

git push — enviar as alterações para o GitHub.

## Comandos Docker praticados

- [Liste os comandos Docker que utilizou]

docker build — construir uma imagem a partir do Dockerfile.

docker run — criar e executar um container.

docker ps — visualizar os containers em execução.

docker logs — visualizar os logs de um container.

docker stop — parar um container.

docker rm — remover um container.

## Como executar este container

```bash
cd aula-01/app
docker build -t portfolio-aula01:1.0 .
docker run -d -p 3000:3000 portfolio-aula01:1.0
curl http://localhost:3000