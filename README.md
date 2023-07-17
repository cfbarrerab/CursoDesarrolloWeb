# Desarrollo Web

Date Created: 8 de julio de 2023 13:04
Status: Doing

# Introducción a HTML y CSS

HTML Hiper Text Markup Language: Define la estructura en el contenido de la pagina web. Extensión .html

CSS: Cascading Style Sheets. Presentación de los elementos definidos en HTML. Extensión .css

JavaScript: Permite que la página diseñada en html y css sea interactiva

# Herramientas de Desarrollo de Chrome

Se puede ver la estructura de toda las páginas web al dar botón derecho y en INSPECT. Se abrirá una ventana con el código html

![Untitled](img/Untitled.png)

# Editores de Código

Visual Studio Code

Creamos una nueva carpeta de trabajo llamada Curso HTML y CSS

![Untitled](img/Untitled%201.png)

# Crear un archivo HTML

Vamos a crear el primer archivo, es un estandar que el archivo principal index.html

![Untitled](img/Untitled%202.png)

En la primera línea vamos a escribir que versión de html vamos a usar en nuestro archivo. DEBE SER LA PRIMERA LÍNEA QUE TENGAN TODOS LOS ARCHIVOS HTML

![Untitled](img/Untitled%203.png)

# Elementos y Etiquetas

Elemento: Componente básico de un archivo html. Usamos los elementos para definir la estructura de una pagina web en un archivo html

Etiquetas: Las etiquetas no permiten definir los elemntos en un archivo html. Especifivan el tipo de elemento que vamos a usar

![Untitled](img/Untitled%204.png)

![Untitled](img/Untitled%205.png)

![Untitled](img/Untitled%206.png)

![Untitled](img/Untitled%207.png)

Hay etiquetas que no requieren etiquetas de cierre como <img>, es opcional colocar el cierre.

## Nuestro primer archivo

![Untitled](img/Untitled%208.png)

<html></html> se considera el elemento raíz, ya que dentro de este elemetno de la página van todos los demás elementos

Head y Body son los segundos elemnto de importancia. 

Dentro de Head son elemntos que actúan destrás de escena

Dentro de Body van los elemntos que van a dar la estructura de la página

# Especificar Idioma

![Untitled](img/Untitled%209.png)

# Crear Encabezados

Se crean dentro de body

![Untitled](img/Untitled%2010.png)

![Untitled](img/Untitled%2011.png)

# Párrafos

<p></p> es el elemtno para crear párrafos. Si el párrafo es muy largo, con ALT+Z este se acomoda al ancho de la ventana del edito de código

![Untitled](img/Untitled%2012.png)

![Untitled](img/Untitled%2013.png)

![Untitled](img/Untitled%2014.png)

![Untitled](img/Untitled%2015.png)

![Untitled](img/Untitled%2016.png)

# Buscar en la Documentación

Buscar información de elementos en la documentación de desarrolladores de Mozilla. MDN WEB DOCS

![Untitled](img/Untitled%2017.png)

# Comentarios en HTML

Nos sirven para ubicarnos y poner texto de referencia en las lineas de código. No afecta el contenido de la página. <!— COMENTARIO—>. Para volver una línea comentario, se puede usar el atajo CTRL+/ 

![Untitled](img/Untitled%2018.png)

# Elemento main

El **elemento HTML `<main>`** representa el contenido principal del `[<body>](https://developer.mozilla.org/es/docs/Web/HTML/Element/body)` de un documento o aplicación. El área principal del contenido consiste en el contenido que está directamente relacionado, o se expande sobre el tema central de un documento o la funcionalidad central de una aplicación. Este contenido debe ser único al documento, excluyendo cualquier contenido que se repita a través de un conjunto de documentos como barras laterales, enlaces de navegación, información de derechos de autor, logos del sitio y formularios de búsqueda (a menos, claro, que la función principal del documento sea un formulario de búsqueda).

**Nota:** **no debe haber** más de un elemento `<main>` en un documento, y este **no debe ser** descendiente de un elemento `[<article>](https://developer.mozilla.org/es/docs/Web/HTML/Element/article)`, `[<aside>](https://developer.mozilla.org/es/docs/Web/HTML/Element/aside)`, `[<footer>](https://developer.mozilla.org/es/docs/Web/HTML/Element/footer)`, `[<header>](https://developer.mozilla.org/es/docs/Web/HTML/Element/header)`, o `[<nav>](https://developer.mozilla.org/es/docs/Web/HTML/Element/nav)`.

![Untitled](img/Untitled%2019.png)

# Indentación

Se trata de jerarquizar los anidados de los códigos mediante espacios o tabulaciones. Se recomienda no mezclar espacios y tabulaciones

![Untitled](img/Untitled%2020.png)

# Imágenes y Atributos

Se usa la etiqueta <img>, no necesita etiqueta de cierre

![Untitled](img/Untitled%2021.png)

en src se coloca la fuente de origen de la imagen, para este caso es una pagina web

![Untitled](img/Untitled%2022.png)

atributo alt: da una descripción a la imagen por si hay una problema al cargar la página web

![Untitled](img/Untitled%2023.png)

También se puede halar una imagen que este en una carpe. Se recomienda usar una carpeta que se llame img y alojar las imagenes allí. En src se coloca la ubicación de la imagen

![Untitled](img/Untitled%2024.png)

![Untitled](img/Untitled%2025.png)

