# Practica02

PRÁCTICA DE LABORATORIO  2
 
 
CARRERA: INGENIERIA DE SISTEMA/COMPUTACION 	ASIGNATURA: HIPERMEDIAL 
NRO. 
PRÁCTICA: 	2 	TÍTULO PRÁCTICA: Resolución de problemas sobre CSS3 
OBJETIVO  
•	Entender y organizar de una mejor manera los sitios de web en Internet 
•	Diseñar adecuadamente  elementos gráficos en sitios web en Internet. 
•	Crear sitios web aplicando estándares actuales.  
INSTRUCCIONES  	 
1.	Se pide realizar el tutorial02 del texto guía New Perspectives HTML5 and CSS3, 7th Edition. El desarrollo del tutorial se debe incluir en el informe de la práctica (detallado). 

DESARROLLO TUTORIAL 2.

◗ 1. Use su editor para abrir el archivo tss_home_txt.html de la carpeta html02-tutorial. Ingrese su nombre y la fecha en la sección de comentarios del archivo y guarde el documento como tss_home.html.
 
◗ 2. Tómese un tiempo para desplazarse por el documento para familiarizarse con su contenido y estructura.
◗ 3. Abra la página tss_home.html en su navegador. Parte de la apariencia de la página se muestra en la Figura 2-2.
 
 

◗ 4. Regrese al archivo tss_home.html en su editor HTML y agregue el siguiente elemento de enlace a la sección de encabezado directamente después del elemento de título:
<link rel="stylesheet" href="tss_layout.css" />

 

◗ 5. Guarde sus cambios en el archivo y luego vuelva a abrir el archivo tss_home.html en su navegador. La Figura 2-4 muestra la apariencia de la página utilizando los estilos de diseño definidos en el archivo tss_layout.css.
 
◗ 6. Regrese al archivo tss_home.html en su navegador.
◗ 7. Presione F12 para abrir la ventana de herramientas del desarrollador. ¿Problema? Si presionar F12 no abre las herramientas de desarrollador, su navegador podría necesitar una combinación de teclado diferente. En Safari para Macintosh, puede ver las herramientas del desarrollador presionando ctrl + shift + I o comando + opción + I.
 
◗ 8. En la lista jerárquica de elementos en la página web, haga clic en la etiqueta <body> si aún no está seleccionada. La Figura 2-6 muestra el diseño de los paneles utilizando las herramientas de desarrollador en Google Chrome para el escritorio.

 


Como se muestra en la Figura 2-6, el panel de estilos enumera los estilos que se han aplicado al elemento del cuerpo. Tenga en cuenta que la propiedad de margen de la hoja de estilo del navegador se ha tachado, lo que indica que este estilo de navegador ha sido reemplazado por un estilo definido en la hoja de estilo externa. ¿Problema? Cada navegador tiene un conjunto diferente de herramientas para desarrolladores y
  configuraciones. Es posible que sus herramientas no se parezcan a las que se muestran en la Figura 2-6.
◗ 9. Tómese un tiempo para explorar el contenido y los estilos utilizados en los otros elementos de la página seleccionando las etiquetas de elementos de la lista jerárquica de elementos.
  ◗ 10. Presione F12 nuevamente para cerrar la ventana de herramientas del desarrollador. 

Escribir un comentario de estilo:
◗ 1. Use su editor para abrir el archivo tss_styles_txt.css de la carpeta html02-tutorial.
◗ 2. En la sección de comentarios en la parte superior del archivo, ingrese su nombre después del Autor: comentario y la fecha siguiente a la Fecha: comentario. 
◗ 3. Guarde el archivo como tss_styles.css.
◗ 4. Regrese al archivo tss_home.html en su editor HTML y agregue el siguiente elemento de enlace directamente antes de la etiqueta de cierre </head>. <link href = "tss_styles.css" rel = "stylesheet" />
◗ 5. Cierre el archivo tss_home.html, guardando sus cambios.

