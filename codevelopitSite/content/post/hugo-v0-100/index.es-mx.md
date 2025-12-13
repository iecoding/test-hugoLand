---
title: "Hugo v0.100.2"
description: ""
date: 2022-06-08
draft: false
images: ["hugo-logo.png"]
categories: ["Notas de Versión de Hugo"]
tags: ["Hugo"]
keywords: ["hugo v0.100"]
authors: ["Bjørn Erik Pedersen"]
---

![Hugo](hugo-logo.svg)
{ .img-fluid .mb-5 }

Esta versión está motivada principalmente por la corrección del pánico experimentado por personas que tenían blackfriday configurado como defaultMarkdownHandler ([#9968](https://github.com/gohugoio/hugo/issues/9968)). El soporte de Blackfriday fue eliminado en Hugo v0.100.0 después de haber sido deprecado con una advertencia durante mucho tiempo.

v0.100.1 corrige el pánico con markdownify/RenderString con shortcode en Page sin archivo de contenido.

$page.RenderString (ver [#6703](https://github.com/gohugoio/hugo/issues/6703)) finalmente soporta shortcodes, y las mejoras de shortcode son el tema principal en Hugo 0.100.0.


[Notas de Versión en GitHub](https://github.com/gohugoio/hugo/releases).
