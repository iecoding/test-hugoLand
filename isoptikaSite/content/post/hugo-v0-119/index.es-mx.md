---
title: "Hugo v0.119.0"
description: ""
date: 2023-09-24
draft: false
images: ["hugo-logo.png"]
categories: ["Notas de Versión de Hugo"]
tags: ["Hugo"]
keywords: ["hugo v0.119"]
authors: ["Bjørn Erik Pedersen"]
---

![Hugo](hugo-logo.svg)
{ .img-fluid .mb-5}

Esta versión está construida con Go 1.21.1 que contiene algunas correcciones de seguridad relevantes para el paquete html/template, consulta [Issue 62196](https://github.com/golang/go/issues/62196) y [Issue 62197](https://github.com/golang/go/issues/62197). Esta es la razón principal por la que Hugo 0.119.0 se lanza antes que después. Pero esta versión también viene con una actualización de dependencias y algunas mejoras útiles en el procesamiento de imágenes:

Un nuevo método y filtro de propósito general [Process](https://gohugo.io/content-management/image-processing/#process).
Un nuevo filtro [Opacity](https://gohugo.io/functions/images/#opacity).


[Notas de Versión en GitHub](https://github.com/gohugoio/hugo/releases).
