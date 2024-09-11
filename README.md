# Hextra

https://github.com/imfing/hextra

Modern, responsive, batteries-included Hugo theme for creating beautiful static websites.

https://imfing.github.io/hextra/docs/getting-started/

### Setup Hextra as Git submodule

```
hugo new site . --force --format=yaml
git submodule add https://github.com/imfing/hextra.git themes/hextra
hugo new content/_index.md
hugo new content/docs/_index.md
hugo server --buildDrafts --disableFastRender
hugo server
```

Configure hugo.yaml to use Hextra theme by adding the following:

```
theme: hextra
```