Para indicar la codificación de caracteres:
◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. Directamente encima de la sección de comentarios iniciales, inserte la línea: @charset "utf-8" ;. La Figura 2-7 resalta el nuevo código en la hoja de estilo.
Tenga en cuenta que solo una regla @charset debe aparecer en una hoja de estilo y siempre debe preceder a cualquier otro carácter, incluidos los comentarios.
 
◗ 3. Guarde sus cambios en el archivo.

Para definir colores de fondo y texto:
◗ 1. Agregue el siguiente código dentro de la sección HTML y Estilos de cuerpo: 
html {    background-color: hsl(27, 72%, 72%); } 
 
body {    color: rgb(91, 91, 91);   
 background-color: ivory; }
 
◗ 2. Agregue las siguientes reglas de estilo dentro de la sección Estilos de encabezado: 
h1 {    color: white;    
background-color: rgb(222, 128, 60); 
} 
 
h2 {    color: white;   
 background-color: rgb(235, 177, 131);
 }
◗ 3. Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su navegador. La Figura 2-11 muestra la apariencia de la página bajo los nuevos estilos.
 

Para crear una regla de estilo con un selector contextual:
◗ 1. Si se tomó un descanso después de la sesión anterior, asegúrese de que el archivo tss_styles.css esté abierto en su editor. 
◗ 2. Dentro de la sección Estilos aparte y Blockquote, inserte la siguiente regla de estilo:

aside blockquote  {    
color: rgb(232, 165, 116);
 }
 
◗ 3. Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su navegador. Verifique que el texto de las cotizaciones de los clientes aparezca en naranja.

Para aplicar un selector de id:
◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. Cambie los selectores para los elementos h1 y h2 en la sección Estilos de encabezado a artículo # about_tss h1 y artículo # about_tss h2 respectivamente. La Figura 2-16 resalta los selectores revisados en la hoja de estilo.

 
◗3. Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su navegador. Verifique que el diseño de los encabezados h1 y h2 solo se aplique a los encabezados en el artículo about_tss pero no a los otros encabezados en la página.

Para aplicar un selector de clase:
◗ 1. Use su editor para abrir los archivos tss_run_txt.html, tss_bike_txt.html y tss_swim_txt.html de la carpeta de tutoriales html02. Ingrese su nombre y la fecha en la sección de comentarios de cada archivo y guárdelos como tss_run.html, tss_bike.html y tss_swim.html respectivamente.
◗ 2. Dentro de cada uno de los tres archivos, inserte los siguientes elementos de enlace antes de la etiqueta de cierre </head> para vincular estos archivos a los archivos tss_layout.css y tss_styles.css, respectivamente:
<link href = "tss_layout.css" rel = "stylesheet" /> 
<link href = "tss_styles.css" rel = "stylesheet" />
 
◗ 3. Tómese un tiempo para estudiar el contenido y la estructura de los archivos. Tenga en cuenta que el elemento del artículo tiene el atributo de clase con el programa de valores. Guarda tus cambios en los archivos.
◗ 4. Regrese al archivo tss_style.css en su editor.
◗ 5. Dentro de la sección Estilos de encabezado, agregue la siguiente regla de estilo para mostrar el texto de los encabezados h1 y h2 en gris medio sobre un fondo púrpura claro:
article.syllabus h1, article.syllabus h2 
{    
background-color: rgb(255, 185, 255);    
color: rgb(101, 101, 101); 
}
 
◗ 6. Guarde sus cambios en la hoja de estilo y luego abra el archivo tss_run.html en su navegador. La Figura 2-18 muestra la apariencia de los encabezados h1 y h2 en esta página.
 

Para especificar una familia de fuentes para el cuerpo de la página:
◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. Agregue el siguiente estilo a la regla de estilo para el elemento del cuerpo:

font-family: Verdana, Geneva, sans-serif;

 
Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su navegador. La Figura muestra la apariencia revisada del texto del cuerpo usando la fuente sans-serif

 

Para instalar y usar una fuente web:
◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. Directamente después de la regla @charset en la parte superior del archivo, inserte la siguiente regla @ font-face:
 @font-face {    
font-family: Quicksand; 
   src: url('Quicksand-Regular.woff') format('woff'),          url('Quicksand-Regular.ttf') format('truetype'); 
}
 

