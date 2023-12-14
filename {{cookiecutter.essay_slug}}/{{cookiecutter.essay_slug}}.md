---
title: {{cookiecutter.title}}
subtitle: {{cookiecutter.subtitle}}
author: 
    - name: {{cookiecutter.author_name}} {% if cookiecutter.author_email != '' %} ({{cookiecutter.author_email}}) {% endif %}
date: {{cookiecutter.date}}
date-format: full
format:
    pdf:
        pdf-engine: xelatex
        papersize: a4
        resources-path: ./resources
        documentclass: article
        cite-method: natbib
        biblio-style: abbrv
        toc: true
        number-sections: true
bibliography: ./resources/bibliography.bib
---

# Introduction

This document shows how to render quarto essays as PDF/HTML.

# Getting started

```bash
pip install cookiecutter
cookiecutter gh:fcossio/quarto-essay
cd <essay-name>
quarto render <essay-name>.md --to pdf
```

In order to cite you can follow the instructions in the citation guide [@quarto-citation]. The bibliography is located in `./resources/bibliography.bib`.

# Results



# Discussion
