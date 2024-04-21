---
tags: on/dev state/seedling
date: 2020-10-10
---
# Git - How to create a submodule
Lo usé para separar el contenido (los posts) del blog
## Comandos
git filter-repo --subdirectory-filter docs/blog
git rm -r docs/blog
git submodule add https://github.com/anabel/blog.git docs/blog

### Referencias:
[Git - Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)
[Git - git-filter-branch Documentation](https://git-scm.com/docs/git-filter-branch)
