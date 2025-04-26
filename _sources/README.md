# jupyter-book-tutorial

This repository provides a step-by-step tutorial and template for building a basic Jupyter Book website, with a focus on practical examples and multilingual support (English and Persian).

## What is Jupyter Book?

[Jupyter Book](https://jupyterbook.org/) is an open-source tool for building publication-quality books, documentation, and websites from Markdown, Jupyter Notebooks, and other content.

## Contents

- **Quickstart Guides:**  
  Step-by-step instructions for local setup, building, and publishing your Jupyter Book.
- **Persian Language Support:**  
  Tips and examples for writing right-to-left (RTL) content and working with Persian text.
- **Static Site Generators Overview:**  
  Introduction to static site generators, with examples and comparisons.
- **Advanced Features:**  
  How to add citations, export to LaTeX/PDF, and convert content from other formats to Markdown.
- **Sample Notebooks and Markdown Files:**  
  Ready-to-use examples for your own projects.

## Build

In the root folder, you can build and publish your book with the following commands:

```sh
jupyter-book build ./
ghp-import -n -p -f ./_build/html
jupyter-book build --builder pdflatex ./
```

## Learn More

- [Jupyter Book Official Documentation](https://jupyterbook.org/en/stable/start/overview.html)
- [Jupyter Book Tutorial by pabloinsente (GitHub)](https://github.com/pabloinsente/jupyter-book-tutorial)
- [Jupyter Book Template & Example by yenchiah](https://yenchiah.me/jupyter-book-template/docs/home.html)

---

Feel free to explore the `docs/` folder for detailed guides and examples in both English and Persian.