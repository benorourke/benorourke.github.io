# benorourke.github.io

## Stack

- [Hugo](https://gohugo.io/) — static site generator
- [Archie](https://github.com/athul/archie) — theme (git submodule)
- GitHub Actions — builds and deploys on push to `main`
- GitHub Pages — hosting

## Local dev

```bash
hugo server --buildDrafts
```

Then open [http://localhost:1313](http://localhost:1313).

## New post

```bash
# Engineering
hugo new content engineering/my-post-title.md

# Recipe
hugo new content recipes/indian/my-recipe.md
```

## Deploy

Push to `main` — GitHub Actions handles the rest.
