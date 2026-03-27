## DVRPC Documentation

This project uses [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)

Source: https://github.com/squidfunk/mkdocs-material

---

install: `docker pull squidfunk/mkdocs-material`

build: `docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material build`

serve: `docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material`