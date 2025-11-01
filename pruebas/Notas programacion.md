# **Programación data:**

**ABM:** Se refiere a las operaciones básicas de gestión de datos en una base de datos: alta (crear un nuevo registro), baja (eliminar un registro) y modificación (actualizar un registro).Programación de software entero que desde el frontend se envíe datos hacia un backend, donde se impacte y se guarde en una base de datos.

**Frontend:** Es la interfaz visual, lo que se ve y se siente al usar la aplicación, incluyendo elementos como botones, menús, imágenes y texto, donde el usuario interactúa. El frontend trabaja en conjunto con el backend y su comunicación se realiza a través de APIs. Ejemplo: HTML, CSS, JAVA

**Backend:** Se encarga de la funcionalidad, la lógica, el procesamiento de datos y la gestión del servidor. No es visible para el usuario final. Ejemplo: JAVA, .NET, NODEJS, PHYTON

**Framework:** Es una estructura o conjunto de herramientas que proporciona una base para el desarrollo de software. Actúa como una plantilla o esqueleto, ofreciendo componentes reutilizables, patrones de diseño y reglas predefinidas para facilitar y acelerar el proceso de creación de aplicaciones. En lugar de empezar desde cero, los desarrolladores utilizan frameworks para construir sobre una base sólida, ahorrando tiempo y esfuerzo en tareas comunes y estandarizando la forma en que se escribe el código.

**API:** Es un conjunto de reglas y especificaciones que permiten que diferentes aplicaciones de software se comuniquen e interactúen entre sí. Actúa como un intermediario, permitiendo que una aplicación acceda a funcionalidades o datos de otra sin necesidad de conocer los detalles internos de su funcionamiento.

**JavaScript:** se utiliza principalmente para crear contenido dinámico e interactivo en páginas web, mejorando la experiencia del usuario. Permite realizar acciones como validar formularios, crear animaciones, actualizar contenido en tiempo real, entre otras funciones, sin necesidad de recargar la página.


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**HTML**

Para empezar la estructura siempre colocar **"html:5"**

-Se empezaria con el **HEAD** el cual seria la informacion de la pagina, que no se ve. Ejemplo el nombre de la pestaña o logo

-En el **BODY** seria todo lo que iria dentro de la web visiblemente.

-En HTML siempre se define cada codigo por Etiquetas, que pueden ser en Bloque o en Linea

-El encabezado "H1" es importante solamente usarlo una sola vez en la web, por la importancia del posicionamiento CEO (posicionamiento web). Luego, usar "H2" o los demas como mas subtitulos.

**-Listas:**
Ordenadas: Se escribe como "ol" y por dentro se agregan los "li" que serian los elementos. Esto mostraria una lista con los elementos ordenados, ejemplo: 1. 2. 3. etc.
Desordenadas: Se escribe como "ul" y por dentro se agregan los "li" que serian los elementos. Esto mostraria una lista con los elementos sin orden, es decir sin numeracion.

**-Enlances:** Se usa la "a" refiriendose a Ancla. Generalmente se crea en conjunto con la propiedad de "href" para agregar el link dentro y que eso lo rediriga. Luego dentro de la "a" se debe agregar un texto.
-Ahora si la web tiene varias secciones de link, se puede usar para que te mande a esas otras secciones a travez del link, colocando el nombre del html de visual.
-Tambien se puede configurar para que el link se abra directo en otra pestaña. Para configurarlo funciona igual pero con el atributo de: target="\_blank".
-Se puede agregar la propiedad de "title" para que si el mouse se pasa por encima del enlace, se muestre un texto del significado o lo que se desee aclarar.

-Otra funcion es crear enlances dentro de la misma web, donde al hacer click te puede llevar un apartado en especifico de la misma web. Esto se usa con ID. O sea agregasmos la "a" y en el href colocamos "#nombredeid". Despues al elemento donde queremos que nos lleve, colocamos un id con el mismo nombre.

