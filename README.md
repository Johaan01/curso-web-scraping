# Web Scraping com Python

Curso prático, em notebooks Jupyter e em português, de **coleta de dados da web com Python**: da instalação do Python até percorrer sites inteiros e salvar os dados coletados. Cada módulo alterna explicações curtas, imagens e células de código, com exercícios divididos em passos e respostas ocultas.

## Como começar

1. Baixe o repositório pelo botão **Code** (**Download ZIP** ou `git clone`).
2. Abra o Módulo 01 pelo PDF [`01-ambiente/01-ambiente.pdf`](01-ambiente/01-ambiente.pdf): ele mostra como instalar o Python, criar o ambiente e abrir os notebooks.
3. Siga os módulos em ordem.

## Módulos

1. [Preparando o ambiente](01-ambiente/): Python, ambiente virtual, `pip` e Jupyter
2. [Fundamentos da Web](02-fundamentos-da-web/): URL, HTTP, HTML, DevTools e `robots.txt`
3. [A biblioteca requests](03-requests/): pedidos, erros, cabeçalhos, cookies e sessões
4. [Seletores XPath e CSS](04-seletores-xpath-css/): extrair dados do HTML com o `parsel`
5. [Paginação e navegação](05-paginacao-e-navegacao/): percorrer sites inteiros

Os Módulos 06 a 10 (pandas, scraper robusto e APIs, projeto final, Selenium e Scrapy) serão publicados aqui quando estiverem prontos.

## Referências

Cada módulo traz, no final, a lista completa do que foi consultado. As principais referências são:

- Documentação do Python: [tutorial](https://docs.python.org/pt-br/3/tutorial/) e [venv](https://docs.python.org/pt-br/3/library/venv.html)
- [Documentação do Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/)
- [Documentação do requests](https://requests.readthedocs.io/en/latest)
- [Documentação do parsel](https://parsel.readthedocs.io/en/latest/usage.html) e a [especificação do XPath 1.0](https://www.w3.org/TR/xpath-10/) (W3C)
- MDN Web Docs: [Uma visão geral do HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Guides/Overview), e a [RFC 9110: HTTP Semantics](https://www.rfc-editor.org/rfc/rfc9110)
- [Documentação do DevTools do Firefox](https://firefox-source-docs.mozilla.org/devtools-user/)
- SEVERANCE, Charles. [*Django for Everybody*](https://www.youtube.com/watch?v=o0XbHvKxw7Y), canal freeCodeCamp.org: inspirou a apresentação do HTTP e do HTML no Módulo 02
- Sites de treino usados nos exercícios: [books.toscrape.com](https://books.toscrape.com/), [quotes.toscrape.com](https://quotes.toscrape.com/), [scrapethissite.com](https://www.scrapethissite.com/pages/) e [webscraper.io/test-sites](https://webscraper.io/test-sites)

## Créditos e uso de inteligência artificial

Curso criado por **Johaan** ([@Johaan01](https://github.com/Johaan01)).

A produção contou com o auxílio de ferramentas de inteligência artificial: principalmente o **Claude** (Anthropic), na redação, no código e nas imagens, e o **Gemini** (Google), em buscas e na seleção de referências. Todo o material foi monitorado e revisado por um humano.
