# open-letter

Served at https://tillwenke.github.io/open-letter/

- `index.html` – page with the statement and a download button
- `statement.pdf` – downloadable PDF
- `pdf-source.html` – source for the PDF. Regenerate with:

```
google-chrome --headless --no-pdf-header-footer --print-to-pdf=statement.pdf "file://$PWD/pdf-source.html"
```