-Tambien se puede hacer que un link genere una descargar de un archivo. Por ejemplo colocando dentro del href el link del archivo y luego la propiedad de "download" funcionaria.

-Una cosa importante es ciertos enlaces de paginas (sobretodo usando target blank) es usar la propiedad de "rel=noopener", esto evita que te redirigia a otro lugar que no se quiera, no modifique la pagina de donde viniste y demas cosas de seguridad. Tambien se puede usar la de "rel=noreferrer".

-Se puede hacer que el link te genere mandar un mail de forma directa. Esto es agregando "mailto:xxx" el mail de destinatario en el href. Esto mismo se puede hacer con un numero de celular, usando "tel:xxxx"

**-Imagenes:** Se usa con "img" y dentro el atributo de source o "src" para que busque la ruta de la imagen en nuestra compu. Tambien se puede usar la propiedad de "alt" en la cual es posible agregar una alternativo por si la imagen no carga o se pierde, por ejemplo un texto aclarando lo que es.
Las etiquetas de imagenes no son necesarias cerrarlas.

**-Rutas:** 
Absolutas: Es un enlance o direccion abosoluta es decis no importa desde donde se entre ni donde estemos. Siempre llevaria a ese enlace.
Relativa: Va a depender de donde estemos para poder acceder al archivo, es decir si esta guardado dentro de una carpeta en especifico por ejemplo, debemos aclararlo en el enlace del codigo que busque ahi dentro.

**-Formularios:** Inputs para recopilar datos del usuario en caso de necesitarlos. Se usa la etiqueta "form" y dentro agregar la propiedad de "input" para que el sistema detecte que debe recibir un dato. Por ultimo dentro se elige el "type" para elegir que tipo de input seria y lo que el cliente puede tipear.
 ATRIBUTOS: 
    -"value" ya sea para dejar anotado algo dentro del form o cambiar la palabra predeterminada que venga del type.
    -"required" para que el campo del form no pueda quedar vacio al intentar enviarlo (posible agregar el "minlength" para olbigar a que se escriba un minimo)
    -"name" se usa para identificar inputs y que el servidor verifique como se llama cada campo. Es importante agregarlos para que luego en la programacion se puedan verificar los datos y demas.
    -"placeholder" agrega un texto visible dentro del form que desaparece cuando el usuario empieza a escribir.

**Comentarios:** un mensaje que solo nosotros podemos leer, y se deja en el codigo para aclarar cosas, en caso de ser necesario. Se hace con /*xxxx*/

**Logos:** Es el que figura en la pestaña. Se agrega desde "Head" con el elemento "link" y su relacion es icon. Luego se agrega la ruta y se escribe el type (el formato de la imagen), para que cargue mas rapido y demas.

**Metadatos:** Etiquetas en la web que se agregan desde "head", los cuales son importantes de forma general. Por ejemplo para marcar que la web siempre se adapate al ancho, etc. A su vez funciona de forma interna para los posicionamientos de la pagina.
Como predeterminado viene el Meta viewport y content.
Luego esta: -Meta name description: para agregar una descripcion de la pagina
            -Meta name keywords: agregar palabras claves de la pagina
            -Meta name author: agregar el autor de la pagina
            -Meta name robots: en el cual podemos agregar que: -la pagina no guarde en cache: "noarchive"
                                                               -la pagina no figure en los resultados: nofollow
                                                               -la pagina no toma fragmentos de nuestra pagina para mostrar en resultados: nosnippet
            -Meta name OG: se usa para que en los links de algun lugar, directo se muestre algunas informaciones. Como el video, la portada, titulo, etc.

**Textarea:** Es un elemento donde se puede escribir, sin un limite como tal. Se usa mas en los formularios como para agregar el comentario. Es importante ajustarlo con diseño luego para que no rompa los demas elemntos. Por ejemplo con un alto y ancho maximo a agrandar y tambien un minimo. Podemos usar la propiedad de Resize en css para elegir si queres que se agrande solo en vetical, solo en horizontal o que no agrande.
Se puede hacer que no se pueda escribir. O sea nosotros dejar um mensaje pero que el usuario no puedo escribir nada en el campo. Tambien se puede hacer que no pueda ni clikearlo.

