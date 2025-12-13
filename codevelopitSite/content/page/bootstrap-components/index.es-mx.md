---
title: "Componentes de Bootstrap ✨"
description: "Bootstrap incluye decenas de componentes que pueden reutilizarse para proporcionar una buena experiencia de usuario e interacciones en una página web."
draft: false
tags: ["Featured"]
images: ["bootstrap-v5-new-logo.png","hugo-bootstrap-banner.png"]
keywords: ["componentes bootstrap","bootstrap","tema hugo bootstrap"]
---

# Componentes de Bootstrap

Bootstrap incluye decenas de componentes que pueden reutilizarse para proporcionar una buena experiencia de usuario e interacciones en una página web.

---

## Acordeón

<br>

<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
        Elemento del Acordeón #1
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>Este es el cuerpo del primer elemento del acordeón.</strong> Se muestra por defecto, hasta que el plugin de colapso agrega las clases apropiadas que usamos para dar estilo a cada elemento. Estas clases controlan la apariencia general, así como el mostrar y ocultar mediante transiciones CSS. Puedes modificar cualquiera de esto con CSS personalizado o sobrescribiendo nuestras variables predeterminadas. También vale la pena señalar que casi cualquier HTML puede ir dentro de <code>.accordion-body</code>, aunque la transición limita el desbordamiento.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingTwo">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
        Elemento del Acordeón #2
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>Este es el cuerpo del segundo elemento del acordeón.</strong> Está oculto por defecto, hasta que el plugin de colapso agrega las clases apropiadas que usamos para dar estilo a cada elemento. Estas clases controlan la apariencia general, así como el mostrar y ocultar mediante transiciones CSS. Puedes modificar cualquiera de esto con CSS personalizado o sobrescribiendo nuestras variables predeterminadas. También vale la pena señalar que casi cualquier HTML puede ir dentro de <code>.accordion-body</code>, aunque la transición limita el desbordamiento.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingThree">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
        Elemento del Acordeón #3
      </button>
    </h2>
    <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>Este es el cuerpo del tercer elemento del acordeón.</strong> Está oculto por defecto, hasta que el plugin de colapso agrega las clases apropiadas que usamos para dar estilo a cada elemento. Estas clases controlan la apariencia general, así como el mostrar y ocultar mediante transiciones CSS. Puedes modificar cualquiera de esto con CSS personalizado o sobrescribiendo nuestras variables predeterminadas. También vale la pena señalar que casi cualquier HTML puede ir dentro de <code>.accordion-body</code>, aunque la transición limita el desbordamiento.
      </div>
    </div>
  </div>
</div>

<br>