◗ 3. En la parte superior de la sección para Estilos de encabezado, inserte la regla de estilo: 
h1, h2 {    font-family: Quicksand, Verdana, Geneva, sans-serif; }
 
◗ 4. Guarde sus cambios en el archivo y vuelva a cargar el archivo tss_home.html en su navegador. La Figura muestra la apariencia revisada de los encabezados h1 y h2 utilizando la fuente web Quicksand.
 

Para establecer los tamaños de fuente de los elementos de la página:
◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. Agregue las siguientes reglas de estilo directamente debajo del comentario Estilos de encabezado para definir los tamaños de fuente para los encabezados h1 y h2 en todo el sitio web:
h1 {    font-size: 2.2em; } 
 
h2 {    font-size: 1.5em; }
◗ 3. Vaya a la sección Estilos aparte y de bloque de comillas y agregue la siguiente regla de estilo para establecer el tamaño de fuente predeterminado del texto en el elemento aparte a 0.8em:
aside {    font-size: 0.8em; }
◗ 4. Vaya a la sección Estilos de navegación y agregue la siguiente regla de estilo para establecer el tamaño de fuente predeterminado del texto en la lista de navegación a 0.8em:
nav {   
 font-size: 0.8em; 
}

◗ 5. Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su navegador. La Figura 2-26 muestra los tamaños de fuente revisados de los encabezados, la lista de navegación y el elemento aparte.

Para establecer los tamaños de fuente de los elementos de la página:
◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. En la sección Estilos de encabezado, inserte el siguiente estilo como parte de la regla de estilo para el selector h1, h2: espacio entre letras: 0.1em;
letter-spacing: 0.1em;

◗ 3. Desplácese hacia abajo hasta la sección Estilos de navegación cerca de la parte inferior del archivo e inserte la siguiente regla de estilo para el texto de los elementos ul anidados dentro del elemento de navegación:

nav > ul {    line-height: 2em; }

◗ 4. Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su navegador. Verifique que el espacio entre letras en los encabezados h1 y h2 se haya incrementado y que la lista de enlaces ahora esté a doble espacio.
 

Para aplicar la propiedad de fuente:
◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. Vaya a la sección Estilos de pie de página y agregue la siguiente regla de estilo:

body > footer address {   
background-color: rgb(222,128,60);    
color: white;    
color: rgba(255, 255, 255, 0.7);    
font: normal small-caps bold 0.9em/3em Quicksand, Verdana, Geneva, sans-serif;    
text-align: center; }

 
◗ 3. Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su navegador. La Figura muestra la apariencia revisada del pie de página del cuerpo.
 

Para aplicar un estilo de contorno:
◗ 1. Asegúrese de que el archivo tss_styles.css esté abierto en su editor.
◗ 2. Desplácese hacia abajo hasta la sección Estilos de lista e inserte las siguientes reglas de estilo para formatear listas ordenadas anidadas dentro del artículo del programa de estudios:
article.syllabus ol {
   list-style-type: upper-roman; 
}
 article.syllabus ol ol
 {   list-style-type: upper-alpha; 
}
 article.syllabus ol ol ol {
   list-style-type: decimal; 
}
 

◗ 3. Guarde sus cambios en el archivo y luego abra el archivo tss_run.html en su navegador. Como se muestra en la Figura 2-33, el plan de estudios para la clase ahora debe mostrarse en un estilo de esquema.
 

Para eliminar los marcadores de las listas de navegación:
◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. Vaya a la sección Estilos de navegación y, dentro de la regla de estilo para el selector nav> ul, agregue el estilo list-style-type: none;
 
◗ 3. Guarde sus cambios en el archivo y luego abra el archivo tss_home.html en su navegador. Verifique que no haya marcadores junto a los elementos de la lista de navegación en la columna izquierda.
 
◗ 4. Vaya a las otras tres páginas en el sitio web y verifique que las listas de navegación en estas páginas tampoco tengan marcadores de lista.

