
<div align="center">
  <h1>Curso Frontend Developer</h1>
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/32/Platzi.jpg" alt="platzi logo" height="300px">
  <h3 style="font-weight:bold;" >Curso Frontend Developer(6H)</h3>
  <h5></h5>
</div>

## Requisitos :clipboard:

*   Curso de prework en; OSX (Mac), Windows o Linux.

## Comenzando 🚀

## Descripcion :notebook:

**Aprender HTML y CSS**
<p>En el curso de frontend developer se ven los inicios de html y css y los metodos de desarrollos modernos . </p>

## Listado de Temas del Curso: 💯
    *   HTML5 + CSS3 => Patrones de Diseño Responsive 
---
#### **HTML y CSS**
*   HTML es un lenguaje de marcas de hipertexto, y aquí es donde se estructura toooda la página web. 
*   CSS nos da la vida a nuestras páginas web agregando estilos a TODOS los elementos que se insertan al documento html.
---
#### Motores de Renderizado
Los 5 pasos de los motores:

* Pasa los archivos de HTML a objetos (El DOM). Esto para que el navegador pueda entenderlo.
* Calcula el estilo correspondiente a cada nodo en el DOM.
* Calcula las dimensiones de cada nodo y va a empezar a estructurar la página web.
* Pinta las diferentes cajas.
* Toma las capas y las convierte en una imagen, para finalmente mostrar esta imagen en la pantalla.

Los navegadores de renderizado son :
``` text
|------------------------|
|  Navegador | Motor     |
|------------------------|
|Chrome      | Blink     |
|Edge        | Edge html |
|Safari      | Webkit    |
|Firefox     | Gecko     |
|------------------------|
```

#### Anotacion de un Documento HTML y sus elementos
* Los docmentos HTML poseen etiquetas! y la gran mayoria de estas se cumple la siguiente estrucctura para el elemento

  * Etiqueta de apertura
  * Contenido
  * Etiqueta de cierre*

``` text
Elemento
1º etiqueta de apertura <h1>
2º contenido <h1>contenido</h1>
3º etiqueta de cierre </h1>


```

* Atributos:
```text

<h1>: Etiqueta de apertura
</h1>: Etiqueta de cierre
Platzi: Contenido
class: Atributo
"title": Valor

<h1 class="title">Platzi</h1>
```

# Anatomia de un HTML
 ```html
 <!Doctype html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<title> Proyecto 1 </title>
<link rel ="stylesheet" href="./css/estilos.css">
</head>
<body>
<header> Encabezado
<nav> Menu </nav>
</header>
<main> Contenido principal
<section> Seccion de una pagina
<article>
<ol>  //lista ordernada 
<li> Marge </li>
<li> Bart</li> 
<li> Lisa </li>
</ol>
</article>
</article>
</section>
</main>
<footer> @ByPlatzi 2021 </footer>
</body>
</html> 
 ```

#### HTML Semantico:
* HTML semántico
* Es un concepto muy importante para los nosotros como desarrolladores.

* Nos va a indicar o señalar que tenemos que usar propiedades adecuadas para los textos, párrafos, imágenes, secciones, etc.

* Tenemos que usar las diferentes etiquetas de HTML que ya existen para las diferentes cosas que queramos colocar.

* **Ventajas**:
Al hacer esto vamos a lograr tener un código accesible.
Tenemos el tema de posicionamiento SEO.
Nos permite tener un código mucho más claro, ligero y fácil de leer.
<div align="center">
<img src="https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202021-09-30%20215520-28ba8103-b824-4c8b-b00d-63e653af79ae.jpg" alt="platzi html semantico" height="300px">
</div>

* **Etiqueta div**
  Es una etiqueta comodín, nos permite hacer muchas cosas no es una buena práctica usarla en cada cosa que hagamos.

