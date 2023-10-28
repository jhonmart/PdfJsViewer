## PDF Stream Online

Este projeto consiste em um visualizador de PDF que opera em modo de streaming, permitindo a leitura do documento em partes, evitando o download do PDF completo. Além disso, o carregamento automático está desativado, o que significa que somente as seções visualizadas serão recuperadas e exibidas, não sobrecarregando o processo com o download de partes não solicitadas.


### Como usar:

#### Para URL simples
- Junte com a URL do projeto passando para file
```js
const URL_PDF_VIEW = "https://jhonmart.github.io/pdf_stream_view";
const myUrl = "URL_AQUI";
const URL_IFRAME = `${URL_PDF_VIEW}?file=${myUrl}`;
```

#### Para URL com query
- Converta a URL para base64
- Junte com a URL do projeto passando para fileb

```js
const URL_PDF_VIEW = "https://jhonmart.github.io/pdf_stream_view";
const myUrlB64 = window.btoa("URL_AQUI");
const URL_IFRAME = `${URL_PDF_VIEW}?fileb=${myUrlB64}`;
```

[Documentação](https://github.com/mozilla/pdf.js/wiki/Debugging-PDF.js#enabling)
