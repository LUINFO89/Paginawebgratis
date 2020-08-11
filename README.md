# paginaemprendimientoweb
# Paginawebgratis
En este codigo podras encontrar la creacion de la pagina web , con HTML y CSS , para los procesos basicos de un emprendimiento y/o de una pagina web comercial.

DONACIONES https://paypal.me/luishernandosoto?locale.x=es_XC

CREA TU PAGINA WEB EMPRESARIAL O DE EMPRENDIMIENTO 
PERSONAL 
COMPLETAMENTE GRATIS.


Profesional:
Licenciado en Informática
Luis Hernando Soto Mesa

 


COMO DESARROLLAR UNA PAGINA WEB 
FÁCIL USANDO CSS Y HTML 
DISEÑO PROFESIONAL


Hola hoy les enseñare a a crear una pagina web fácil y con unos sencillos comando de HTML y CSS,
Los enlaces del codigo completo de la pagina los podras encontrar en mi git-hub

Bueno los quiero invitar a mi curso completo de desarrollo web donde encontraremos todos los procesos de creación de una web desde cero hasta construir varios proyectos como son una pagina web para su empresa comercial y una pagina web para un hotel.

Sin mas los invito a disfrutar de los siguientes pasos:


Lo primero que debemos hacer es crear una carpeta principal con el nombre desarrollo :
En esta carpeta crearemos unas sube-carpetas como veremos a continuación.









Después de crear las carpetas debemos tener en cuenta que guardaremos en ellas es por esto que dejaremos muy claro audio para música , css para los estilos ,img imagen ,js java script video y el index se dejara por fuera para tener en cuenta para la estructura de la pagina. 

Bienvenido a HTML!


Después de crear las carpetas nos dispondremos a crear el index,html de nuestra pagina .

HTML son las siglas en ingles de Hyper Text Lenguaje corresponde a sus siglas en ingles “Hiper Text Markup Languaje” que traduce “ Lenguaje de Marcado de Hipertexto”.
HTML siendo un lenguaje de marcado utiliza etiquetas a diferencia de los scripting o códigos de programación , estas etiquetas son las que permiten que el navegador reconozca la estructura del archivo y gestione el orden de las etiquetas a ejecutar.
Ejemplo de una etiqueta en HTML.
<p> Soy un párrafo </p>





ESTRUCTURA DE UNA PAGINA

La capacidad de programar usando HTML es esencial para cualquier profesional que este en construcción de una web y de tal manera es importante que sepa reconocer de manera automática cual es la estructura de esta, es así que estas habilidades deben ser el punto de partida para la generación de contenido.

Etiqueta HTML :

Esta es una de las etiquetas principales en el desarrollo de HTML en esta es donde agregamos y informamos al navegador que tipo de archivo vamos a enviarle, esta etiqueta funciona igual que un sándwich que tiene dos rebanadas de pan una superior y una inferior al igual esta etiqueta y las demás deben tener de manera obligatoria una etiqueta de inicio y una de cierre .

Ejemplo de nuestro sándwich 
<html>
………..
</html> 

La etiqueta <head> :

Los elementos de cabecera son los elementos no visuales de la pagina, pero son supremamente importante ya que son los que permiten ubicar los link de css o script de java u otros lenguajes así mismo son los que nos procesan el algoritmo de google en los navegadores y posiciona nuestra pagina.
<html>
<head>………..</head>
</html> 

La etiqueta <body> :

La etiqueta body sigue después del head 
Todos los elementos visuales del contenido web se ubicaran en la etiqueta <body>
Títulos encabezados imágenes párrafos botones .
<html>
<head>………..</head>
<body>
</body>
</html>


CREACIÓN DEL ARCHIVO HTML

Los código de HTML son archivos de texto , por lo que se puede utilizar cualquier editor de texto para crear tu primera pagina web.
Existen algunos editores de código profesionales como sublime text3, visual studio code, etc, puedes investigar sobre estos pero por ahora vamos a escribir nuestro ejemplo en el bloc de notas del pc.

EL ARCHIVO :

Después de tener los conceptos básicos de HTML y su estructura pasaremos a desarrollar nuestro primer archivo para este caso usaremos SUBLIME TEXT 3 como editor de texto para el desarrollo.

Lo primero que crearemos sera darle clic en nuevo file , New file , después daremos clic en guardar .