# Crear Enlaces Externos

Para crear enlaces externos de un texto, es decir qwue una frase o palabra sea un enlace a otra página usamos en elemento <a></a>. Usamos tambien href en e el elemnto para inficar la url de la página de referencia

![Untitled](img/Untitled%2026.png)

![Untitled](img/Untitled%2027.png)

Si ingresamos al enlace, lo hace en la misma pestaña, por los que si se desea que el enlace sea en otra pestaña se agrega el atributo target=_blank

![Untitled](img/Untitled%2028.png)

adicional por seguridad se coloca el atributo rel=”noopener noreferrer” nos permite evitar TABNABBING (es un término informático para definir un tipo de phishing (delito donde por medio de ingeniería social se obtiene datos de forma fraudulenta) descrito en 2010 por Aza Raskin[1](https://es.wikipedia.org/wiki/Tabnabbing#cite_note-1)[2](https://es.wikipedia.org/wiki/Tabnabbing#cite_note-2) y que se basa en persuadir al usuario de insertar datos para entrar en cuentas, normalmente de correos o redes sociales, por medio de páginas que aparentan ser las reales. Este método es muy peligroso porque se basa en la poca atención que un usuario puede tener mientras navega en múltiples pestañas y la falta de hábito de no revisar el [código fuente](https://es.wikipedia.org/wiki/C%C3%B3digo_fuente) al entrar en una página.)

![Untitled](img/Untitled%2029.png)

# Enlaces a secciones internas

Para la creación de enlaces internos vamos a crear 4 enlaces con el nombre de los títulos de los párrafos. A cada párrafo, con su título, lo vamos a identificar de la siguiente manera. Y luego enlazamos los enlaces creados al nombre del párrafo

![Untitled](img/Untitled%2030.png)

![Untitled](img/Untitled%2031.png)

# Enlaces con imágenes

Para crear enlaces con imágenes, anidamos la imagen creada con <a></a> y lo ponemos en href el enlace destino con target blank y las medidas de seguridad

![Untitled](img/Untitled%2032.png)

 

# Crear enlaces con #

Se usan como enlaces muertos. Son usados cuando aun no se tiene certeza a donde colocar el destino del href en el proceso de construcción de una pa´gina web

![Untitled](img/Untitled%2033.png)

# Listas no ordenadas

Son Listas con Viñetas. Se hacen con los siguientes elementos

![Untitled](img/Untitled%2034.png)

# Listas ordenadas

Listas numeradas

![Untitled](img/Untitled%2035.png)

# Etiqueta strong

Texto en negrita

![Untitled](img/Untitled%2036.png)

# Text en cursiva

![Untitled](img/Untitled%2037.png)

# Texto Tachado

![Untitled](img/Untitled%2038.png)

# Línea Horizontal

![Untitled](img/Untitled%2039.png)

![Untitled](img/Untitled%2040.png)

# Crear formularios

Se crea para que los usurios ingresen información.

![Untitled](img/Untitled%2041.png)

![Untitled](img/Untitled%2042.png)

/enviar-respuesta es el archivo destino a donde se enviará lo escrito por el usuario

# Texto Marcador de Posición

Para agregar texto de sugerencia de respuesta al usuario. Cuando el usuario empieza a escribir, el texto desaparece

![Untitled](img/Untitled%2043.png)

![Untitled](img/Untitled%2044.png)

# Crear un campo obligatorio

Se agrega “required”

![Untitled](img/Untitled%2045.png)

# Botones de Radio

Son aquellos botones de selección múltiple. Van dentro del form y es de tipo radio. 

![Untitled](img/Untitled%2046.png)

![Untitled](img/Untitled%2047.png)

Label sirve para que al hacer click al texto tambien marque la opción, y bautizamos las respuestas como interior y exterior con un id de input

# Grupo de Botones de Radio

Para que se pueda escoger una sola respuesta en los botones de radio, se agrega el atributo name al input. Todo el conjunto de respuestas que se deseen que se escoja entre ellas, deben estar agrupados con el mismo nombre. Para esta caso, lo llamamos “interior-exterior”

![Untitled](img/Untitled%2048.png)

# Salto de Línea

Para agregar un salto de línea entre los elemntos, se agraga el elemtno br

![Untitled](img/Untitled%2049.png)

![Untitled](img/Untitled%2050.png)

# Casillas de Verificación

![Untitled](img/Untitled%2051.png)

![Untitled](img/Untitled%2052.png)

# El atributo 'checked’

Nos marca las opciones que queremos que se marquen por defecto

![Untitled](img/Untitled%2053.png)

![Untitled](img/Untitled%2054.png)

# El atributo 'value’

Este es el valos que cada respuesta que el usuario ingrese el sistema va a tomar. Es decir, si se escoge EXTERIOR sin valo. No tendremos un valor ingresado, en cambio si le damos value=”exterior” el valor ingresado por el usuario sera exterior

![Untitled](img/Untitled%2055.png)

# Elementos div

Es un contenedor para cualquier proposito.

 

![Untitled](img/Untitled%2056.png)

# Pie de Página

Información de pie de página. Se pueden poner enlaces y se puede achical la letra con el elemento small

![Untitled](img/Untitled%2057.png)

# Head

En el head se van a colocar todos los elementos que funcionan tras bambalinas en la pagina, mas especificamente CSS. También con title podemos ponerle título de la pestaña del navegador

#