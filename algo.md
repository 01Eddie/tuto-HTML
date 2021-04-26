# HTML - HyperText Markup Language

Esto es un markup language, lo que significa que está escrito con códigos que puede leer una persona sin que sea necesario compilarlo primero. En otras palabras, el texto en una página web está «marcado» con estos códigos para dar instrucciones al navegador web sobre cómo mostrar el texto. Estas etiquetas de marcado son las propias etiquetas HTML.

# The Basics o Generals

## !DOCTYPE

El primer elemento a aparecer en el código fuente de una página web es el tipo de documento de declaración. Esto proporciona al navegador web (u otro agente de usuario) información sobre el tipo de lenguaje de marcado en el que está escrita la página, lo que puede afectar o no la forma en que el navegador muestra el contenido. Esto se ve asi.

```html
<!DOCTYPE html>
```

## HTML

Inmediatamente después del tipo de documento aparece el elemento: este es el elemento raíz del árbol del documento y todo lo que sigue es un descendiente de ese elemento raíz html.

```html
<html>
</html>
```

Este sera el elemento que divide el documento en dos secciones principales: el head y el body

```html
<html>
<head>
...
</head>
<body>
...
</body>
</html>
```

# Cabeceras — HEAD

Aqui se encontraran los metadatos que contienen información sobre la página. Esto incluye información sobre los estilos, scripts y datos para ayudar al software que pueden ser:

Motores de búsqueda , navegadores , etc. que se utiliza y representa la página. Los metadatos para los estilos y scripts se pueden definir en la página o enlazar a otro archivo que tenga la información.

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
```

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%205bd8ea14e4fc4dc1a41259a5ded5b9af.csv)

# Cuerpo — Body

Aquí es donde se encuentra la mayor parte de la página. Todo lo que puede ver en la ventana del navegador (o ventana gráfica) está contenido dentro de este elemento, incluidos párrafos, listas, enlaces, imágenes, tablas y más.El aspecto de la página dependerá completamente del contenido con el que decida llenarla. Cabe resaltar que solo incluye atributos globales.

```html
<body>
    ...
</body>
```

## Seccion de contenido

Este permiten organizar el contenido del documento en partes lógicas. Utilice los elementos de sección para crear un esquema amplio para el contenido de su página, incluida la navegación de encabezado y pie de página, y elementos de encabezado para identificar secciones de contenido.

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%202c5cdfb635644abdade566bc510e708e.csv)

## Contenido del texto

Son importantes para la accesibilidad y el SEO ya que estos elementos identifican el propósito y/o la estructura de ese contenido.

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%20a240a001b03e4b9e9fec6f065b783232.csv)

## Semántica de texto en línea

Esta sive para definir el significado.

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%20bf8e4fbba9f54983beb3f58a6b28efeb.csv)

## Imagen y multimedia

Este permite agregar recursos multimedia como imagenes, video y/o audio

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%205085412a93da435fa4764ba76de9e9d6.csv)

## Contenido incrustado

[E](https://www.notion.so/notion/Notion-editor-101-create-and-edit-68c7c67047494fdb87d50185429df93e)ste bloque sirve para que nosotros podamos incluir una variedad de otro contenido.

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%209b16a4d037e745239bb4928daa9d7900.csv)

## SVG y MathML

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%2025c4e64a654946b59cdfd29eeba26e0c.csv)

## Scripting

Este sirve para crear contenido dinamico, es decir, hacer aplicaciones web, ya que HTML admite el use de lenguajes de secuencias de comandos, originados principalmente de Js.

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%20bba6826a7d5c44d0880a7c362c80f036.csv)

## Demarcar ediciones

Estos elementos sirven para proporcionar indicaciones de que se han modificado partes especificas del texto.

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%207c5aec3b865a4e8d8d1a78157ca9c7bd.csv)

## Contenido de la tabla

Estas se utilizan para crear y manejar datos tabulares.

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%20173db4a3764140898899245dea969898.csv)

## Formularios

Estas se pueden usar juntos para crear formularios que el usuario puede completar y enviar al sitio web o la aplicación.

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%20dae484d5160b4230b5ad8a2d37d39689.csv)

## Elementos interactivos

Este sirve para crear objetos de interfaz de usuarios interactivos.

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%202d5dc5d55a1f45308889744c9c00aaa5.csv)

## Componentes Web

Esta es una tecnología relacionada con HTML que permite, esencialmente, crear y utilizar elementos personalizados como si fuera HTML normal. Además, puede crear versiones personalizadas de elementos HTML estándar.

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%208ce4447c296445ac9218396de7d8cf30.csv)

[Untitled](HTML%20-%20HyperText%20Markup%20Language%202d041a63b79f41c8b2a9519918390171/Untitled%20Database%20e7678d6cf3fb4e069ed18a26155ae57e.csv)