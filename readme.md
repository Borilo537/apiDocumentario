# Documentação de API

* Escolher um local do computador para criar o projeto

* Abrir o gitbash nesta pasta

Com o gitbash aberto, executar o comando para criar a raiz do projeto:
```
mkdir NOME_PROJETO
```
* mkdir = make diretory
#

Acessar a pasta do projeto:
```
cd NOME_PROJETO
```
* cd = change diretory
#

Comando para abrir o VSCode:

```
code .
```
#
Criar o arquivo gerenciador de pacotes node:

```
npm init -y
```

* npm = node package manager

* init = inicializar

* -y = yes
#

Criar arquivo .gitignore na raiz do projeto:

```
touch .gitignore
```
* touch = cria um arquivo vazio

* .gitignore = arquivos e diretórios listados no .gitignore não serão incluídos em commits do Git.

#

Criar arquivo .env (arquivo para reservar variáveis do projeto)

```
touch .env
```


## Instalar os pacotes do projeto

Instalar pacotes para o projeto

```
npm i express nodemon dotenv
```
* i = install
3
* express = será o servidor da api

* nodemon = atualizar os arquivos alterados sem parar o servidor 

* dotenv = gerenciador de variáveis do ambiente
#

Criar pasta src

```
mkdir src
```
#
Criar arquivo server.js dentro da pasta src

```
touch src/server.js
```
#
Adicionar arquivos e pastas no gitignore

```
node_modules
.env
```
