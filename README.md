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

# CSS

En HTML se define la estructura de la página, y con CSS se define el estilo

# 3 Opciones para CSS

Estilos de Línea: El estilo se añade directamente a la etiqueta de apertura en el HTML

Elemeto Style: Se añade el estilo en el head del HTML

Archivo CSS: Se crea un archivo css con el estilo de la pagina

# Estilos de Línea

Se va al archivo html, y se selecciona el elemento a dar estilo

![Untitled](img/Untitled%2058.png)

![Untitled](img/Untitled%2059.png)

# Elemento STYLE

Se añade el estilo a todos lo elemento de tipo h2 en este caso

![Untitled](img/Untitled%2060.png)

# Archivo CSS

Se crea un archivo tipo .css con el nombre styel. Dentro de este, se establecen los estilos para el documento.

![Untitled](img/Untitled%2061.png)

Y ya dentro del README, en el head se llama al archivo style con el elemento <link>, llamando al archivo style.css y dandole altributo rel (relationship) como stylesheet

![Untitled](img/Untitled%2062.png)

# Selectores CSS

Los selectores definen sobre qué elemento se aplicará un conjunto de reglas CSS

# Selectores de Clase

Selecciona todos los elementos que tienen el atributo class especificado

Se define sobre el elemento, qué tipo de clase es

![Untitled](img/Untitled%2063.png)

![Untitled](img/Untitled%2064.png)

Luego, en el archivo style.css se definen las características de la clase. Siempre se debe iniciar con un punto. Así se puede asignar esa clase a cualquier elemento

![Untitled](img/Untitled%2065.png)

# Tamaño de fuente

Para el cambio del tamaño de fuente, se usa en font-size y se define el tamaño de la letra, puede ser en pixeles

![Untitled](img/Untitled%2066.png)

Si se desea aplicar un mismo tamaño de fuente a varios elementos, se puede colocar de la siguiente manera

![Untitled](img/Untitled%2067.png)

Para agregar mas de una caracteristica de estylo, se puede hacer así. No olvidar el punto y coma al final

![Untitled](img/Untitled%2068.png)

# Familias Tipográficas

Define una familia de fuentes. Si van separados por comas, es porque hay fuentes de respaldo. Caso de que si no funciona una, esta el siguiente como valor de respaldo

![Untitled](img/Untitled%2069.png)

Se pueden agregar fuentes espaciales usando goolgle fonts. Se ingresa a la página y se escoge el tipo de fuente. Se  copia y se pega el texto en el head de el html

![Untitled](img/Untitled%2070.png)

![Untitled](img/Untitled%2071.png)

Luego en el CSS se pega el texto que muestra la página

![Untitled](img/Untitled%2072.png)

![Untitled](img/Untitled%2073.png)

Podemos descargar varias fuentes, colocarlas en el head y usarlas a los largo de la pagina segun queramos

# Cambiar el tamaño de las imágenes

Podemos etsablecer el tamañano de todas las imágenes con el elemento with en css.

![Untitled](img/Untitled%2074.png)

Para ajustar imágenes por separado, se recomienda hacerlo por clases

![Untitled](img/Untitled%2075.png)

Se le coloca como atributo a la imagen la clase deseada. Y en el archivo style se definen las clases

![Untitled](img/Untitled%2076.png)

# Añadir bordes alrededor de un elemento

![Untitled](img/Untitled%2077.png)

Hay varias combinaciones de tipos de bordes 

![Untitled](img/Untitled%2078.png)

![Untitled](img/Untitled%2079.png)

# Esquinas redondeadas

![Untitled](img/Untitled%2080.png)

se puede definir el radio de redondero o un porcentaje. Para imágenes cuadradas poner 50% hace que queden redondas y rectangulares ovoides

# Color de Fondo de un <div>

Podemos ponerle estilo a todos los div asi

![Untitled](img/Untitled%2081.png)

o darle una clase al div y definir esa clase

![Untitled](img/Untitled%2082.png)

![Untitled](img/Untitled%2083.png)

# Atributo ID

Se le puede dar un id a un elemento y con este, en el archivo css darle características.

![Untitled](img/Untitled%2084.png)

![Untitled](img/Untitled%2085.png)

# Padding

Es la distancia entre el borde de un elmento html y su contenido. El Padding es el margen entre el espacio del div y lo que contiene

![Untitled](img/Untitled%2086.png)

![Untitled](img/Untitled%2087.png)

![Untitled](img/Untitled%2088.png)

Padding 0px

![Untitled](img/Untitled%2089.png)

Padding 20px

![Untitled](img/Untitled%2090.png)

# Padding a cada lado

