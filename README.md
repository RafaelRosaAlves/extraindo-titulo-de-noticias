# Web Scraping de Notícias com Python

Este projeto consiste em um notebook Python que utiliza a técnica de Web Scraping para extrair manchetes de grandes portais de notícias brasileiros.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RafaelRosaAlves/extraindo-titulo-de-noticias/blob/main/extraindo-titulos-de-noticias.ipynb)

##  Descrição

O script realiza requisições HTTP para os sites, baixa o conteúdo HTML e utiliza a biblioteca **Beautiful Soup** para navegar na estrutura da página e capturar textos específicos (títulos e subtítulos).

O projeto está dividido em duas partes principais:
1.  **Extração do Globo.com:** Captura as manchetes principais identificadas pela tag `<h2>` e classe `post__title`.
2.  **Extração do R7.com:** Captura subtítulos identificados pela tag `<h3>` e um conjunto específico de classes de formatação.

## 🛠 Tecnologias Utilizadas

* **Python 3**
* **Beautiful Soup 4** (bs4): Para fazer o parsing do HTML.
* **Requests:** Para fazer as requisições HTTP aos sites.
* **Lxml & Html5lib:** Parsers utilizados pelo Beautiful Soup.

##  Como Executar

Você pode visualizar e executar este notebook diretamente no Google Colab clicando no botão "Open in Colab" acima.

Caso queira rodar localmente, certifique-se de instalar as dependências:

```bash
pip install beautifulsoup4 requests lxml html5lib
