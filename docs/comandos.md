# Comandos usados no terminal para este projeto TypeScript

Este arquivo reúne os principais comandos executados no terminal para configurar, compilar e rodar este projeto.

## Comandos básicos de navegação

### `cd`
Muda de pasta no terminal.
Exemplo:
```bash
cd /home/renato/GitHub/typescript
```

### `ls`
Lista os arquivos e pastas da pasta atual.
Exemplo:
```bash
ls
```

## Comandos de inicialização do projeto

### `npm init -y`
Cria o arquivo `package.json` com configuração padrão para o projeto Node.js.

## Comandos de instalação de dependências

### `npm install -D typescript`
Instala o TypeScript como dependência de desenvolvimento.

### `npm install -D tsx`
Instala o `tsx`, que permite executar arquivos TypeScript diretamente no Node.js.

## Comandos de configuração do TypeScript

### `npx tsc --init`
Gera o arquivo `tsconfig.json` com as configurações iniciais do compilador TypeScript.

## Comandos de compilação

### `npx tsc`
Compila os arquivos `.ts` para JavaScript usando as regras do `tsconfig.json`.

### `npm run dist`
Executa o script definido em `package.json` para compilar o projeto com `npx tsc`.

## Comandos para executar o projeto

### `npm run start:dev`
Roda o projeto diretamente em TypeScript com o `tsx`, sem precisar compilar primeiro.

### `npm run start:watch`
Executa o projeto em modo observação, reiniciando automaticamente quando houver alterações.

### `npm run start:dist`
Compila o projeto e depois executa o arquivo JavaScript gerado.

### `node src/index.js`
Executa o arquivo JavaScript já compilado pelo TypeScript.

## Resumo rápido

Os comandos principais usados neste projeto são:

```bash
npm init -y
npm install -D typescript
npm install -D tsx
npx tsc --init
npx tsc
npm run dist
npm run start:dev
npm run start:watch
npm run start:dist
node src/index.js
```
