# dssales-resources

### Criando projeto com o `create-react-app`:

`npx create-react-app front-web --template typescript`

### Link do projeto no Figma: 

https://www.figma.com/file/vnK7024sr7YkEe3QdvAFT6/BDS3-dashboard?node-id=0%3A1

### Configuração do Eslint e Prettier

1) instalar as dependências necessárias:

`yarn add eslint prettier eslint-plugin-react-hooks @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-plugin-react eslint-config-prettier eslint-plugin-prettier  --dev`

2) Certifique-se de instalar as extensões do Eslint e Prettier no VSCode

3) Copiar o arquivo `.eslintrc.js` e adicionar na raiz da pasta `front-web`

3) Copiar o arquivo `.prettierrc.js` e adicionar na raiz da pasta `front-web`

4) Editar preferências do VSCode:

```
"editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
},
"editor.formatOnSave": true, 
"eslint.alwaysShowStatus": true,
```

## React-flatpickr
- https://flatpickr.js.org/
- https://github.com/haoxins/react-flatpickr

## Apex Charts
- https://apexcharts.com/

## High order functions JavaScript e TypeScript

Estes vídeos são necessários para entender:
- Funções de alta ordem: map, filter, reduce, sort
- Como essas funções foram aplicadas para transformar os dados a API nos dados necessários para plotar os gráficos

#### Parte 1:
[![Image](https://img.youtube.com/vi/ZYPQmfcZGxg/mqdefault.jpg "Vídeo no Youtube")](https://youtu.be/ZYPQmfcZGxg)

#### Parte 2:
[![Image](https://img.youtube.com/vi/IL9UfTcCXL4/mqdefault.jpg "Vídeo no Youtube")](https://youtu.be/IL9UfTcCXL4)


## Alguns links úteis para quem quiser aprofundar em algum conceito mencionado durante as aulas:

- ### Como formatar números/preços usando apenas JavaScript
https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Intl/NumberFormat

## Entendendo o React Hook useMemo

- https://pt-br.reactjs.org/docs/hooks-reference.html#usememo

- https://medium.com/@devjpnobrega/primeiros-passos-com-react-hooks-usememo-e-usecallback-13d54da4f9ba

## Propriedade  `box-sizing` do CSS

- http://sergiolopes.org/css-box-sizing-border-box/