**Labels:** Elemento que pueden funcionar para etiquetar inputs. Se le puede hacer focus, para que al presionarlo, te mande directo al input del form. Para esto debemos colocar un id en el input y luego en el label colocar "for" con el nombre del id. Sino se puede hacer con que el label contenga al input y tambien le da focus.

**Select y datalist:** Los select son un campo para poder elegir un dato entre varias opciones. Los datalist son input que se autocompleta con opciones que configuramos.
Para los select tenemos que agregar el elemento y dentro colocamos "option" con el nombre de cada opcion.

**Details y Summary:** La idea de estas etiquetas es crear un contenido desplegable. Por ejemplo como cuando figura en google las respuestas rapidas.
Usamos el elemento "details" y dentro creamos el "summary" con el titulo de lo que se se veria al principio.Luego abajo hiria toda la descripcion de lo que apareceria si abrimos la lista.
Si usamos "details[open]" podes elegir opciones diferentes para cuando el elemento este cerrado o abierto.

**Tablas:** Hace tiempo se usaban para todo en las web, pero ahora es solo para agregar datos tabulares. Se usa la etiqueta semantica de "table". Dentro se coloca "tr" que es para armar una fila. Luego "td" es la columna. Y tambien estan los "th" que es para agregar el encabezado de cada columna.
En caso de que una de las filas tenga menos columnas de datos, se puede usar el atributo de "colspan= x".
Con los estilos podemos agregar los bordes y demas valores de amplitud.

**Audio y Video:** Se usan dos etiquetas la de "audio" y la de "video". En video se busca en el src la ruta del video. Ademas se deben agregar atributos como:
-Autoplay para que empiece el video cuando guardamos la pagina
-Controls y figurarian los botones
-Muted para que cuando se recarga la pagina se reproduzca
El video se debe crear como un archivo en visual, no funciona si se busca como una imagen en una carpeta.

Para los audios es lo mismo pero usando la etiqueta "audio" y el archivo tiene que ser de tipo audio.

**Carga Diferida:** El contenido se carga a medida que el usuario va bajando y llegando al elemento. Sirve mucho para las imagenes, cuando hay varias.
Por ejemplo en las imagenes se agrega el atributo de "loading:lazy".

**HTML Semantico:** Con esto es ideal usar los tipos de etiquetas ideales para cada apartado de la web. Se pueden reemplazar por tantos DIV. Ademas de esta manera queda mas correcto semanticamente y ordenado. Por ejemplo la etiqueta de "nav" para la barra de navegador, la de "section" para seccionar todo un apartado o tambien la de "footer" que seria para el pie de pagina.

**Accesibilidad Web:** Se usa el codigo con la idea de que cualquier persona pueda ver o entender la pagina. Por ejemplo una persona ciega, que usa la accesibilidad, puede entender la pagina a pesar de no verla, si generamos el codigo correctamente.


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**CSS**

Se usa para darle estilos a los elementos creados previamente en HTML o el codigo que sea.

Como enlazarce a css:
-Puede ser en linea, es decir desde el mismo codigo generado en html, agregas el atributo de "style" y lo que se quiera modificar. Pero esto no es lo ideal, ya que no seria lo mejor mezclar los estilos con los codigos. Cada lenguaje por separado.

-La mejor opcion es usar la propiedad de "link" creada dentro del "head". Con el atributo de "rel" y "stylesheet". Seguido del enlance del ccs creado Asi: <link rel="stylesheet" href="">. De esta manera vinculamos con el archivo css creado donde colocaremos todo.

Primero se agrega el selecctor a editar, es decir si todos los parrafos van a ser en rojo, agregamos la letra "p" y dentro de las llaves colocamos el estilo.

