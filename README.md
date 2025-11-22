# README.md

## Installation
```bash
cd ~/Desktop
uv init jbook
cd jbook
uv venv
source .venv/bin/activate
uv add jupyter-book ipykernel

# The following command uses the jupyter book CLI to create a new book.
# Click the Enter key when prompted with "Would you like jupyter book start now? (Y/n)"
jupyter-book
```
To open the new book, open `https\\localhost:3000` in a web browser.

## Deployment
I followed directions on https://jupyterbook.org/stable/get-started/publish/ to create a web site using GitHub Pages.

```
git remote add origin https://github.com/aubreymoore/jbook.git
git branch -M main
git push -u origin main
```
