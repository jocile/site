---
layout: page
title: Sobre
permalink: /sobre/
weight: 3
---

## **Sobre mim**

Olá, eu sou **{{ site.author.name }}** :wave:,

Atualmente atuo como instrutor de informática no [SENAC](https://cursos.ce.senac.br/), onde ministro aulas práticas de desenvolvimento de sistemas, lógica de programação, webdesigne, edição gráfica, informática básica com aplicativos de escritório.

<div class="row">
{% include about/skills.html title="Abilidades de programação" source=site.data.programming-skills %}
{% include about/skills.html title="Outras habilidades" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>