**Selecctores:** 
  -Seleccion por elementos: Si todos los parrafos van a ser en rojo, agregamos la letra "p" y dentro de las llaves colocamos el estilo. De esta menera seleccionamos a todos esos elementos.

  -Seleccion puntual: -Se puede usar la etiqueta "span" y asi lo que va dentro solamente tendria el estilo. Es una manera, pero no la mejor de todas y depende el caso.
                      -Se puede a travez de las "clases" que es la mejor opción. Se usa con la etiqueta de "class" y se agrega un nombre cortito para identificar. Para identificarla en css se usa con . (punto) y el nombre. Se puede usar en varios para identificar.
                      -Otra manera es con "id" se usa para algo muy clave y solo es una vez en el codigo. Para identificarla en css se usa un # (hashtag) y el nombre.

**Selectores avanzados:** Maneras mas complejas de seleccionar los elementos de la web y darle sus caracteristicas. Diferentes formas para encontrar la mejor manera de hacerlo en diferentes ocasiones.

-Selector de atributo: De esta manera podes modificar varios elementos que tengan el mismo atributo. Por ejemplo en una imagen le colocamos el src y su ruta. Ahora eso mismo lo podes modificar en css, agregando entre corchetes ese atributo en especifico. De esa manera todas las imagenes que tengan el mismo atributo de la ruta, tomara el mismo diseño.
Dentro del corchete se puede agregar el signo de Pesos $ para que se detecte que el terminar debe ser el mismo. O sea no importa con que empieza pero debe terminar con PNG por ejemplo.
  Ejemplo Practico: img[src$="png"] {}
Si queremos que sea al revez, o sea que tome lo que empieza con algo seria con el signo cirncunflejo ^. 

-Selectores descendientes: Seria para agregar elementros que esten dentro de otro. Aca debemos agregar el elemento padre y el hijo, luego colocar las llaves y completar. Quedaria: x > x{}

-Selector de hermano adyacente: Se usa para seleecionar elementos que estan a continuacion de otro. Se agrega el nombre del elemento + el otro nombre: xx + xx {}. Esto solo funciona en el primer elemento que suceda, pero no para todos los que sigan (en caso de tener varios iguales).

-Selector de hermano general: Con este podes hacer lo mismo, pero que aplique para todas los elementos que le sigan. Aca se usa el signo de ~. Queda: xx ~ xx.

**Propiedades de Texto:** (formas de darle diseño)
  -color (color de texto o fondo)
  -font-family (tipografia de fuente)
  -font-size (tamaño de fuente)
  -font-weight (grosor de la fuente, segun la tipografia) ("bold" la hace negrita y gruesa y "bolder" la hace mas gruesa aun)
  -font-style (como figura la tipografia, es decir si es curvisa, normal, oblique, etc)
  -text-align (desde donde arranca el texto en su elemento). Solo funciona en las etiquetas que no ocupan todo su elemento.
  -text-decoration (subrayado, subrayado por arriba, tachar)
  -line-break (espaciado entre lineas de texto)
  -text-transform (definicion de mayuscula o minuscula el texto)

    CONTROL DE FLUJO DE TEXTO: manejos de textos
      WHITE-SPACE:
        -nowrap: no hay saltos de linea, queda todo en una misma, a pesar de desbordar en el contenido.
        -pre: toma el salto de linea segun como lo tengas escrito en el codigo html.
        -pre-wrap: parecido al normal, si el texto no entra te genera un salto de linea automatico. Ademas de respestar los saltos de linea que genere uno.

**Modelo de Caja:** Es el contenido del elemnto, es decir la caja que contiene. Y se puede ajustar y modificar segun como queremos que interacciones con las demas.
   Las propiedades son:
    -Contenido: el nucleo, el elemento que figuraria.
    -Padding: el margen entre el contenido y la caja.
    -Border-width: un borde alrededor de la caja. Tambien esta "border-style" y "border-color". Se puede definir las 3 propiedades por separado o todo en una usando solo "border" seguido del tamaño, estilo y color.
    -Margin: El espacio alrededor de toda la caja.
    -Border Radius: redondeo en la forma de la caja
    -Height
    -Width
    -Box-sizing: Se usa para ajustar que la medida total de la caja sea el ancho y alto que le coloquemos. O sea que si hay margen, borde, paddin, etc, todo se suma para que de el total del box que definamos
    -Gap: se usa para dar espacio entre los bloques (en flex)

