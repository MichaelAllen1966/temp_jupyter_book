# Getting started with Jupyter Books

## Install requirements

`pip install jupyter-book`
`pip install ghp-import`


## Method overview

1. Set up repo on GitHub
1. Clone repo to local computer
1. Add some content
1. Write `_toc.yml` table of contents

# Build book

`jupyter-book build ./`
`ghp-import -n -p -f _build/html`

Add line to .bashrc
alias book="jupyter-book build ./ && ghp-import -n -p -f _build/html"

