# technology-innovations

## Create a new repository on GitHub

`git clone https://github.com/<repository_uri>`  
`cd <repository>`


## Creating the Virtual Environment

`python -m venv venv`  
`source venv/bin/activate`  
`pip --version`  
`pip install mkdocs-material`

## Open in VS Code
`.code`

## new mkdocs website

`mkdocs new .`
`mkdocs serve`

This should create the mkdocs.yml and docs folder to start with.

## Publish to GitHub

add a folder `.github/workflows/ci.yml`

- Go to GitHub Settings 
- Source > Deploy from a branch
- Branch `gh-pages` and Save

