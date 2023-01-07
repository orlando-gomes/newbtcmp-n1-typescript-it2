

<h1 align ="center">
	newbtcmp-n1-typescript-it2
</h1>



## Assuntos cobertos!

- Como adicionar o typescript no projeto
- Como adicionar pacotes e seus tipos (Express)
- Como configurar criar o arquivo de configuração do typescript (tsconfig.json)
- Como configurar o arquivo de conversão do typescript para .js
- Como rodar o projeto

---
</br></br>

## Comandos iniciais

```bash

# Iniciar este repositório
$ yarn init -y

# Instalar typescript
$ yarn add typescript -D

# Instalar o express e os tipos
$ yarn add express @types/express

# criando o tsconfit.json
$ yarn tsc --init

```
---
</br></br>

## Especificando o local de build

Abrir o tsconfig.json e descomentar a linha

```json

// "outDir": "./",

```
E mudar para
```json

"outDir": "./dist",

```
---
</br></br>

## Executando o build

Executar o comando

```bash

$ yarn tsc

```
---
</br></br>

## Executando o projeto

Executar o comando

```bash
# O Node não reconhece arquivos typescript
# Vamos rodar o arquivo .js criado no diretório de build
$ node dist/index.js

```
---
</br></br>