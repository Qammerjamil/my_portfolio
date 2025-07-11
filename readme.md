# building portfolio 

we will use mkdocs to build the portfolio mkdocs is a static site generator that is geared towards project documentation. It uses markdown files to create a static website.

link to the documentation: https://www.mkdocs.org/getting-started/

## 1 install mkdocs
conda create -n mkdocs python=3.12
conda activate mkdocs
pip install mkdocs

## 2 create a new mkdocs project
mkdocs new my-portfolio
cd my-portfolio

## 3 run the development server
mkdocs serve

this is how you can specify the port and host
mkdocs serve --dev-addr=127.0.0.1:8501

## 4 build the static site
mkdocs build