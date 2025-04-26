
# Useful Tips and Advanced Features for Jupyter Book

## About `_config.yml`

The `_config.yml` file is the main configuration file for your Jupyter Book.  
You can use it to set the book title, author, LaTeX output filename, theme options, language, and many other settings.  
For more details, see the [Jupyter Book configuration documentation](https://jupyterbook.org/en/stable/customize/config.html).

## How to Add Citations in Jupyter Book

To cite references in Jupyter Book, use a bibliography file (e.g., `references.bib`) and the `cite` syntax.

1. Add your reference to a `.bib` file (for example, `references.bib`):

    ```bibtex
    @article{Lemos2023,
      author    = {Lemos, Pablo and Jeffrey, Niall and Cranmer, Miles and Ho, Shirley and Battaglia, Peter},
      title     = {Rediscovering orbital mechanics with machine learning},
      journal   = {Machine Learning: Science and Technology},
      year      = {2023},
      month     = {oct},
      publisher = {IOP Publishing},
      volume    = {4},
      number    = {4},
      pages     = {045002}
    }
    ```

2. In your Markdown file, cite the reference like this:  
    `{cite}` syntax:
    ```markdown
    This is an example citation {cite}`Lemos2023`.
    ```

3. In your `_config.yml`, add:
    ```yaml
    bibtex_bibfiles:
      - references.bib
    ```
4. To display the bibliography in any file, add the following section where you want the references to appear:
    ````markdown
    ## References

    ```{bibliography}
    ```
    ````
Lemos et al. (2023) present a novel approach for discovering the laws of orbital mechanics using machine learning techniques. Their work demonstrates how AI can rediscover fundamental physical principles from data {cite}`Lemos2023`.


**For more details, see the [Jupyter Book citation guide](https://jupyterbook.org/en/stable/content/citations.html).**

## Export to LaTeX Book (PDF)

- You can convert your educational content to a LaTeX book (and then PDF) using:
  ```bash
  jupyter-book build --builder pdflatex ./
  ```
- The output `.tex` file name is set in your `_config.yml` file.
- Note: The generated LaTeX file often needs manual error fixing and should be compiled with **XeLaTeX** for best results, especially for non-English content.

## File Conversion to Markdown

When building your Jupyter Book, you may want to incorporate existing content from other formats. Here are three simple and effective ways to convert files to Markdown:

1. AI Tools (ChatGPT & LLMs)
- Paste your content (text, tables, code, etc.) into ChatGPT or similar language models and ask for Markdown conversion.
- Great for quick, small conversions and cleaning up formatting.

2. Online Tools
- Use online tools such as [Markdown Converters](https://markdownconverters.com/docs) for drag-and-drop conversion from PDF, Word, PPT, LaTeX, and more.
- Supports equations, tables, and images.

3. Pandoc (Universal Converter)
- Use Pandoc for powerful, scriptable conversion of most formats (LaTeX, Word, PDF, PowerPoint, HTML) to Markdown:
  ```bash
  pandoc input.file -o output.md
  ```

## More Resources: Installing and Using Jupyter Book

- [Jupyter Book Official Site – Installation & Usage Guide](https://jupyterbook.org/en/stable/start/overview.html)
- [Jupyter Book Tutorial by pabloinsente (GitHub)](https://github.com/pabloinsente/jupyter-book-tutorial)
- [Jupyter Book Template & Example by yenchiah](https://yenchiah.me/jupyter-book-template/docs/home.html)