Al dar clic en guardar como debemos agregar la extención del archivo como .html

después de guardar nuestro archivo lo abriremos con sublime text y agregaremos la etiqueta <html y damos un enter  esto nos agregara de manera automática la estructura básica de nuestro html para empezar a trabajar.








Para nuestro HEAD agregaremos las etiquetas META las cuales son las encargadas de dar esa conexión de comunicación directa con nuestro navegador es decir se conectara a traves de esta 

<meta charset="utf-8">
       <meta http-equiv="X-UA-Compatible" content="IE=edge">
       <title>BasketballStore.com</title>
       <link rel="stylesheet" type="text/css" href="css/estilo.css">

Ahora analizaremos estas etiquetas donde meta compatible con los navegadores edge y demás esto es el fin de poder generar una adaptación de pantallas .

Agregaremos un title que corresponde al nombre o titulo de nuestra pagina web que se vera reflejada en la parte superior del navegador.





Es aquí donde veremos ese primer reflejo de nuestra pagina 

Así mismo agregaremos otros enlaces correspondientes al link rel que corresponde a las referencias de nuestra conexión a nuestra hoja de estilos.css que crearemos en el siguiente capitulo.
ESTILO.CSS

Los estilos css son denominados hoja de estilo de cascada quienes se encargaran de darle ese dinamismo y color a nuestra pagina web, sin los css tendríamos paginas web planas y sin vida, es este el que se encarga de darle ese arte ese sentimiento a una pagina para que el usuario interactué , navegue y luego genere una interactividad de compra.


Para crear el estilo de nuestra pagina debemos estar el el sublime text , por consiguiente daremos clic en el boton NEW , new file y posterior daremos clic en guardar y es aquí donde daremos el nombre de estilo.css y guardaremos en la carpeta que previamente creamos .



En este archivo crearemos el contenido relacionado a los estilos es así aquí lo abriremos con nuestro sublime text y agregaremos las primeras lineas de código.

En el manejo de HTML vimos como se empezaba a trabajar con etiquetas , para este caso en el uso de CSS no usaremos etiquetas , las tomaremos como referencia es decir como vimos en el capitulo anterior al momento que agregamos la etiqueta link le dimo como referencia que se conectara o enlazara a un archivo llamado estilo.css, le dimos la ruta donde vamos a enlazar esos archivos .

<<
Muy bien si agregamos estas lineas de codigo en el html en el head estaremos dando la ruta del css, es asi que debemos ahora realizar el procedimiento de trabajo para los estilos, es por esto que ahora nos dirigimos al archivo estilo.css y agregamos un # que sera en este caso un valor unico para establecer como estilo y/o seleccionamos un . Para las clases de los atributos de la pagina .

Vamos a ver un ejemplo, en el HTML agregamos la etiqueta <div> dentro del body :
los div son conocidos en el mundo html como contenedores u etiquetas para organizar .
<body > 
	<div id=”principal” > </div>
</body>
como vimos al div le agregamos un id =”principal” y en el estilo le agregaremos ahora las siguientes leneas con el fin de darle un estilo.











GENIAL!
Como vemos el resultado sera un lienzo de trabajo para empezar a agregar nuestro código.

El siguiente bloque de estilo sera una classe que relacionara los valores correspondientes a nuestra pagina.

header{
    width: 1000px;
    height: 100px;
    border: 1px solid #FFFFFF;
    
}

Bueno aquí tenemos lo que es una linea general del header quien se encargara de dar un encabezado a nuestros archivo es este el encargado de establecer los valores correspondientes al menu.

Bueno vamos a ser claros en este proceso existen dos formas de creación de del código uno puede ser agregar primero todo el html y después agregar el código de Css , esta es una de las practicas pero para mi caso me gusta mas ir desarrollando en bloque es decir a medida que creo el HTML voy modificando en css.

Bueno ahora voy a modificar el html .




Como vemos en este código HTML podemos observar que encontramos un div con un nuevo id de nombre logo agregamos dos clases una para el titulo y otra para el subtitulo , sin embargo vemos dos etiquetas comunes del HTMl como el H1 Y el P que denominan titulo y párrafos.
Bueno en este espacio llamado logo como el mismo nombre lo indica es para establecer un icono en la parte lateral izquierda de la pantalla.












De esta forma se agregara el logo o el nombre de tu empresa.

