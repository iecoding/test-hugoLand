---
title: "Guía Rápida de Markdown Ⓜ️⬇️"
description: "Una descripción general de la sintaxis básica de markdown."
draft: false
tags: ["Featured"]
images: ["markdown-guide-og.jpg"]
keywords: ["guía rápida markdown","markdown","guía rápida", "guía rápida markdown hugo", "goldmark"]
aliases:
  - blog/my-third-blog-post
---

# Guía Rápida de Markdown

Hugo tiene excelente soporte para Markdown listo para usar. Por defecto, Hugo usa el [procesador Markdown Goldmark](https://github.com/yuin/goldmark/) que es totalmente compatible con CommonMark. Consulta las [instrucciones de configuración](https://gohugo.io/getting-started/configuration-markup/) para aprender más sobre las extensiones que puedes configurar.

## Descripción General

Puedes consultar la tabla a continuación para obtener una descripción general de la sintaxis básica de markdown:

| TAREA           | SINTAXIS DE MARKDOWN                  |
| -------------- | -------------------------------- |
| Encabezado 1      | `#`                              |
| Encabezado 2      | `##`                             |
| Encabezado 3      | `###`                            |
| Cursiva        | `*cursiva*`                      |
| Negrita           | `**Negrita**`                       |
| Tachado         | `~~tachado~~`                     |
| Cita     | `>`                              |
| Enlaces          | `[nombre del enlace](https://enlace.com)`  |
| Imágenes         | `![Nombre de imagen](imagen.png)`       |
| Lista desordenada | `* Elemento de lista`                    |
| Lista ordenada   | `1. Elemento de lista`                   |
| Código en línea    | <code>\`inserta código aquí\`<code> |
{.table .table-sm .table-striped .table-hover}

---

## Encabezados

```markdown
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
```

# Encabezado 1

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

---

## Listas

```markdown
* Elemento desordenado
* Elemento desordenado
* Elemento desordenado

1. Elemento ordenado
2. Elemento ordenado
3. Elemento ordenado

- [ ] Elemento de tarea
- [x] Elemento de tarea marcado
- [ ] Elemento de tarea
```

* Elemento desordenado
* Elemento desordenado
* Elemento desordenado

1. Elemento ordenado
2. Elemento ordenado
3. Elemento ordenado

- [ ] Elemento de tarea
- [x] Elemento de tarea marcado
- [ ] Elemento de tarea

---

## Formato

```markdown
**Negrita**

*Cursiva*

<u>Subrayado</u>

<sup>Superíndice</sup>

<sub>Subíndice</sub>

<mark>Resaltado</mark>

`Código en línea`

~~Tachado~~

[Hipervínculo](http://ejemplo.com)

![Imagen](placeholder-50-09f-fff.png)
{ .img-fluid }
```

**Negrita**

*Cursiva*

<u>Subrayado</u>

<sup>Superíndice</sup>

<sub>Subíndice</sub>

<mark>Resaltado</mark>

`Código en línea`

~~Tachado~~

[Hipervínculo](http://ejemplo.com)

![Imagen](placeholder-50-09f-fff.png)
{ .img-fluid }

---

## Tabla

```markdown
| Encabezado 1 | Encabezado 2 |
| -------- | -------- |
| Celda 1   | Celda 2   |
| Celda 3   | Celda 4   |
```

| Encabezado 1 | Encabezado 2 |
| -------- | -------- |
| Celda 1   | Celda 2   |
| Celda 3   | Celda 4   |

---

## Cita

```markdown
> Cita  
> Segunda línea
> 
>  -- Autor
```

> Cita  
> Segunda línea
> 
>  -- Autor

---

## Bloque de código

`````
```go
package main

import "fmt"

func main() {
    fmt.Println("hola mundo")
}
```
`````

```go
package main

import "fmt"

func main() {
    fmt.Println("hola mundo")
}
```

---

## HTML

```markdown
<div>
    <p>Hola mundo</p>
</div>
```

<div>
    <p>Hola mundo</p>
</div>

---

## Ver también

- [Referencia de Markdown de Hugo](https://www.markdownguide.org/tools/hugo/)
- [Tipografía de Bootstrap](https://getbootstrap.com/docs/5.3/content/typography/)