**Unidades de Medidas:**  PX: pixeles, seria cada pequeña luz del monitor. Generalmente se usa para definir alto y ancho de imagenes, tamaños de texto, margenes, padding, etc.
                          PT: puntos (Ni se usan)
                          Milimitros/Centimetros/Pulgadas: se usan por si algo se va a imprimir, para que tengan ese espacio literalmente en la impresion. Medidas fisicas serian.
                           TODAS ESTAS SON ABSOLUTAS, ES DECIR QUE NO SON RESPONSIVE. SI LUEGO ABRIMOS LA WEB EN EL CELU, ESTAS MEDIDAS NO SON LAS IDEALES, CIERTO ALGUNAS COSAS

                          RELATIVAS: Van a depender de otro valor para su medida. Super importante para el responsive.
                           Porcentaje: Siempre ocuparia el mismo porcentaje de medida segun de lo que tenga adentro. Es decir se adapta a ese porcentaje segun el total del elemento padre.
                           EM: Usa el valor que tenga el elemento padre y toma su valor, para igual, duplicar, etc segun cuanto em le pongamos.
                           REM:  Usa el valor que tenga el elemento raiz, o sea html y toma su valor, para igual, duplicar, etc segun cuanto em le pongamos.
                           VH y VW: Medidas del total de la vista de la pagina, o sea de toda la pantalla (se usa mucho en ventanas modales).

**Fondos:** Se usa la propiedad de "background", pero entre ellas se puede generar mas cosas.
             -Color:agregar color de fondo
             -Transparencia: usar opacity
             -Imagen: usar background-image, con esto hacemos que en el fondo del elemento haya una imagen. A pesar de no colocar imagen propiamente.
             -Size: usar backgroun-size, es para controlar el tamaño del fondo y cuanto queremos que mida. Se puede usar el atributo de "contain" para ajustar la imagen y que entre sea como sea, pero se puede repetir. Si usamos el atributo "cover" la imagen se adapta y sin repetirse.
             -Position: usar backgroun-position, para elegir el lugar, left, center, right, top, bottom.
             -Attachment: se puede usar con el atributo "fixed" y eso genera que al usar el scroll la imagen vaya subiendo o bajando

             Gradientes: Se usa con "background" o #background-image", hay diferentes tipos de gradiantes.
                        -Lineal: "linear-gradient" agregando los dos valores o mas de color. Se puede colocar desde donde empezaria con "to right" , "to left" o "to bottom".
                        -Radial: "radial-gradient" funciona igual, pero hacia el centro se genera el gradiente.

**Sombras:** La idea es crear mas realismo y con que parezcan con dimension. Pueden ser tres tipos:
             -Box-shadow: funciona para el elemento de una caja, ejemplo un div.
             -Text-shadow: funciona para la sombra de los textos
             -Drop-shadow: funciona para otro tipo de componente x. Ejemplo en una imagen que esta en PNG. Con la propiedad de "filter: drop-shadow"
Primero se agrega el valor en horizontal, luego en vertical, despues la cantidad de desenfoque, cuarto va el grosor digamos. Por ultimo el color.
En la sombra de texto el cuarto valor no se debe agregar.

**Herencia:** Caracteristicas que se pueden heredar en los elementos del codigo. El ejemplo mas claro es con el Body, si a este mismo le coloco que la letra va a ser de color violeta, tooodos los elementos de dentro del body, sin importar, van a ser de color violeta. Al menos que se pisen con las caracteristicas del elemento puntual. Si al texto puntual le cambio el color solo en ese, ahi si tomaria ese estilo y no el del body.