<div align="center">
<img src="https://static.platzi.com/media/user_upload/html5_sectioning_high_level-8080ec80-4567-4401-a429-7e7a0ddf26c4.jpg" alt="platzi html semantico" height="300px">
</div>

* **Estructura basica**
  * Todas los sitios web tienden a compartir componentes estándar similares.
  * webs de recursos : 
    * **[Referencia-Html]** (https://htmlreference.io)
    * **[Imagenes]** (https://pexels.com/es-es)
    * **[Imagenes]** (https://unsplash)
    * **[Imagenes]** (https://placeholder.com)
    * **[Genedador-texto]** (http://getlorem.com)
    * **[Favicon-generador]** (http://favicon-generator.org)
    * **[Iconos]** (https://fontawesome.com)
    * **[Iconos]** (https://feathericons.com)
    * **[Falsear-datos]** (https://mockaroo.com)
    * **[Ids-Generator]** (https://uuidgenerator.net)
    * **[Colores]** (https://colorhunt.co)
    * **[Colores]** (https://flatuicolors.com)
    * **[Colores]** (https://uigradients.com)
    * **[Colores]** (https://colorhailpixel.com)
    * **[Diagramas]** (https://app.diagrams.net)
    * **[Diagramas]** (https://wireframe.cc)
  
- **CABEZERA o HEADER**: **< header >**
- **NAV o NAVBAR**: **< nav >** .
- **CENTENIDO DEL CUERPO PRINCIPAL**:** < main >** , con varias subsecciones de -contenido representados por **< article >**, **< section >** y **< div >** elementos.
- **RECUADRO****:< aside> a menudo colocado en el interior **< main >**.
- **PIE DE PAGINA O FOOTER**: **< footer >**


---

#### Etiquetas HTML Basicas
* **¿Cuáles son las etiquetas HTML básicas?**
  * Hay una serie de etiquetas que son las más usadas para crear cualquier documento HTML, a continuación las explicamos:
* **Listado de Etiquetas :**
* **Etiquetas base**
  * **< !doctype >** : Indica version html
  * **< html >** : es la raiz del archivo
  * **< head >** : engloba metadatos
  * **< title >** : titulo pestaña navegador
  * **< link >** : enlazar archivos css externos no embebidos
  * **< style >** : escribir css dentro del html
  * **< script >** : enlaza o escribe scripts de js
  * **< meta >** : caracteristicas de la pagina html creada
  * **< body >** : cuerpo visible html
* **Para texto**
  * **< p >** : parrafo
  * **< span >** para estilos de una parte del texto
  * **< Hx >** : tituto o subtitulo , creado con jerearquias de importacias de 1 al 6 ejemplo.
  * **< b >** : texto negrita
  * **< i >** : texto italica
  * **< u >** : texto subrayado
  * **< a >** : agrega link a texto
  * **< strong >** : texto con importacia
  * **< blockquote >** : texto en formato cita
  * **< br >** : salto de linea o retorno de carro "enter"
* **Para multimedia**
  * **< img >** : insertat imagen
  * **< video >** : insertar video
  * **< iframe >** : insertar contenido de otro website
  * **< audio >** : insertar audio
* **Para la estructura de contenido**
  * **< ul >** : crea lista sin orden
  * **< ol >** : crea lista ordenada
  * **< li >** : defina articulos de listas
  * **< div >** : selecciona o agrupa etiquetas 
  * **< nav >** : crea el menu de navegacion
  * **< header >** : define cabecera 
  * **< footer >** : define pie de pagina
* **Para crear tablas** 
  * **< table >** : crea una tabla
  * **< tr >** : crea flas
  * **< td >** : crea columnas
  * **< th >** : crea titulo de columna
  * **< col >** : especifica las propiedades de las columnas
* **Para crear formularios**
  * **< form >** : crea un formulario
  * **< input >** : campo para introducir datos de entrada
  * **< label >** : titulo del input 
  * **< textarea >** : campo para introducir datos
  * **< button >** : boton