Para usar una imagen para un marcador de lista:
◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. En la parte superior de la sección Estilos de lista, inserte la siguiente regla de estilo:
article#about_tss ul {  
  list-style-image: url(runicon.png); 
}

◗ 3. Guarde sus cambios en el archivo y luego abra el archivo tss_home.html en su navegador. Como se muestra en la Figura 2-36, los elementos de la lista desordenada ahora usan el archivo de imagen runicon.png como marcador de la lista. 
 

Para cambiar el relleno izquierdo utilizado en la lista de navegación:
◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. Localice la regla de estilo nav> ul en la sección Estilos de navegación e inserte el estilo padding-left: 5px ;.
 

◗ 3. Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su navegador. Verifique que las entradas en la lista de navegación en la columna izquierda se hayan desplazado hacia la izquierda, que es el resultado de cambiar la configuración del relleno izquierdo a 5 píxeles.

Para aumentar el margen superior:
 ◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. Directamente debajo de la regla de estilo para el selector nav> ul en la sección Estilos de navegación, inserte la siguiente regla:
nav > ul > li.newgroup {   margin-top: 20px; }
 

◗ 3. Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su navegador. Verifique que las entradas en la lista de navegación ahora estén divididas en tres grupos: el primer grupo que contiene los enlaces del sitio web Tri and Succeed Sports; el segundo grupo contiene enlaces a sitios web sobre carrera, ciclismo y natación; y el tercer grupo que contiene enlaces a sitios web de triatlón.
 

Para cambiar el espacio de margen alrededor de las comillas de bloque:
◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. Localice la regla de estilo para el selector de bloque de citas a un lado en la sección Estilos aparte y bloque de citas e inserte el margen: 20px 5px; estilo en la regla de estilo.
 
◗ 3. Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su navegador. La Figura 2-42 muestra la apariencia revisada de la página con el nuevo relleno y los tamaños de margen aplicados a la lista de navegación y las comillas de bloque.
 

Para aplicar pseudo-clases a una lista desordenada:
◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. Vaya a la sección Estilos de lista en la parte inferior de la hoja de estilos, elimine la regla de estilo del artículo # about_tss ul que establece el marcador de imagen de estilo de lista y reemplácelo con las siguientes tres reglas de estilo:

article#about_tss ul li:first-of-type {   list-style-image: url(runicon.png); } article#about_tss ul li:nth-of-type(2) {   list-style-image: url(bikeicon.png); } article#about_tss ul li:last-of-type {   list-style-image: url(swimicon.png); }

 

2.	Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su navegador. La Figura 2-45 muestra el nuevo formato de la lista desordenada con diferentes marcadores de imagen utilizados con cada uno de los elementos de la lista.
 

Para aplicar pseudo-clases a enlaces de hipertexto:
◗ 1. Regrese al archivo tss_styles.css en su editor.
 ◗ 2. Vaya a la sección Estilos de navegación e inserte las siguientes reglas de estilo para los enlaces de hipertexto que se han visitado o no visitado.

nav > ul > li > a:link, nav > ul > li > a:visited {  
 color: rgb(151, 151, 151);   
text-decoration: none; 
}
 
◗ 3. Agregue las siguientes nuevas reglas de estilo para los enlaces que se ciernen o estén activos:
 
◗ 4. Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su navegador y desplace el puntero del mouse sobre los enlaces en la lista de navegación. La Figura muestra el efecto de desplazamiento aplicado al enlace a la clase de natación TSS.
 

Para insertar comillas en comillas de bloque: 
◗ 1. Regrese al archivo tss_styles.css en su editor.
◗ 2. Vaya a la sección Estilos aparte y de comillas en bloque y, dentro de la regla de estilo para el selector de comillas en bloque a un lado, inserte la siguiente propiedad de comillas para usar comillas para las comillas:
qoutes: "\ 201C" "\ 201D";
◗ 3. Agregue las siguientes reglas de estilo para insertar comillas antes y después de cada comilla de bloque en el elemento aparte:
aside blockquote::before {   
content: open-quote;   
font-family: 'Times New Roman', Times, serif;   
font-size: 1.6em;   
font-weight: bold; 
}
aside blockquote::after {  
content: close-quote;   
font-family: 'Times New Roman', Times, serif;   
font-size: 1.6em;   
font-weight: bold; 
}

 
4. Guarde sus cambios en el archivo y luego vuelva a cargar el archivo tss_home.html en su navegador. Como se muestra en la Figura 2-52, se han agregado comillas en negrita antes y después de cada comentario del cliente
 

