# Prueba desarrollo web - CV

Generar un sitio web personal utilizando un CMS como Wordpress o Django, cuyo contenido principal sea una publicación que muestre el currículum vitae del propietario del sitio.

## Datos

Los datos del currículum deberán ser ingresados a través de un post, haciendo uso de las taxonomies y fields necesarios para conformar correctamente el post.

## Frontend

Para desarrollar el frontend del sitio se podrá elegir entre dos alternativas:

#### Caso 1: Generar el frontend directamente con Wordpress o Django.

Se podrá iniciar un tema desde cero, o bien, utilizar un tema predefinido de libre elección. Sin embargo, en caso de seleccionar un tema ya establecido, se deberán cambiar al menos los siguientes aspectos de la plantilla original:

- Tipo de fuente (utilizar variables globales de CSS)
- Paleta de colores (que combinen botones, links, backgrounds, etc.)
- Imágenes
- Apariencia de los botones, menús e íconos (al menos en forma y color)

*Plus: preferir el uso de SASS como preprocesador de CSS, así como el uso de variables para colores y tipografías*

#### Caso 2: Generar el frontend con algún framework de JavaScript como Angular, React o Vue.

Generar todo el maquetado y funcionalidad frontend fuera del CMS con algún framework JS, posteriormente, realizar peticiones a la REST API de Wordpress (<https://developer.wordpress.org/rest-api/>) o a la de Django.

## UX

Integrar diseño responsivo con Bootstrap o Materialize

## Entrega

1. Comentar y explicar el código
2. Justificar el uso de las fields y taxonomies utilizadas
3. Compartir el repositorio de git en el que esté el código
4. Si es posible, subir el proyecto usando un PaaS como Heroku u OpenShift. (opcional)

## Mockup

Ejemplos de temas predefinidos para Wordpress: <https://www.hosteurope.es/blog/10-plantillas-gratis-para-un-curriculum-en-wordpress>