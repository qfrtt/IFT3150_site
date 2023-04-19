---
title: /
layout: home
permalink: /
---

# Compile time binary obfuscation

# Resume
Notre projet a pour but d'utiliser les techniques d'obfuscation pour generer un code complexe a analyser qui
rendra la retro-ingenieurie extremement difficile et permettra de decourager les pirates informatique de nous cibler.

On utilise les methodes d'obfuscation de base :
- La substituion d'instructions : celle-ci a pour but de remplacer des expressions simples par des expressions complexes equivalente.
- Le flux de controle trompeur : celle-ci consiste a ajouter du code supplementaire pour cacher le flux de controle.
- Le flux de controle aplati : celle-ci consiste a melange les blocs de code independants

Pour appliquer ces methodes sans pour autant modifier le code source directement on utilise LLVM qui est un compilateur open-source
avec la version O-LLVM qui est une modification du compilateur qui implemente ces methodes directement lors de la compilation.

Notre proof of concept est une application client/serveur de chat qui integre ces methodes la en plus d'autres methodes qui rendent l'analyse statique et dynamique du code difficile par le bias de l'anti-debugging et un networking chiffree par cle privee.



 References pour le site : jekyll-theme-console