Resultado Final: 

 


Github 
Tutorial02
User:ElyPriscy
https://github.com/ElyPriscy/Tutorial02.git
 
 

3.	Se pide realiza un sitio web que tenga al menos una página principal (index.html) y cinco páginas que tengan navegabilidad entre todas las páginas html. Además, se pide utilizar estilos CSS con la finalidad de obtener un diseño como el que se muestra a continuación, para cada uno de las páginas html. El tema elegido por cada estudiante deberá ser distinto al realizado en la práctica 01 – Creación de un sitio web usando HTML5. 

 


	  
Figura 1. Diseño base del sitio web 
   
Se recomienda utilizar, en al menos una página HTML, un diseño a dos columnas con cabecera y pie de página, como el que se muestra en la Figura 2. Así, como también se recomienda utilizar, en al menos una página HTML, un diseño a tres columnas con cabecera y pie de página como se muestra en la Figura 3. 
 
Figura 2. Diseño de un sitio web con base a dos columnas 
 

	  
Figura 3. Diseño de un sitio web con base a tres columnas 

 
De igual manera, se pide que se creé al menos tres archivos CSS, estos archivos estarán almacenados en una carpeta llamada css. Un archivo será para el diseño a dos columnas, otro archivo para el diseño a tres columnas, y los demás archivos será para la reglas CSS relacionas a textos, colores, tablas, secciones, artículos, etc. 
 
También, se pide que se utilice selectores por etiquetas, selectores descendentes, selectores por clase y selectores por id. 
 
Selectores por id: 
 
 
 

Luego, se pide que se personalicen al menos tres etiquetas para títulos (h1 – h6), tanto en color, tamaño, fuente, decoraciones, etc. 
 
   
Asimismo, se pide que se personalice todos los hipervínculos usando pseudo-clases. 

 
 
 
 
 
También, se pide que se cree un menú vertical (navegación) para todas las páginas. El menú debe tener bordes ovalados, con color de fondo y una separación entre cada menú de al menos 5px. 
 
 
De igual manera, se pide crear una nueva página HTML, en donde, se muestre un formulario de contacto que tenga los siguientes campos (nombre, correo electrónico, mensaje y botón para enviar). 
 
 

