# File Conversion to Markdown

When building your Jupyter Book, you may want to incorporate existing content from other formats. Here are reliable methods to convert common file types to Markdown:

## 1. **LaTeX to Markdown**
- **Pandoc**:  
  ```bash
  pandoc input.tex -o output.md --mathjax
  ```
  - Preserves equations (converts to MathJax)
  - Handles citations and cross-references

- **Online/Desktop Tool**:  
  - [Markdown Converters](https://markdownconverters.com/docs) (Supports LaTeX → Markdown with equation handling)

## 2. **PowerPoint to Markdown**
- **Export as Text**:  
  1. Save PPT as `.txt` (File → Save As → Plain Text)  
  2. Clean up and add Markdown syntax (headers, lists)

- **Automated Tools**:  
  - [PPT-to-Markdown](https://github.com/matthuisman/ppt-to-markdown) (Python script)  
  - [Markdown Converters](https://markdownconverters.com/docs) (Handles PPT/PPTX → MD)

## 3. **PDF to Markdown**
- **Pandoc** (Best for text-heavy PDFs):  
  ```bash
  pandoc input.pdf -o output.md --pdf-engine=xelatex
  ```

- **OCR-Based Tools**:  
  - [Mathpix](https://mathpix.com) (Extracts text + equations)  
  - [Markdown Converters](https://markdownconverters.com/docs) (PDF → MD with formatting)

## 4. **Word to Markdown**
- **Built-in Export**:  
  Word (2016+) → File → Export → Markdown (.md)

- **All-in-One Solution**:  
  - [Markdown Converters](https://markdownconverters.com/docs) (DOCX → MD with table/image support)

## Key Features of [Markdown Converters](https://markdownconverters.com/docs):
- **Multi-Format Support**: LaTeX, PDF, PPT, Word, HTML → Markdown  
- **Desktop App**: Available for Windows/macOS (Offline conversion)  
- **Math Support**: Preserves LaTeX equations during conversion  

---

**Note**: For batch processing or complex documents, combine these tools with scripting (e.g., Pandoc + Python). Always validate converted Markdown in your Jupyter Book preview!  