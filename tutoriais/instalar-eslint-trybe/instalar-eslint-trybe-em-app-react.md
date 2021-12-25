# Instala e configura eslint da Trybe em aplicação React

1. Baixe e instale a extensão Eslint no vscode

2. Criar projeto React:

  `npx create-react-app nome-do-projeto`
  
3. Instala ESlint da Trybe:

  `npm install eslint-config-trybe-frontend -D`
  
4. Inicia ESlint no projeto:

  `npx eslint --init`
  
5. Selecione as opções abaixo:

  `To check syntax and find problems`
  
  `JavaScript modules (import/export)`
  
  `React`
  
  `No`
  
  `Browser`

  `JSON`
 
  `Yes`
  
6. Alterar linha 7 do arquivo .eslintrc.json para:

 `"trybe-frontend"`
 
7. Adicionar linha nos scripts do arquivo package.json:

 ` "lint": "eslint --no-inline-config --no-error-on-unmatched-pattern -c .eslintrc.json . --ext .js, .jsx"`
