# Geodados: uma introdução digital

Publicação online e colaborativa com os conteúdos deste [currículo desenvolvido pela School of Data sobre dados espaciais](https://github.com/school-of-data/GIS-curriculum). O código faz uso de R Markdown, [bookdown](https://github.com/rstudio/bookdown) e o Github Actions para compilar de forma automatizada as edições de conteúdo nos seguintes arquivos:

- PDF: [https://gis.escoladedados.org/ebook-gis.pdf](https://gis.escoladedados.org/ebook-gis.pdf)
- EPUB: [https://gis.escoladedados.org/ebook-gis.epub](https://gis.escoladedados.org/ebook-gis.epub)
- MOBI: [https://gis.escoladedados.org/ebook-gis.mobi](https://gis.escoladedados.org/ebook-gis.mobi)

## Diretórios
- `.github/workflows`: receita do Github para automatizar a compilação do livro;
- `docs`: contém o diretório com o livro em HTML e os arquivos finais compilados;
- `data`: dados mencionados nos tutoriais da publicação;
- `media`: imagens e mídias utilizadas no livro.

## Como editar?
Faça um fork do repositório e enviei um *pull request* editando o arquivo markdown de um capítulo.

# Comandos úteis:

- Juntando PDFs: `pdftk media/cover/cover_ebook.pdf docs/ebook-gis.pdf cat output docs/ebook-gis-cover.pdf` 
  
- Conversão de EPUB para MOBI: `ebook-convert _main.epub _main.mobi`
