---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---

# Git y Github

---

## Git

- Sistema de control de versiones (VCS)
- Commit
    - Deltas
- Ammendjhdgjhdvgf
- Stash / shelve

---

## Git

- Revert
- Reset
- Ramas
    - Checkout
- Tags
- [.gitignore](https://github.com/github/gitignore)

[Cheat sheet](https://git-scm.com/cheat-sheet)

---

## Repositorio remoto

- Descentralizado
- Clone
- Ramas local vs remote
    - Fetch
    - Pull y Push
    - Merge 
        - Conflictos: keep ours, keep theirs, resolve conflict manually

---

## Github

- Repositorio en la nube, centralizado
- Cómo contribuir a un repo
    - Pull Requests
        - Permisos
    - Fork
- Documentación
    - README.md
    - LICENSE.md
- Github Actions

---

## Flujos de trabajo

- GitFlow
![bg 45%](https://blog.jetbrains.com/wp-content/uploads/2023/05/git-flow.png)

---

## Flujos de trabajo

- Trunk Based Development

![](https://trunkbaseddevelopment.com/trunk1b.png)

---

## Buenas prácticas

- [Conventional commits](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13)
- Commits pequeños
- Commits frecuentes
- No pushear inmediatamente
- Si se trabaja con ramas: integrar la rama principal en la nuestra recurrentemente