Asimismo, se pide que se utilice una gama de máximo cinco colores (ver más, https://htmlcolorcodes.com/es/recursos/mejorpaleta-de-colores-generadores/). 

 
Finalmente, se pide que en toda la práctica existan al menos 100 reglas CSS únicas. 



 Etiquetas: 
1.	Background: 		Color de relleno
2.	Width:	96%		Tamaño de ancho de la pantalla del 96%.
3.	Margin:0 auto;	Sin margen, o margen automático. 
4.	Padding:		Relleno
5.	Font-size:
6.	Display:table;	Da sentido de tabla al navegador
7.	Margin-bottom:
8.	Box-sizing:
9.	Border: rgb;		Dar colores de rgb al borde
10.	Resize:vertical;	Para expandir el textarea verticalemnte. 
11.	Max-height: 		Tamaño máximo de ancho del textarea.
12.	Min-height:		Tamaño mínimo de ancho de textarea.
13.	Cursor:pointer; 	Para que al apuntar un botón se ponga un puntero diferente.
14.	Color: 			Para dar color a la letra. 
15.	Text-align:		Para ubicar el texto. 
16.	Height:		Tamaño de alto
17.	Float:			
18.	Box-shadow		Sombreado 
19.	Display:table-row	Da sentido de una fila de una tabla. 
20.	Border-style:solid;	Estilo de borde solido. 
21.	Border-radius:	Contornos redondeados.
22.	Border-style:doublé; 	Estilo de borde de doble línea. 
23.	Border-color: ivory;		Color de borde ivory.  
24.	Clear:both; 
25.	Max-width: 			Tamaño máximo de la caja. 
26.	Margin:auto; 			Centrar el contenido a la medida por defecto.
27.	list-style: none;		Quita las viñetas del menu de navegacion.  
28.	Overflow:hidden; Para ocultar el contenido que sobrepasa, y limpia los float left.
29.	Display:block;		Permite que el padding funcione hacia arriba y abajo. 
30.	Text-decoration:none	Quita el subrayado del texto.
31.	list-style-type: square;		Viñetas Cuadradas.
32.	#img				Hace referencia al id img
33.	a:hover			Efecto que hace cuando se pasa el mouse.
34.	Text-decoration:underline;	subrayado cuando para el mouse por el texto.
35.	Font-size:			a:hover, para que cambie la fuente al pasar el mouse.
36.	 Background:			a:hover cuando se pasa el mouse se cambia de color
37.	Color:#fff			a:hover: cambia el color del texto al pasar el mouse. 
38.	a:active 			Efecto cuando se de un clic 
39.	background 			cambiar el color al dar un clic
40.	a:visited			Hace efecto a los enlaces que se han visitado. 
41.	Color:# 			Cambia de color a un enlace que ya se ha visitado.
42.	a:link 				Da color de inicio al link.
43.	Display:inline-block;		De un elemento en línea nos pasa a un bloque. 
44.	Box-shadow: 0px 2px 0px #222	Efecto de botón
45.	a:active 			box-shadow:none;
46.	height:auto			tamaño de largo es automatico.
47.	ol				lista ordenada
48.	list-style-type:upper-latin;	Viñetas en letras mayusculas
49.	list-style-type:lower-alpha;	Viñetas en letras minusculas /-latin
50.	ul				lista desordenada
51.	list-style-type:square;	viñetas cuadradas.	
52.	list-style-position:inside;	
	No es permitido el uso de plantillas (CSS o HTML). 

 
ACTIVIDADES POR DESARROLLAR  
1.	Crear un repositorio en GitHub con el nombre “Practica02 – Mi Sitio Web (CSS)” 2.	 
3.	Realizar un commit y push por cada requerimiento de los puntos antes descritos. 
3. Al finalizar la práctica se debe validar todas las páginas HTML y hojas de estilos CSS creadas usando el W3C Validator. 
4. Luego, se debe crear el archivo README del repositorio de GitHub. 
5. Generar informe de los resultados en el formato de prácticas. Debe incluir: 
a.	El desarrollo de cada uno de los puntos antes descritos así como las reglas CSS utilizadas para resolver cada punto.  
b.	La evidencia del correcto diseño de las páginas HTML usando CSS. Para lo cuál, se puede generar fotografías instantáneas (pantallazos).  
c.	La evidencia de la validación de cada página HTML. 
d.	La evidencia de la validación de las hojas de estilos CSS. 
e.	El informe debe incluir conclusiones apropiadas.  
f.	En el informe se debe incluir la información de GitHub (usuario y URL del repositorio de la práctica)  
g.	En el informe se debe incluir la firma digital del estudiante. 
6. En el archivo README del repositorio debe constar la misma información del informe de resultados de la práctica que se indica en el punto anterior. 
 
RESULTADO(S) OBTENIDO(S): 
• Tener el conocimiento suficiente para que el estudiante pueda entender y organizar de una mejor manera los sitios de web y de negocios en Internet 
 
CONCLUSIONES:  
• Se logró organizar sitios web basados en el lenguaje de etiquetado HTML y CSS 
•	Se conoció varias etiquetas nuevas y su funcionamiento.
•	Se aprendió probar valores en el mismo navegador para un mejor resultado.

 
RECOMENDACIONES:  
• Probar la solución de la práctica en al menos tres navegadores web; Google Chrome, 
Firefox y Safari 
 
 
 
 
Docente:  Ing. Gabriel León Paredes, PhD. 
Firma:   
 