Como segunda medida vemos que tenemos un nav con class=”menu” este class en el estilo.css se asignara el menu de pantalla correspondiente en este caso agregaremos varias lineas de codigo estas corresponden a los UL que seria como el marco y los LI y A para las referencias de hipervínculos , como vemos el html sin la etiqueta de estilos se vera de esta forma.


Como vimos en el capitulo anterior , pudimos evidenciar como agregar un logo o un nombre de empresa como encabezado con el header, así mismo agregamos el menú correspondiente a nuestra pagina, pudimos ver que si creamos nuestra pagina en html nos quedara unos enlaces simples y sin diseño es aquí en donde nuestro ingenio entrara a flote y le pondremos los colores tipos de letra tamaño etc.

como podemos ver nuestra pagina con estilo se vera totalmente diferente :
Ahora vamos a agregar las etiquetas que nos faltan a nuestro estilo.css

Listo como vemos aquí estamos gestionando los menús para la parte superior de nuestra pagina el .menu hace referencia a las clases que utilizaremos es decir el nav tomara en cuenta la clase menú y en el css agregaremos los ul o los li correspondientes 

como podemos observar en el codigo de la imagen podemos encontrar en ingles los valores correspondientes a los colores de fondo en hexadecimales es decir  #ffffff a los tamaños del menú en los bordes los padding que corresponde a los valores de los espacios de pantalla.


En este capitulo usaremos los valores correspondientes a la imagen de jordan que para este caso se denominaremos los valores del slide.


Para este caso veremos el id como slide que es la imagen de jordan.





















Bueno como vemos en pantalla los omg 1,2 ,3 corresponden a las clases correspondientes a los textos que se ven en pantalla para luego mostrar los productos.








LISTO!
	En este capitulo veremos como se realizara la selección de las categorías de los productos.


































Bueno ahora agregaremos los valores correspondientes a la selection que corresponde a los valores de los marcos o casillas de trabajo donde vamos a incorporar nuestros productos como veremos a continuacion.



Como vemos realizaremos los espacios correspondientes a los tennis o productos que se colocaran para la venta.

Estos códigos los pondremos en referencia para los section o secciones de pantalla 
en el html como vemos agregamos la imagen con la etiqueta img y le dimos una proporción de alto y ancho por cada imagen , agregamos la etiqueta h2 .
Agregaremos las secciones correspondientes a la cantidad de productos a mostrar en la pantalla en este caso usaremos 2 filas 3 columnas .

Ya para terminar agregaremos los valores correspondientes al pie de pagina .


















Como podemos ver en la imagen daremos a conocer los valores correspondientes a la ultima selección de los valores de la pagina para dar a conocer las redes sociales .


<section id="red">
                            <h4 class= "red1">¡Siguenos en nuestras redes sociales!</h4>  
                            <p class="red2">Instagram , Twitter , Facebook como @Basketball_World_Off</p>
                            <section id="slide2">
                                <img src="img/red.jpg" width="500" height="230">
                            </section>
                             
  </section>

Daremos como valor el dato a conocer de nuestra imagen final y las etiquetas en las clases red1 y red2 
#red{
    width: 993px;
    height: 350px;
    border: 1px solid #DF0101;
    float: left;
    padding: 2.5px;
    
}
.red1{
    text-align: center;
    
}
.red2{
    text-align: center;
}

esto nos dara a conocer la ubicación de los valores correspondientes a nuestra pagina.

Bueno como vemos hemos creado una pagina web basica con HTML Y CSS donde daremos a conocer a nuestros clientes los productos que manejamos o los servicios que se van  a publicar de esta manera nuestra empresa sera reconocida y vista para sus procesos empresariales .

NOTA : Para la publicacion de la pagina en internet recomiendo que compren un servicio de hosting gator , pueder ingresar y seguir los pasos de compra con el siguiente enlace .

https://luishernandosoto.wordpress.com/

Si deseas el servicio o tutoría para un emprendimiento o di deseas re inventar tu negocio puedes comunicarte conmigo y con gusto generare un plan de negocio en marketing digital y utiliza internet para ganar dinero.

Para donaciones o apoyo para continuar con los cursos y eventos gratuitos lo puedes hacer por el siguiente enlace.
				
https://paypal.me/luishernandosoto?locale.x=es_XC


