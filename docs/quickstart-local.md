# Quickstart Guide 

This guide helps you run Jupyter Book locally on Windows in a few simple steps.

## 1. Install Anaconda

- Download and install [Anaconda](https://www.anaconda.com/).
- During installation, select the option to **add Anaconda to the system PATH**.
<!-- - Open the Command Prompt and check Anaconda is installed:
  ```sh
  conda --version
  ``` -->

## 2. Download the Repository

- Go to: https://github.com/fum-cs/jupyter-book-tutorial  
  Or download directly: [Download ZIP](https://github.com/fum-cs/jupyter-book-tutorial/archive/refs/heads/main.zip)

  ![Download Repository](images/download-repository.png)

- Extract the ZIP file to a folder.

## 3. Install Jupyter Book

- In the Anaconda Command Prompt, run:
  ```sh
  pip install -U jupyter-book
  ```

## 4. Build the Book

- Go to the folder where you extracted the files:
  ```sh
  cd path\to\jupyter-book-tutorial
  ```
- Build the book:
  ```sh
  jupyter-book build ./
  ```
- Open the generated file `_build/html/index.html` in your browser to view the book.