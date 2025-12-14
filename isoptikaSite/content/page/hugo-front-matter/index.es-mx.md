---
title: "Front Matter de Hugo 🦉"
description: "Hugo te permite agregar front matter en yaml, toml o json a tus archivos de contenido."
summary: "Hugo te permite agregar front matter en yaml, toml o json a tus archivos de contenido. Sigue leyendo para saber más sobre las variables de front matter predefinidas y definidas por el usuario."
draft: true
tags: ["Featured"]
images: ["hugo-front-matter.jpg","hugo-logo.svg"]
keywords: ["Front Matter de Hugo","hugo","front matter","publicación borrador","variables front matter"]
aliases:
  - draft-post
  - my-fourth-blog-post
---

# Front Matter de Hugo

Hugo te permite agregar front matter en yaml, toml o json a tus archivos de contenido.

**Front matter** te permite mantener metadatos adjuntos a una instancia de un tipo de contenido—es decir, incrustados dentro de un archivo de contenido—y es una de las muchas características que le da fuerza a Hugo.

![Banner](hugo-front-matter.jpg)
{ .img-fluid }

## Variables de Front Matter

Hay algunas [variables predefinidas](https://gohugo.io/content-management/front-matter/#predefined) que Hugo reconoce. Consulta [Variables de Página](https://gohugo.io/variables/page/) para ver cómo llamar a muchas de estas variables predefinidas en tus plantillas.

Puedes agregar campos a tu front matter arbitrariamente para satisfacer tus necesidades. Estos pares clave-valor definidos por el usuario se colocan en una única variable `.Params` para usar en tus plantillas.

Cualquier nodo o sección puede transmitir a los descendientes un conjunto de valores de Front Matter siempre que se definan debajo de la clave reservada `cascade` de Front Matter.

### Ordenar Contenido a Través de Front Matter

Puedes asignar un `weight` específico del contenido en el front matter de tu contenido. Estos valores son especialmente útiles para ordenar en vistas de lista. Puedes usar `weight` para el ordenamiento del contenido y la convención de [<TAXONOMY>_weight](https://gohugo.io/content-management/taxonomies/) para ordenar contenido dentro de una taxonomía. Consulta [Ordenar y Agrupar Listas de Hugo](https://gohugo.io/templates/lists/#order-content) para ver cómo se puede usar `weight` para organizar tu contenido en vistas de lista.

### Publicación Borrador

Si es `true`, el contenido no se renderizará a menos que se pase la bandera `--buildDrafts` al comando `hugo`.

**Nota**: Esta página tiene la variable de front matter `draft` con valor `true`, por lo que no se renderizará en producción.