Consulta la [documentación del Acordeón](https://getbootstrap.com/docs/5.3/components/accordion/).

---

## Alerta

<br>

<div class="alert alert-primary" role="alert">
  ¡Una simple alerta primaria—échale un vistazo!
</div>
<div class="alert alert-secondary" role="alert">
  ¡Una simple alerta secundaria—échale un vistazo!
</div>
<div class="alert alert-success" role="alert">
  ¡Una simple alerta de éxito—échale un vistazo!
</div>
<div class="alert alert-danger" role="alert">
  ¡Una simple alerta de peligro—échale un vistazo!
</div>
<div class="alert alert-warning" role="alert">
  ¡Una simple alerta de advertencia—échale un vistazo!
</div>
<div class="alert alert-info" role="alert">
  ¡Una simple alerta informativa—échale un vistazo!
</div>
<div class="alert alert-light" role="alert">
  ¡Una simple alerta clara—échale un vistazo!
</div>
<div class="alert alert-dark" role="alert">
  ¡Una simple alerta oscura—échale un vistazo!
</div>

<br>

Consulta la [documentación de Alertas](https://getbootstrap.com/docs/5.3/components/alerts/).

---

## Insignia

<br>

<p>Texto con insignia <span class="badge bg-primary">Nuevo</span></p>

<br>

<button type="button" class="btn btn-primary">
  Botón <span class="badge text-bg-secondary">4</span>
</button>

<br>
<br>

<button type="button" class="btn btn-primary position-relative">
  Posicionado
  <span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger">
    99+
    <span class="visually-hidden">mensajes no leídos</span>
  </span>
</button>

<br>
<br>

<button type="button" class="btn btn-primary position-relative">
  Perfil
  <span class="position-absolute top-0 start-100 translate-middle p-2 bg-danger border border-light rounded-circle">
    <span class="visually-hidden">Nuevas alertas</span>
  </span>
</button>

<br>
<br>

<span class="badge rounded-pill text-bg-success">Píldora redondeada</span>

<br>

Consulta la [documentación de Insignias](https://getbootstrap.com/docs/5.3/components/badge/).

---

## Botón

<br>

<button type="button" class="btn btn-primary">Primario</button>
<button type="button" class="btn btn-secondary">Secundario</button>
<button type="button" class="btn btn-success">Éxito</button>
<button type="button" class="btn btn-danger">Peligro</button>
<button type="button" class="btn btn-warning">Advertencia</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-light">Claro</button>
<button type="button" class="btn btn-dark">Oscuro</button>

<button type="button" class="btn btn-link">Enlace</button>

<br>

Consulta la [documentación de Botones](https://getbootstrap.com/docs/5.3/components/buttons/).

---

## Tarjeta

<br>

<div class="card w-50">
  <img src="picsum-photo-300x200.jpg" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Título de la tarjeta</h5>
    <p class="card-text">Algún texto de ejemplo rápido para construir sobre el título de la tarjeta y formar la mayor parte del contenido de la tarjeta.</p>
    <a href="#card" class="btn btn-primary">Ir a algún lugar</a>
  </div>
</div>

<br>

Consulta la [documentación de Tarjetas](https://getbootstrap.com/docs/5.3/components/card/).

---

## Grupo de lista

<br>

<ul class="list-group">
  <li class="list-group-item">Un elemento</li>
  <li class="list-group-item">Un segundo elemento</li>
  <li class="list-group-item">Un tercer elemento</li>
  <li class="list-group-item">Un cuarto elemento</li>
  <li class="list-group-item">Y un quinto</li>
</ul>

<br>

Consulta la [documentación de Grupos de lista](https://getbootstrap.com/docs/5.3/components/list-group/).

---

### Crear los tuyos propios

Lee la [página de personalización de componentes](https://getbootstrap.com/docs/5.3/customize/components/) para aprender cómo construir tus propios componentes.

---

## Llamada de atención

<br>

<div class="callout">
    <strong>Esta es una llamada de atención.</strong> La construimos personalizada para nuestra documentación para que nuestros mensajes destaquen. Tiene tres variantes mediante clases modificadoras.
</div>

<div class="callout callout-info">
    <strong>Esta es una llamada de atención informativa.</strong> Texto de ejemplo para mostrarla en acción.
</div>

<div class="callout callout-warning">
    <strong>Esta es una llamada de atención de advertencia.</strong> Texto de ejemplo para mostrarla en acción.
</div>

<div class="callout callout-danger">
    <strong>Esta es una llamada de atención de peligro.</strong> Texto de ejemplo para mostrarla en acción.
</div>

<br>

---

## Información sobre herramientas

<br>

<div class="tooltip">
  <p class="">
  Texto de marcador de posición para demostrar algunos <a href="#" data-bs-toggle="tooltip" data-bs-title="Información sobre herramientas predeterminada">enlaces en línea</a> con información sobre herramientas. Esto ahora es solo relleno, sin contenido real. Contenido colocado aquí solo para imitar la presencia de <a href="#" data-bs-toggle="tooltip" data-bs-title="Otra información sobre herramientas">texto real</a>. Y todo eso solo para darte una idea de cómo se verían las información sobre herramientas cuando se usan en situaciones del mundo real. Así que esperamos que ahora hayas visto cómo <a href="#" data-bs-toggle="tooltip" data-bs-title="Otra más aquí también">estas información sobre herramientas en enlaces</a> pueden funcionar en la práctica, una vez que las uses en <a href="#" data-bs-toggle="tooltip" data-placement="bottom" data-bs-title="¡El último consejo!">tu propio</a> sitio o proyecto.
  </p>
</div>

<br>
