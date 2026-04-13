---
title: Déploiement et mises à jour
date: 2026-04-12 15:00:00
tags:
  - hexo
  - github
cover: /images/posts/post2.jpg
---

Quand le dépôt est connecté à **GitHub Pages** avec **GitHub Actions** comme source de publication, chaque push sur la branche configurée (par exemple `main`) déclenche un workflow : installation des dépendances, `hexo generate`, puis mise en ligne du dossier `public/`.

Tu n’as pas besoin de committer le site généré à la main : la CI s’en charge. Pour le détail des commandes Git et du flux, voir `NOTE_GIT_ET_PAGES.md` à la racine du projet.
