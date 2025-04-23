# Publishing Jupyter Book on GitHub Pages

This guide explains how to publish your Jupyter Book online using GitHub Pages.

## 1. Install Git and GitHub Desktop

- Download and install [Git](https://git-scm.com/download/win).
- Download and install [GitHub Desktop](https://desktop.github.com/).

## 2. Create a GitHub Repository

- Go to [GitHub](https://github.com/) and sign in.
- Click **New repository** and create a new repository (e.g., `my-jupyter-book`).

## 3. Clone the Repository

- Open GitHub Desktop.
- Click **File > Clone repository** and select your new repository.
- Choose a folder to clone the repository to your computer.

## 4. Copy Book Files

- Copy all files and folders (including `_build/html`) from your Jupyter Book project into the cloned repository folder.

## 5. Commit and Push Changes

- In GitHub Desktop, you should see the new files listed as changes.
- Add a summary (e.g., "Add Jupyter Book files") and click **Commit to main**.
- Click **Push origin** to upload your changes to GitHub.

## 6. Publish with ghp-import

- Open the Command Prompt in your repository folder.
- Run the following command to publish your book to GitHub Pages:
  ```sh
  ghp-import -n -p -f ./_build/html
  ```
- This will create a `gh-pages` branch and publish your site.

## 7. View Your Book Online

- Go to your repository on GitHub.
- Click **Settings > Pages**.
- Your site will be available at the URL shown there (usually `https://<username>.github.io/<repository>/`).

## 8. Update Your Book After Changes

- If you make any changes to your book content:
  1. Rebuild the book:
     ```sh
     jupyter-book build ./
     ```
  2. Run the `ghp-import` command again to update the published site:
     ```sh
     ghp-import -n -p -f ./_build/html
     ```
  3. Commit and push any other changes to your repository if needed.

---