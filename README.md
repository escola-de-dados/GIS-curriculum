Olá! 

Este é um ebook baseado em R Markdown e construido com o **bookdown** (https://github.com/rstudio/bookdown). 

Baixe o repositório e abra o projeto do livro em um ambiente R com o pacote instalado. Para compilar os arquivos markdown, basta rodar o comando: `rmarkdown::render_site(encoding = 'UTF-8')`

O site com o livro em HTML será compilado na pasta `docs`. 

# Comandos úteis:

- `pdftk media/cover/cover_ebook.pdf docs/ebook-gis.pdf cat output docs/ebook-gis-cover.pdf && ps2pdf -dPDFSETTINGS=/ebook docs/ebook-gis-cover.pdf docs/ebook-gis.pdf && rm docs/ebook-gis-cover.pdf`

- Conversão de EPUB para MOBI `ebook-convert _main.epub _main.mobi`
