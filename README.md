# Getting Started with Create React App
App criado utilizando React

# O que é o Create React App (CRA)?
O CRA é uma ferramenta que ajuda a configurar rapidamente um projeto React com boas práticas, sem exigir que o desenvolvedor lide diretamente com configurações complexas como:

Webpack (para empacotamento de módulos)
Babel (para transpilar código JavaScript moderno)
ESLint (para análise de código)
Outros arquivos de configuração necessários.
Por padrão, essas configurações ficam escondidas, permitindo ao desenvolvedor focar apenas no desenvolvimento da aplicação.

### `npm start`
Para rodar o app no modo de desenvolvimento.
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm test`
Para rodar os testes unitários.
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`
Compila o App para produção da pasta build.
Your app is ready to be deployed!
See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
O comando npm run eject remove essa abstração e expõe todas as configurações que estavam ocultas no projeto. Ele faz isso copiando os arquivos de configuração (como Webpack, Babel, ESLint) para o diretório do seu projeto, deixando-os disponíveis para edição.

Após rodar o comando:

O arquivo package.json é modificado para incluir as dependências específicas do Webpack, Babel, etc., que antes estavam gerenciadas internamente pelo CRA.
Os arquivos de configuração são criados ou expostos, como:
config/webpack.config.js
.babelrc ou equivalente
Configurações de ESLint, Jest (testes), e outros.
O controle total da configuração do projeto passa a ser do desenvolvedor.
