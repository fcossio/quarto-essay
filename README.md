# quarto-essay
Write an essay in markdown, render as PDF/HTML using quarto. 

## Requirements

- [quarto](https://quarto.org/docs/getting-started.html)
- [pandoc](https://pandoc.org/installing.html)
- [latex](https://www.latex-project.org/get/)

## Getting Started

```bash
pip install cookiecutter
cookiecutter gh:fcossio/quarto-essay
cd <essay-name>
quarto render <essay-name>.md --to pdf
```