**Cascada y Especificidad:** La funcion de esto es que el propio css, identifica las caracteristicas y acomoda segun a lo que debe estar agregado teniendo en cuenta la cascada. Ejemplo si agregaste dos veces el color en un texto, el css va a quedarse con el que este en la linea inferior. O sea se basa en el orden que esten colocado el estilo.
Ahora en cuanto a la especificidad, se basa en la importancia del elemento por asi decirlo. Es decir si un div y el elemento suelto tienen el mismo estilo, css va a tomar el color del div, a pesar de que figure antes que el otro elemento. Esto pasa por la especifidad del div y su clase. Lo mismo pasa con un ID en un elemento, es mas importante que una clase y que un elemento suelto.

**Pseudo-Clases:** Son formas de seleccionar un momento y cambiar las caracteristicas cuando pase tal cosa. Ejemplo el texto es azul, pero si paso el mosue por encima se pasa a rojo.
Ese mismo ejemplo se usaria con: 
              -hover en el css: h1:hover{}.
              -active seria al clickear el elemento
              -first-child esto selecciona el primer elemento de lo que este dentro
              -nth-child(2) selecciona el segundo elemento. Si cambio el numero toma el tercero y asi.
              -last-child igual pero para el ultimo elemento de lo que este dentro 
              -empty funciona cuando el elemento esta vacio
              -checked revisa si algo esta chequeado y cambia. Por ejemplo si el checkbox de un formulario esta tildado.
              -link y -visited detecta cuando un link fue visitado o no y puede cambiar su estilo segun eso.
Se pueden ver muchas mas de esto en la pagina de "mdn pseudoclases".

**Pseudo-Elementos:** Se usa para especificar una parte del elemento, no todo el elemento. Ejemplo con las listas desordenadas, especificar que los puntos que figuran, hacer que desaparezcan.
              -market se puede usar para el ejemplo de las listas
              -first-letter seleccionamos que solo a la primer letra del texto haga x cosa
              -first-line solo modifica la primer linea del texto
              -placeholder seria para el texto que figuran de fondo en formularios y demas.
              -before y -after agregar algo antes o despues del elemento.

**Metodologia BEM:** Bloques, elementos y modificadores. Se puede usar para copiar partes de codigos que son iguales en 2 o mas elementos y que se repiten en la web, a su vez con esto genera que quede mas limpio, corto y sencillo el codigo. Eligiendo de una sola forma, cada parte.

Una cosa importante es el manejo de esta metodolo, por ejemplo en lo escrito, si tengo una lista con muchos items, en vez de a cada items agregar una clase, se puede colocar la clase del mismo nombre de ul y agregarle dos guiones bajos y el nombre item: lista__item. Con esto generamos que sea mas sencillo la forma de entender de donde vienen los elementos.

Ahora para marcar los elementos que van a tener algo diferente, se agregar ademas de lo ultimo, otro nombre de clase pero con dos guiones: lista__item item--xx
Cuando vayamos a css, solo debemos agregar todas las propiedades a la clase de lista__item. Y a los que van a tener algo diferente usamos la clase item--xx pero solo poniendo la caracteristica aparte, sin todo el mismo codigo.

**Display:** Esta funciona para definir de que manera de veran ciertos elementos juntos.
    -inline: seria uno al lado de otro, o sea en linea (aca, los estilos de margin, padding, height, no serian usados ya que rompe de cierta manera. Solo se pueden usar de forma horizontal).
    -block: queda uno por debajo del otro, en bloque (ocupa todo el ancho disponible y ademas el siguiente eleemnto, comienza como una linea nueva abajo)
    -inline-block: es la mezcla de ambos, se usa mucho en menus de navegacion. Con esto cada elemento esta al lado de otro, pero no ocupan todo el ancho, sino que cada uno es una cajita, pero unidos.
    -none: el elemento desaparece de la web a pesar de estar en el codigo, no ocupa espacio y los elemento adyacentes se destribuyen como si no estuviera.

