# App Hello World

Este é um projeto simples criado utilizando o Create React App (CRA) para demonstrar um aplicativo básico em React.

## Tecnologias Utilizadas

- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **Create React App (CRA)**: Ferramenta para configurar rapidamente um projeto React com boas práticas.
- **Webpack**: Empacotador de módulos.
- **Babel**: Transpilador de código JavaScript moderno.
- **ESLint**: Ferramenta de análise de código.
- **Jest**: Framework de testes unitários.
- **Testing Library**: Conjunto de utilitários para testar componentes React.

## Estrutura do Projeto

```
.gitignore
package.json
public/
  - favicon.ico
  - index.html
  - logo192.png
  - logo512.png
  - manifest.json
  - robots.txt
README.md
src/
  - App.css
  - App.js
  - App.test.js
  - index.css
  - index.js
  - logo.svg
  - reportWebVitals.js
  - setupTests.js
```

## Passo a Passo para Executar o Projeto

### Pré-requisitos

- Node.js instalado na máquina.
- Gerenciador de pacotes npm ou yarn.

### Instalação

1. Clone o repositório:
   ```sh
   git clone <URL_DO_REPOSITORIO>
   cd app-hello-world
   ```
2. Instale as dependências:
   ```sh
   npm install
   # ou
   yarn install
   ```

## Scripts Disponíveis

No diretório do projeto, você pode executar:

### `npm start`
Executa o aplicativo no modo de desenvolvimento. Abra [http://localhost:3000](http://localhost:3000) para visualizá-lo no navegador.

### `npm test`
Executa os testes unitários. Veja a seção sobre executar testes para mais informações.

### `npm run build`
Compila o aplicativo para produção na pasta `build`. Seu aplicativo está pronto para ser implantado!

### `npm run eject`
Remove a abstração do CRA e expõe todas as configurações que estavam ocultas no projeto.

Após rodar esse comando:

- O arquivo `package.json` é modificado para incluir as dependências específicas do Webpack, Babel, etc., que antes estavam gerenciadas internamente pelo CRA.
- Os arquivos de configuração são criados ou expostos, como:
   - `config/webpack.config.js`
   - `.babelrc` ou equivalente
   - Configurações de ESLint, Jest (testes), e outros.

A partir desse ponto, o controle total da configuração do projeto passa a ser do desenvolvedor.

## Regras de Negócio

Este projeto é um exemplo básico de um aplicativo React que exibe uma mensagem "Hello World". Ele serve como ponto de partida para desenvolvedores que desejam aprender ou iniciar um novo projeto com React.

## Estrutura dos Arquivos

- **`public/`**: Contém arquivos estáticos como `index.html`, ícones e manifestos.
- **`src/`**: Contém os arquivos de código-fonte do aplicativo.
   - **`App.js`**: Componente principal do aplicativo.
   - **`App.css`**: Estilos para o componente App.
   - **`App.test.js`**: Testes unitários para o componente App.
   - **`index.js`**: Ponto de entrada do aplicativo.
   - **`index.css`**: Estilos globais.
   - **`reportWebVitals.js`**: Utilitário para medir a performance do aplicativo.
   - **`setupTests.js`**: Configuração para testes.

## Contribuição

Sinta-se à vontade para contribuir com este projeto. Para isso, siga os passos abaixo:

1. Faça um fork do projeto.
2. Crie uma branch para sua feature:
   ```sh
   git checkout -b feature/nova-feature
   ```
3. Commit suas mudanças:
   ```sh
   git commit -m 'Adiciona nova feature'
   ```
4. Faça um push para a branch:
   ```sh
   git push origin feature/nova-feature
   ```
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

Autor: Renan