# Holistix Home Spray

![Logo Holistix](https://www.holistix.com.br/arquivos/logo-loja-2x.png?v=637677734139100000)

---

<br>
<br>


### Como foi feito

* :nail_care: Utilizei o pre processador [stylus](https://stylus-lang.com/)
* :alien: Sem bibliotecas javascript! Tudo feito com um `index.html` e `css`
* :wheelchair: No `index.html` foram incluidas as melhores praticas de SEO e acessibilidade
* :older_man: Foi utilizado o [autoprefixer-stylus](https://github.com/jescalan/autoprefixer-stylus) para a geracao de propriedades que deem suporte a browsers antigos/legados

### Estrutura

* Na raiz do projeto existe a pasta `src`, que contem todo o projeto
* Ainda na raiz o `package.json` inclui as dependencias e tras informacoes adicionais sobre o projeto
* O arquivo principal eh o `index.html` para visualizar o projeto basta abri-lo no seu navegador
* Na pasta `css` esta o `CSS` gerado automaticamente pelo `autoprefixer + stylus`
* Em `src/images` estao todas as imagens usadas no projeto, assim como favicon
* As fontes estao em `static/fonts` todas no formato `.woff2`
* Finalmente na pasta `styl` esta o `css` usado no projeto, o arquivo principal eh o `main.styl` ele que chama os outros arquivos.

### Como rodar o projeto

* :memo: Clone o repositorio
* :package: Instale as dependencias rodando o comando `npm install`
* :computer: Abra o arquivo `index.html` no seu navegador
* :tada: Pronto!

<br>

> **Obs.:** Para gerar um novo arquivo `.css` eh so rodar o comando `npm run css`