**Posicion:** Posiciones de elementos. Sirve para apilamientos de elementos tambien.
    -Relative: se mantiene en su posicion, pero es posible moverla, para cada lado. Y ademas es punto de referencia para los demas elementos que sigan abajo. El lugar del elemento ocupa el mismo lugar siempre, pero puede estar movido. Si tenemos un elemento arriba y ajustamos su estilo, se pone por encima, ahora si la ajustamos para la que le sigue en el codigo, la caja figuraria por debajo. Para que en el elemento siguiente tambien quede por delante, se debe usar "z-index:10" el numero al final, cuanto mas grande sea mas adelante esta del otro elemento.

    -Absolute: El elemento en este caso no ocupa lugar, a pesar de seguir figurando en la web. Con esto, un elemento puede estar encima de otro, literalmente en el mismo lugar. Si le damos estilo, por ejemplo de margin top, left y demas, va a empezar desde el principio de la pagina, esto porque con Absolute, toma como referencia la etiqueta HTML, o sea el principio de la pagina. Si queremos que el elemento se mueva tomando otra referencia, debemos colocar position relative a su contenedor. De esa manera el elemento absolute, se mueve desde el elemento padre.

    -Fixed: Es parecido a absolute en algunas propiedades, pero la diferencia es que en fixed, no importa si su padre es relative o no, el elemento siempre va atomar como referencia la web. Otra diferencia es que siempre queda fija en la pagina a pesar de hacer scroll.

    -Sticky: Funciona como relative, pero cuando se agrega un estilo, por ejemplo de margin top, el elemento queda fijo, hasta que alcance ese estilo y ahi funciona como fixed, ya que al hacer scroll sigue bajando.

**Ventanas Modal:** Se usan para crear ventanas por encima de la pagina, puede ser con algun mensaje de advertencia y demas. A esto mismo se le puede colocar un "boton" y que se pueda cerrar.
Se puede configurar con javascript esa parte o sino con el elemento "dialog" que si luego la usamos en un form con el method=dialog, funciona para que se pueda cerrar.

**Transiciones:** Se usa idealmente directo en la caja del elemento, no en el hover. Ademas hay 3 propiedades, el nombre de lo que se va a cambiar, la duracion y el delay, o sea despues de cuanto tiempo va a empezar.

**Overflow:** Se define como se maneja el contenido si sobresale de su contenedor. Tien 4 valores:
    -visible: se va a ver a pesar de salir del contenido.
    -hidden: se va a ocultar la parte que sale del contenido. Pero reserva espacio para la barra de scroll. Mejor usar el valor "clip".
    -scroll: se genera la barra para subir y bajar y ver todo el contenido
    -auto: se ajusta para cuando sea necesario se muestra el scroll y sino no

**Object fit y pisition:** Se usan para imagenes y videos, con la idea de ajustar. Si al elemento ya le pusimos un ancho y alto predeterminado, podemos ajustarlo. Funciona como los background-image y sus valores.
    Object Fit:
      -contanin: queda la imagen al menos 1 vez ajusta en el total del elemento.
      -cover: se adapta a todo el elemento
      -none: la imagen se queda con su valor justo, sin hacer nada con los demas valores.
    
    Object Position: elegimos que posicion mostrar.

**Contorno:** Se basa en el espacio entre el borde y el margin. Por ejemplo en los formularios al elegirlo sucede ese contorno de espacio. Solo es algo visual que no ocupa espacio en la web.
Se le puede definir con 3 valores, "outline-width" "outline-color" "outline-style". Puede servir mucho para el hover, con la idea de que al pasar por encima, el elemento no se agrande, pero si tenga un distintivo.
Tambien en el ejemplo de los formularios, se puede sacar con para que no figure al hacer focus con "outline:none" pero esto se debe aplicar con "focus-visible", para que no afecte en la accesibilidad de la web (personas con discapacidad).

