---
layout: default
title: Proyectos
---

## Algunos de mis proyectos destacados

### 🐶 PetLove App
App de citas para mascotas usando Flutter + Node.js.

### 🧩 API Usuarios
Backend con Express + SQL Server, autenticación JWT.

---

## Proyectos recientes en GitHub

<ul>
  {% assign repos = site.github.public_repositories | sort: "pushed_at" | reverse %}
  {% for repo in repos limit:5 %}
    <li>
      <strong><a href="{{ repo.html_url }}" target="_blank">{{ repo.name }}</a></strong>: {{ repo.description }}
    </li>
  {% endfor %}
</ul>
