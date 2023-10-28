## PDF Stream Online

> Este projeto consiste em um visualizador de PDF que opera em modo de streaming, permitindo a leitura do documento em partes, evitando o download do PDF completo. Além disso, o carregamento automático está desativado, o que significa que somente as seções visualizadas serão recuperadas e exibidas, não sobrecarregando o processo com o download de partes não solicitadas.

### Como usar:
- Converta a URL para base64
- Junte com a URL do projeto passando o base64 com o nome de url

```js
const URL_PDF_VIEW = "https://jhonmart.github.io/pdf_stream_view";
const myUrlB64 = window.btoa("URL_AQUI");
const URL_IFRAME = `${URL_PDF_VIEW}?url=${myUrlB64}`;
```