**Emmet:** Plugin de creacion de codigo para facilitarlo, con abreviacion. Esto sirve mucho para crear 1 sola vez, varias lineas del mismo codigo. Ejemplo crear muchos items con uno solo codigo.
Ejemplo: ul>li con eso cre el ul y el li directo. Si es ul>li>a esto genera el a de link directo dentro del li.
Otra forma es con el * que genera multiplicacion, es decir li*3, se generan 3 li directos.
Tambien se pueden colocar clases de forma directo. Con el . y nombre de la clase se crearian directo.
Una cosa a usar tambien son los snipper, que funciona para dejar marcado un tipo de abreviacion emmet que podemos usar en otros momentos, esto lo debemos guardar en un archio jason.

**Flexbox:** Un modelo de caja flexible, o sea adaptable para los elementos. Al contenedor principal, se le debe dar un estilo flex: display: flex.
Ahora otra cosa que es importante, seria los items flex, es decir los elementos que estan dentro del contenedor definir que sean flex, con esto es posible elegir la direccion de cada elemento, ademas de que sean responsive.
Tenemos:
    -flex-direction: con las opciones de row y row-reverse, con esto podesmos mezclar el orden de los elementos en cuanto a derecha a izquierda o de izquierda a derecha. Otra opcion es column, esto hace que cada elemento se genere en columnas uno abajo de otro y a su vez se puede usar el column-reverse que hace lo mismo pero al revez.

    -flex-wrap: genera que los elementos, bajen de linea, cuando ya no alcanzan en el ancho del navegador. Con esto mantienen su tamaño de px.

    -flex-flow: seria para juntar dos tipos de estilo, el de wrap o no wrap y el de direccion.

    -flex-grow: controla cuánto espacio adicional puede tomar un elemento flexible dentro de un contenedor, en proporción a los otros elementos flexibles. Si se le asigna un valor a flex-grow, el elemento puede crecer para llenar el espacio disponible en el contenedor.

    -flex-basis: tamaño minimo/base que un elemento se puede encoger, sino tiene que pasar para abajo.

**Alineacion:** estilos para alinear de cierta forma los elementos.
    -Justify-content: alinea los elementos en el eje horizontal. Se puede usar Start, end, center, space-between (el primer elemento va al principio, el ultimo va al final y los del medio se ajustan para que queden a la misma distancia entre ellos), space-around (cada elemento tiene una separacion igual, pero hay diferencias con el primero y el utlimo en cuanto a sus bordes), space-evenly (cada elemento tiene una separacion igual, incluso con los bordes).

    -Align-items: alinea los elementos en el eje vertical Sirve solo para cuando hay una linea de elementos. Se puede usar start (ocupan el alto del contenido nomas y figuran al principio), stretch (se estiran para ocupar todo el contenido padre), end, center, baseline(se alinea en base al elemento de dentro, es decir no al alto del elemento, sino a lo que hay dentro).

    -Align-content: alinea los elementos en el eje vertical. Los toma todos juntos sin dejar espacios entre si, mas que nada cuando hay varias lineas de elementos. Se puede usar los mismo estilos que con align-items.

    -Align-self: se usa para el elemento hijo y es para moverlo donde sea. Funciona si el elemento padre tiene asignado un align-items. Se usan los mismos estilos que los anteriores.

**Responsive:** 
    -Bloques Flexibles: Soluciones con max o min width, otra manera es a base de usar porcentaje de width.
    -Multimedia Flexibles: Seria importante (para imagenes) que se use su max-width, para que se agrande hasta el maximo de su resolucion y un height auto. Ahora para los videos es ideal agregarlo dentro de un contenedor, a ambos se le da un max-width de 100% y al padre un aspect-ratio: 16/9.

**Media-quary:** Es la forma de que ciertos estilos o elementos se ajusten si X cosa pasa. Ejemplo, si la pantalla es de Xpx o mas chica, pasa tal cosa con este elemento y demas. Se pueden usar varias condiciones, conectadas con el "and".
    -Print: Es decir al imprimir, podemos cambiar el estilo.
    -(max-width: 768px): Cuando el ancho maximo de la pantalla es de esos pixeles o menos, cambiar a tal cosa.
    -Screen: solo para cuando es pantalla la visualizacion.

