![Untitled](img/Untitled%2091.png)

![Untitled](img/Untitled%2092.png)

# Padding en una sola línea

Se puede establecer un padding en una línea especificando su grosor empezando por arriba y en sentido horario

![Untitled](img/Untitled%2093.png)

# Margen

![Untitled](img/Untitled%2086.png)

![Untitled](img/Untitled%2094.png)

# Ajustar el Margen

![Untitled](img/Untitled%2095.png)

Margen en una sola linea

# Margen en una sola línea

![Untitled](img/Untitled%2096.png)

# Padding vs. Margin

![Untitled](img/Untitled%2097.png)

![Untitled](img/Untitled%2098.png)

![Untitled](img/Untitled%2099.png)

# Selectores de Atributos

En esta sección podemos definir un elemento que tenga un valor determinado y darle un atributo, Por ejemplo, todas la imágenes que tengan alt les vamos a dar radio del 50%

![Untitled](img/Untitled%20100.png)

Para seleccionar los elemntos input con valor radio

![Untitled](img/Untitled%20101.png)

![Untitled](img/Untitled%20102.png)

Para los elemntos de verificacion

![Untitled](img/Untitled%20103.png)

Para elementos que lleven a un mismo enlace, le cambiamos el color de la letra, quitamos el subtitulado y le pusimos negrilla

![Untitled](img/Untitled%20104.png)

![Untitled](img/Untitled%20105.png)

![Untitled](img/Untitled%20106.png)

# Unidades Absolutas y Relativas

Todas las unidades siguientes son unidades de longitud **absoluta**: no son relativas a nada más y en general se considera que siempre tienen el mismo tamaño.

![Untitled](img/Untitled%20107.png)

La mayoría de estos valores son más útiles cuando se usan en una salida en formato impreso que en la salida de pantalla. Por ejemplo, normalmente no usamos `cm` (centímetros) en pantalla. El único valor que usarás de forma frecuente es `px` (píxeles).

### Unidades de longitud relativa

Las unidades de longitud relativa son relativas a algo más, por ejemplo, al tamaño de letra del elemento principal o al tamaño de la ventana gráfica. La ventaja de usar unidades relativas es que con una planificación cuidadosa puedes lograr que el tamaño del texto u otros elementos escalen en relación con todo lo demás en la página. En la tabla siguiente se enumeran algunas de las unidades más útiles para el desarrollo web.

![Untitled](img/Untitled%20108.png)

Ejemplo

![Untitled](img/Untitled%20109.png)

![Untitled](img/Untitled%20110.png)

# Aplicar estilo a <body>

Al elemento body se le peude dar un estilo mediante la aplicación de atributos. Estos atributos se aplicarán a todo el body

![Untitled](img/Untitled%20111.png)

# Prioriza un estilo sobre otro

![Untitled](img/Untitled%20112.png)

![Untitled](img/Untitled%20113.png)

El orden de las clases en el archivo html no define cual es prioridad. Es la última clase que aparece en el archivo css

![Untitled](img/Untitled%20114.png)

# Prioridad de class vs id

Id se prioriza sobre las clases, y las clases sobre lo selectores de tipo

# Prioridades de los estilos en línea

El estilo en línea se prioriza sobre el id. Si se desea que un atributo sea prioridad sobre los demás, se debe colocar !important y así se prioriza

![Untitled](img/Untitled%20115.png)

# Códigos Hexadecimales para Colores

Código en base 16. Es decir que cada dígito puede tener 16 valores diferentes, entre 0 y 1 y A y F

![Untitled](img/Untitled%20116.png)

![Untitled](img/Untitled%20117.png)

![Untitled](img/Untitled%20118.png)

# Abreviar Códigos Hexadecimales

ff00ff=f0f

000000=000

00ff00=0f0

# Valores RGB para Colores

![Untitled](img/Untitled%20119.png)

Cada color tiene una equivalencia en los diferentes sistemas de representación

En google se usa COLOUR PICKER y se puede buscar un color y conocer sus diferentes representaciones

![Untitled](img/Untitled%20120.png)

Parandonos sobre el color, se puede acceder en VSC a una herramienta similar a Colour Picker. Allí se puede personalizar un color a gusto, y aparece un cuarto numero (entre 0 y 1) que indica la transparencia del color

![Untitled](img/Untitled%20121.png)

![Untitled](img/Untitled%20122.png)

# Variables en CSS

Una variable es un nombre que se le da a un valor, para poder usarlo más adelante únicamente con el nombre. Se denota con dos guiones previos al nombre de la variable

![Untitled](img/Untitled%20123.png)

![Untitled](img/Untitled%20124.png)