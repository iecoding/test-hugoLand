---
title: "Mejores Prácticas de Seguridad 🔒"
description: "Mejora la salud del código de tu página web siguiendo estas mejores prácticas. Previene vulnerabilidades de seguridad"
draft: false
tags: ["Featured"]
keywords: ["mejores prácticas de seguridad","enlaces externos","no usa https","los enlaces a destinos de origen cruzado no son seguros","incluye bibliotecas JavaScript de front-end con vulnerabilidades de seguridad conocidas","asegurar que CSP sea efectivo contra ataques XSS","Política de Seguridad de Contenido","csp"]
---

# Mejores Prácticas de Seguridad

Mejora la salud del código de tu página web siguiendo estas mejores prácticas.

## Usar HTTPS

Todos los sitios web deben estar protegidos con HTTPS, incluso aquellos que no manejan datos sensibles. HTTPS previene que los intrusos manipulen o escuchen pasivamente las comunicaciones entre tu sitio y tus usuarios.

## Enlaces Externos

Cuando enlazas a una página en otro sitio usando el atributo `target="_blank"`, puedes exponer tu sitio a problemas de rendimiento y seguridad:

- La otra página puede ejecutarse en el mismo proceso que tu página. Si la otra página está ejecutando mucho JavaScript, el rendimiento de tu página puede verse afectado.

- La otra página puede acceder a tu objeto window con la propiedad `window.opener`. Esto puede permitir que la otra página redirija tu página a una URL maliciosa.

Agregar `rel="noopener"` o `rel="noreferrer"` a tus enlaces `target="_blank"` evita estos problemas.

---

Todos los enlaces externos tendrán los atributos `target="_blank"` y `rel="noopener nofollow"`.

- [Salvus.Site](https://salvus.site)

- [Render-link.html ayuda necesaria](https://discourse.gohugo.io/t/render-link-html-help-need/30006/3)

Enlace interno:

- [Blog](/blog/)

## Verifica tus bibliotecas JavaScript en busca de vulnerabilidades de seguridad

Los intrusos tienen rastreadores web automatizados que pueden escanear tu sitio en busca de vulnerabilidades de seguridad conocidas. Cuando el rastreador web detecta una vulnerabilidad, alerta al intruso. Desde ahí, el intruso solo necesita averiguar cómo explotar la vulnerabilidad en tu sitio.

Para detectar bibliotecas vulnerables, consulta la [Base de Datos de Vulnerabilidades de Snyk](https://snyk.io/vuln?packageManager=all).

## Configurar Política de Seguridad de Contenido (CSP)

Una Política de Seguridad de Contenido (CSP) ayuda a asegurar que cualquier contenido cargado en la página sea confiable por el propietario del sitio. Las CSP mitigan los ataques de cross-site scripting (XSS) porque pueden bloquear scripts inseguros inyectados por atacantes. Sin embargo, la CSP puede ser fácilmente evitada si no es lo suficientemente estricta.
