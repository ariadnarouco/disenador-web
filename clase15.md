# Pautas de Accesibilidad al Contenido en la Web
Las Pautas de Accesibilidad al Contenido del W3C están compuestas de 14 pautas, que son los principios generales del diseño accesible:

#### Proporcione alternativas equivalentes para el contenido visual y auditivo.
Los textos alternativos al contenido visual o auditivo benefician a personas ciegas y/o sordas y a aquellos usuarios que deciden anular la descarga de imágenes y/o sonidos (velocidad de acceso a Internet limitada).
Los equivalentes no textuales, como pueden ser dibujos o vídeos, benefician a personas analfabetas o con dificultades en la lectura.

#### No se base sólo en el color.
Los textos y gráficos deben comprenderse sin necesidad de ver los colores. El cumplimiento de esta pauta beneficia a personas con dificultades para ver los colores y a usuarios que utilizan pantallas monocromáticas.

#### Utilice marcadores y hojas de estilo y hágalo apropiadamente.
El control de la presentación de los contenidos se debe realizar con hojas de estilo en vez de con elementos y atributos de presentación. Con el uso de marcadores de presentación los usuarios que utilizan software especializado tendrán dificultades para entender la estructura de la página.

#### Identifique el idioma usado.
Esta pauta implica usar marcadores que faciliten la pronunciación o interpretación de texto abreviado o extranjero. Se debe indicar el idioma predominante en cada página y marcar aquellas expresiones que se encuentren en otra lengua. De esta forma, los sintetizadores de voz son capaces de cambiar su pronunciación en función del idioma siempre y cuando se usen los marcadores apropiados.

#### Cree tablas que se transformen correctamente.
Las tablas sólo se utilizan para marcar información tabular (tablas de datos). El uso de tablas con otros fines crea dificultades para los usuarios que usan lectores de pantalla. De igual forma, las tablas mal estructuradas (por ejemplo, sin encabezados ```<th>```) dificultan la lectura a usuarios que no pueden visualizar la información de forma global: ciegos con lectores de pantalla y/o dispositivos braille, deficientes visuales que utilizan magnificadores de pantalla o usuarios con dispositivos de pantalla pequeña.

#### Asegúrese de que las páginas que incorporen nuevas tecnologías se transformen correctamente.
Una página basada en tecnologías modernas tiene que ser accesible al desconectarla o al visualizarla con navegadores antiguos. El usuario puede desconectar las tecnologías más modernas para ganar en rapidez de descarga. Sin embargo, los contenidos deben permanecer accesibles.

#### Asegure al usuario el control sobre los cambios de los contenidos tempo-dependientes.
El movimiento de los objetos o páginas, su parpadeo o actualización automática deben ser controlados por el usuario. Las personas con discapacidades cognitivas o visuales no pueden leer textos en movimiento. De forma similar, algunos discapacitados físicos no pueden interactuar con objetos móviles (limitaciones motrices).

#### Asegure la accesibilidad directa de las interfaces incrustadas.
Cuando un objeto incrustado (flash, applet) tiene su "propia interfaz", ésta (al igual que la interfaz de su navegador) debe ser accesible. Si la interfaz del objeto incrustado no puede hacerse accesible, debe proporcionarse una solución alternativa accesible.

#### Diseñe para la independencia del dispositivo.
Esta pauta significa que el usuario puede interactuar con la aplicación de usuario o el documento con un dispositivo de entrada (o salida) preferido - ratón, teclado, voz, puntero de cabeza (licornio) u otro. Si, por ejemplo, un control de formulario sólo puede ser activado con un ratón u otro dispositivo de apuntamiento, alguien que use la página sin verla, con entrada de voz, con teclado o quien utilice otro dispositivo de entrada que no sea de apuntamiento, no será capaz de utilizar el formulario.

#### Utilice soluciones provisionales.
Las alternativas accesibles sólo son imprescindibles hasta que los antiguos navegadores y las ayudas técnicas operen correctamente.

#### Utilice las tecnologías y pautas W3C.
Cuando no se pueda usar una tecnología W3C o al usarla se obtengan materiales que no se transformen correctamente, se debe proporcionar una versión alternativa. Se recomiendan las tecnologías W3C por incluir características accesibles incorporadas, estar desarrolladas en un proceso abierto consensuado y porque se utilizan como base para crear contenidos accesibles.

#### Proporcione información de contexto y orientación.
Esta información ayuda al usuario a comprender páginas o elementos complejos. Se deben agrupar los elementos y ofrecer información contextual sobre la relación entre elementos. Esta acción es fundamental para discapacitados cognitivos y visuales.

#### Proporcione mecanismos claros de navegación.
Estos mecanismos facilitan a todos los usuarios la búsqueda de aquella información que necesitan (fundamental para discapacitados cognitivos y visuales). Ejemplos: mapa web, ayuda, barras de navegación, etc.

#### Asegúrese de que los documentos sean claros y simples.
La utilización de lenguaje claro y simple facilita la comunicación de información. El acceso a la información escrita puede ser difícil para discapacitados cognitivos o con dificultad de aprendizaje y para personas sordas o que hablan en una lengua extranjera. La comprensión de un documento también depende de la maquetación de la página y de los gráficos (que deben llevar un texto alternativo).

# Elementos para desarrollar un sitio accesible

**Imágenes y animaciones**

Utilizar el atributo alt para describir la función de cada elemento visual. 

**Mapas de imagen**

Utilizar el elemento map y texto para las zonas activas.

**Multimedia**

Proporcionarle al usuario subtítulos con transcripción del sonido, y descripción del vídeo.

**Vínculos de hipertexto**

Usar texto que tenga sentido leído fuera de contexto. Por ejemplo, evitar "click aquí".

**Organización de las páginas**

Hacer uso de encabezados, listas y estructura consistente.

**Figuras y diagramas**

Describirlos brevemente en la pagina o emplear el atributo longdesc.

**Scripts, applets y plug-ins**

Ofrecer contenido alternativo si las funciones no son accesibles.

**Marcos**

Utilizar el elemento noframes y títulos con sentido. 

**Revisá tu trabajo**

Verificar el sitio utilizando las herramientas de validación de sitios web y estar al tanto de las pautas de [http://www.w3.org/TR/WCAG](http://www.w3.org/TR/WCAG).

Poder cumplir con los requerimientos para que nuestro sitio sea más accesible que otros nos evitará perder una cuota de usuarios que no tendrían acceso a él.

Además una web accesible será fácilmente indexada por los principales motores de búsqueda, lo cual es un punto muy a favor que tenemos en internet, estar mejor posicionados que la comeptencia.

Hay que emplear la mayor creatividad posible para crear un sitio de fácil usabilidad y por tanto, más intuitiva.

# Ejemplos

**Imágen**

```<img src="img/camp-2011-logo.gif" alt="Camp 2011">```

**Campos de texto**

<iframe height='268' scrolling='no' src='//codepen.io/team/coderhouse/embed/KdPpPm/?height=268&theme-id=14781&default-tab=html' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/team/coderhouse/pen/KdPpPm/'>Accesibilidad 17.3.1 - 1</a> by Coderhouse (<a href='http://codepen.io/coderhouse'>@coderhouse</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

<iframe height='268' scrolling='no' src='//codepen.io/team/coderhouse/embed/zvOGOj/?height=268&theme-id=14781&default-tab=html' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/team/coderhouse/pen/zvOGOj/'>Accesibilidad 17.3.1 - 2</a> by Coderhouse (<a href='http://codepen.io/coderhouse'>@coderhouse</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

# Crea títulos de página únicos y precisos




#### Indica los títulos de las páginas utilizando las etiquetas title



Una etiqueta title indica tanto a los usuarios como a los motores
de búsqueda el tema sobre el que trata una página. La etiqueta
`<title>` debe colocarse dentro de la etiqueta `<head>` en el
documento HTML. Lo ideal sería crear un título único para
cada página del sitio.

#### El contenido de la etiqueta title se muestra en los resultados de búsqueda

Si el documento aparece en una página de resultados de
búsqueda, el contenido de la etiqueta title, por lo general, aparece
en la primera línea de los resultados.

El título de tu página principal puede incluir el nombre de tu sitio web o negocio y podría incluir otra información importante, como
la ubicación física de la empresa o tal vez algunas de sus
principales actividades u ofertas.

#### Usa títulos descriptivos breves

 Los títulos pueden ser concisos pero informativos. Si el título es demasiado largo, Google mostrará tan solo una parte del mismo en el resultado de búsqueda.
 
 ## Utiliza la metaetiqueta description




#### Los textos pueden definirse para cada página



La metaetiqueta description de una página proporciona a Google y
a otros motores de búsqueda un resumen sobre la página.

Mientras que el título de una página contiene unas pocas
palabras, la metaetiqueta description podría contener un par de
frases o incluso un párrafo corto. Las Herramientas para
webmasters de Google disponen de un útil apartado de análisis de
contenido, que te informaría de cualquier metaetiqueta
description que fuera demasiado corta, larga o bien duplicada
(también dispones de esta misma información para las etiquetas
`<title>`). Al igual que la etiqueta `<title>`, la metaetiqueta
description se coloca dentro de la etiqueta `<head>` en el
documento HTML.

#### ¿Cuáles son las ventajas de las etiquetas meta de descripción?

Las metaetiquetas description son importantes ya que Google podría utilizarlas como fragmentos de descripción de tus páginas. Ten en cuenta que decimos “podría” porque Google podría optar por utilizar una parte relevante del texto visible de tu página si ésta concuerda con la consulta del usuario.

Agregar metaetiquetas description para cada una de tus páginas es siempre una buena práctica en caso de que Google no pueda encontrar un buen texto a utilizar como fragmento. Encontrarás una entrada sobre cómo mejorar los fragmentos con metaetiquetas description en el Blog para webmasters de Google.

Las palabras que aparecen en el fragmento están en negrita si coinciden con la consulta del usuario. Esto da pistas al usuario para saber si el contenido de la página coincide con lo que busca. 

A continuación hay otro ejemplo, esta vez mostrando un fragmento de una metaetiqueta description de una página interna (que idealmente tiene una metaetiqueta description única) que contiene un artículo.


#### Resume de forma precisa el contenido de la página

 Escribe una descripción que informe y a su vez cree interés en los usuarios en caso de que encuentren esa metaetiqueta description como fragmento de un resultado de búsqueda.

**Evita**

* una metaetiqueta description con contenido no relacionado con la página descripciones genéricas como “Esto es una página web” o “Página sobre cromos de béisbol”

* una descripción con sólo palabras clave 
copiar y pegar todo el contenido del documento en una metaetiqueta description.


#### Utiliza descripciones únicas para cada página

Tener una metaetiqueta diferente para cada página ayuda tanto a los usuarios como a Google, especialmente en búsquedas en las que los usuarios pueden obtener varias páginas de tu dominio (por ejemplo, búsquedas con el operador site:). Si tu sitio tiene miles o incluso millones de páginas, la elaboración de metaetiquetas description a mano no será factible. En este caso, se pueden generar automáticamente basándose en el contenido de cada página.

**Evita:** 
* Utilizar una única metaetiqueta description en todas las páginas de tu sitio o en un gran grupo de páginas de tu sitio.

# Mejorando la estructura de las url

#### URL sencillas sugieren el contenido de la página



Crear categorías descriptivas y nombres de archivo para los documentos de tu sitio web no sólo puede ayudar a mantener tu sitio web mejor organizado, sino que también podría facilitar el rastreo de tus documentos a los motores de búsqueda. Además, puede crear URL más sencillas de enlazar. Los usuarios que visitan tu sitio pueden sentirse intimidados por URL muy largas y raras, con pocas palabras reconocibles. URL de este tipo (1) pueden ser confusas. Sería difícil para los usuarios repetir la URL de memoria o enlazarla. Además, los usuarios pueden creer que una parte de la URL no es necesaria, sobre todo si la URL muestra muchos parámetros irreconocibles. Podrían dejar fuera una parte, rompiendo así el enlace. Algunos usuarios podrían enlazar a tu página utilizando la dirección URL de la página como texto ancla. Si la URL contiene palabras relevantes, se proporciona a los usuarios y a los motores de búsqueda información adicional sobre la página más allá del que daría un ID de sesión o un nombre de parámetro. (2)

#### Las URL se muestran en los resultados de búsqueda

Por último, recuerda que la URL de documento se muestra como parte de un resultado de búsqueda en Google, después del título del documento y del fragmento descriptivo. Al igual que el título y el fragmento, las palabras en la URL del resultado de búsqueda aparecerán en negrita si coinciden con la consulta del usuario. (3) A la derecha hay otro ejemplo que muestra una URL de nuestro dominio para una página que contiene un artículo sobre cromos de béisbol más buscados. Las palabras en una URL resultan más atractivas para los usuarios que opciones como “www. brandonsbaseballcards.com/articulo/102125/”. Google es bueno rastreando todo tipo de estructuras de URL, incluso si son muy complejas, pero crear URL lo más simple posible, tanto para los usuarios como para los motores de búsqueda, puede ser muy útil. Algunos webmasters reescriben las URL dinámicas como URL estáticas. Esto es un procedimiento avanzado y, si se hace incorrectamente, podría causar problemas.

#### Utiliza palabras en las URL

URL con palabras relevantes para el contenido y la estructura del sitio ayudan a que los usuarios que visitan tu sitio naveguen por él. Las recordarán mejor y podrían facilitar que enlacen a éstas.

Evita:
* URL largas con parámetros y números de identificación de sesión innecesarios nombres genéricos como “pagina1.html”
* El uso excesivo de palabras clave como “béisbol-cromos-beisbol-cromo-béisbolcromos.htm”

#### Crea una estructura de directorios simple

Utiliza una estructura de directorios que organice el contenido y facilite a los usuarios que visitan tu sitio el saber dónde están dentro de éste. Trata de usar la estructura de directorio para indicar el tipo de contenido que se encuentra en esa URL.

**Evita:**

* Anidar subdirectorios como “.../ dir1/dir2/dir3/dir4/dir5/dir6 /pagina.html”
nombres de directorios sin relación alguna con el contenido

#### Proporciona una versión de la URL para llegar a un documento

Para evitar que los usuarios enlacen a una versión de la URL y otros enlacen a otra versión diferente (esto podría dividir la reputación del contenido entre ambas URL), céntrate en usar y referenciar una URL en la estructura y en los enlaces internos de tus páginas. Si observas que los usuarios acceden al mismo contenido a través de varias URL, puedes crear un redireccionamiento 301 desde las URL no preferidas a la URL dominante. Además puedes usar la URL canónica o el elemento de enlace rel=“canonical” si no puedes redireccionar.

Evita
* Que páginas desde subdominios y desde el directorio raíz accedan al mismo contenido (por ejemplo, “dominio.com/pagina.htm” y “sub.dominio.com/pagina.htm”) utilizar mayúsculas innecesarias en las URL (muchos usuarios esperan URL en minúsculas y las recuerdan mejor).


### Facilita la navegación en tu sitio
La navegabilidad es muy importante para los motores de búsqueda. La navegabilidad de un sitio web es importante ya que ayuda a los usuarios a encontrar rápidamente el contenido que desean.

Además, puede ayudar a los motores de búsqueda a entender cuál es el contenido que los webmasters piensan que es importante. Y aunque los resultados de búsqueda de Google se ofrecen a nivel de página, a Google además le gusta saber el papel que juega una página dentro de un sitio web.

#### Planifica la navegación basándote en la página de inicio

Todos los sitios web tienen una página principal o una página raíz, que es la que normalmente más se visita de un sitio web, así como el punto de partida para muchos usuarios. A menos que tu sitio tenga sólo unas cuantas páginas, deberías pensar en cómo los usuarios irán de la página general (tu página raíz) a otra página que aloja un contenido más específico.

¿Tienes suficientes páginas sobre un determinado tema como para crear una página que las describa (p. ej. página raíz -> listado con los temas relacionados -> tema específico)?; ¿tienes cientos de productos que necesitan ser clasificados en varias categorías y subcategorías?

#### Asegúrate de utilizar los enlaces de navegación

Los enlaces de navegación son una línea de enlaces internos ubicados en la parte superior o inferior y que permite a los usuarios ir a secciones visitadas con anterioridad o a la página de inicio (1). Muchas de estas líneas tienen la página más general (normalmente la página de inicio) en primera posición y las secciones más específicas a la derecha.

#### Deja abierta la posibilidad de que una parte de la URL pueda ser eliminada

Piensa lo que puede ocurrir cuando un usuario quita parte de una de tus URL - Algunos usuarios podrían navegar por tu sitio web de formas muy raras y deberías anticiparte a esto. 

Por ejemplo, en lugar de usar los enlaces de navegación de la página, un usuario podría quitar parte de una URL para encontrar contenido más general. El o ella podría estar visitando http://www. brandonsbaseballcards.com/noticias/2010/eventos-béisbolcromos.htm, pero escribe http://www.brandonsbaseballcards.com/ noticias/2010/ en la barra de navegación, creyendo que esto le mostrará todas las noticias de 2010.

¿Está tu sitio web preparado para mostrar contenido cuando esto pase o ofrecerá un error 404 (“página no encontrada”) al usuario? ¿Qué tal si subes el nivel del directorio a http://www.brandonsbaseballcards.com/ noticias/?

#### Crea dos sitemaps: uno para los usuarios y otro para los motores de búsqueda

Un mapa del sitio es una página normal y corriente de nuestro sitio web en el que se muestra su estructura, y que normalmente consiste en una lista jerárquica de las páginas que lo conforman. Puede que los usuarios visiten esta página si no pueden encontrar alguna página determinada de nuestro sitio web, aunque puede que los motores de búsqueda también visiten esta página para una mejor indexación de las páginas del mismo.

Esta página se crea principalmente para los usuarios. Un archivo Sitemap XML, el cual puede enviarse a través de las Herramientas para webmasters de Google, facilita que Google encuentre las páginas de tu sitio web. 


Usar un archivo sitemap es además una forma de decirle a Google, aunque no de garantizar, qué versión de una URL prefieres como la principal (p. ej. http:// brandonsbaseballcards.com/ o http://www.brandonsbaseballcards. com/; más información en ¿Qué es un dominio preferido?).


Por otra parte, Google ayudó a crear la secuencia de comandos del generador de sitemaps, de código abierto, que a su vez te ayuda a crear tu archivo sitemap. Para aprender más sobre estos archivos, el Centro de asistencia para webmasters ofrece una guía de archivos sitemap, que te será útil.

### Practicas Recomendadas

#### Añade un mapa del sitio HTML al sitio web y usa un archivo sitemap XML

Un sencillo mapa del sitio con enlaces al resto de páginas o al menos a las más importantes (si tienes cientos o miles de ellas), puede ser muy útil. Crear un archivo sitemap XML de tu sitio web ayudará a asegurarse de que los motores de búsqueda encuentran las páginas de tu sitio web.

#### Crea una página 404 útil

Algunas veces los usuarios acceden, o bien porque siguen un enlace roto o bien porque escriben una URL errónea, a páginas que no existen en tu sitio web. Tener una página 404 personalizada que amablemente guíe a los usuarios a una página en funcionamiento puede mejorar en gran medida la experiencia del usuario. Tu página 404 podría tener un enlace a la página principal e incluso podría ofrecer una serie de enlaces a páginas populares o contenido relacionado de tu sitio web. Google ofrece un widget 404 que puedes incorporar a tu página 404 para reproducirlo automáticamente con muchas funciones útiles. Además puedes utilizar las Herramientas para webmasters para encontrar las razones de los errores de las URL que causan el “no encontrado”.

**Evita**

* Que tus páginas 404 sean indexadas por los motores de búsqueda (asegúrate de que tu servidor web esté configurado para dar un código 404 HTTP cuando se pidan páginas que no existen) 
* Ofrecer solo mensajes vagos como “No encontrado”, “404” o ni siquiera un 404 
* Usar un diseño para tus páginas 404 que no sea coherente con el diseño de tu sitio web

# Ofrece contenido y servicios de calidad

#### Sitios interesantes aumentarán su valor por si mismos


Crear contenido interesante y útil será probablemente lo que más influya en tu sitio web de todos los factores que tratamos aquí. Los usuarios reconocen buen contenido en cuanto lo ven y es probable que deseen compartirlo con otros usuarios.

Esto puede ser a través de una entrada en un blog, redes sociales, correo electrónico, foros u otros medios. El contenido orgánico o el boca a boca será lo que más ayude a crear tu reputación tanto con los usuarios como con Google, y esto rara vez ocurre sin un buen contenido.

#### Anticípate a la diferencia de conocimiento de tus usuarios sobre el tema que tratas y ofrece contenido único y exclusivo


Piensa en las palabras que un usuario podría utilizar en la búsqueda para encontrar tu contenido. Usuarios que saben mucho sobre el tema podrían utilizar diferentes palabras que otros a los que el tema les es nuevo. Por ejemplo, un seguidor del béisbol de toda la vida podría buscar por [nlcs], acrónimo de National League Champion Series. Mientras un nuevo fan utilizaría una búsqueda más general como [béisbol playoffs]. 

Anticiparse a estas diferencias en cómo los usuarios hacen las búsquedas y tenerlas en cuenta a la hora de escribir tu contenido (utilizando una buena mezcla de palabras claves) puede dar buenos resultados. Google Adwords ofrece una práctica herramienta, Herramienta para palabras claves, que te ayudará a descubrir nuevas variaciones de palabras claves y ver el volumen aproximado de búsquedas de cada una. 

Además, las Herramientas para webmasters de Google te ofrecen un ranking de búsquedas por las que tu sitio web aparece y las que generan más usuarios para tu sitio web.

Así que piensa bien en crear un servicio nuevo y útil que otros sitios no ofrezcan. Puedes además pensar en escribir un documento de investigación sobre el que no se haya tratado antes, ser el primero en publicar un noticia, o aprovechar la cantidad de usuarios únicos que posees. 

Otros sitios web podrían tener falta de recursos o experiencia en hacer algunas de estas cosas.

## Practicas Recomendadas

#### Escribe textos de fácil lectura

Los usuarios disfrutan de un contenido que está bien escrito y sea fácil de entender.

**Evita**

* escribir textos descuidados con muchos errores ortográficos y gramaticales. 
* incorporar texto en formato imagen cuando quieras que ese texto forme parte del contenido, ya que los usuarios podrían querer copiar y pegar el texto, y además los motores de búsqueda no pueden leerlo.

#### Céntrate en el tema

Siempre es beneficioso organizar el contenido de tal manera que el usuario tenga buena idea de dónde empieza, dónde termina un tema y dónde empieza el siguiente. Dividir tu contenido en fragmentos lógicos ayuda a los usuarios a encontrar lo que desean de una forma más rápida.

**Evita**
* poner una gran cantidad de texto que abarque varios temas en una misma página sin párrafos, encabezados o sin un diseño que los separe.

#### Crea contenido único y original

El contenido nuevo no sólo hará que los usuarios que ya tienes vuelvan a tu sitio web, sino que además atraerá nuevas visitas.

**Evita**
* rehacer (o copiar) contenido que ya existe, pues aportará muy poco valor añadido a los usuarios. 
* tener versiones duplicadas o muy parecidas en tu sitio web - más en contenido duplicado.

#### Crea contenido principalmente para los usuarios, no para los motores de búsqueda

Diseña tu sitio web según las necesidades de los usuarios y si además te aseguras de que tu sitio es accesible para los motores de búsqueda de forma sencilla, tendrás resultados muy buenos.

**Evita**

* Insertar una gran cantidad de palabras clave dirigidas a los motores de búsqueda, pero que no tienen sentido y son molestas para los usuarios 
* Tener bloques de texto tipo “errores ortográficos frecuentes usados para llegar a esta página” y que ofrecen poco valor a los usuarios 
* texto escondido para los usuarios, pero visible para los motores de búsqueda.

# Escribe textos ancla de mejor calidad


#### Buenos textos ancla transmiten mejor el contenido al que nos dirigimos.

El texto ancla es aquel texto en el que podemos hacer clic y que los usuarios ven como un enlace. Este está ubicado en la etiqueta ancla.

Este texto indica a los usuarios y a Google algo sobre la página a la que se enlaza. Los enlaces de tu página web puede que sean internos, es decir, que enlacen a otras páginas de tu sitio web, o salientes, que te llevan a contenido en otras páginas web. 

En ambos casos, cuanto mejor sea tu texto ancla, más fácil será para los usuarios moverse por tu página y más fácil será para Google entender de qué va la página a la que estás enlazando.

####Elige un texto descriptivo

El texto ancla que utilices para enlazar debe ofrecer al menos una idea general sobre lo que trata la página a la que está enlazando.

**Evita:**
* escribir texto ancla genérico como “página”, “artículo” o “haz clic aquí” 
* usar texto fuera de contexto o que no esté relacionado con la página a la que se enlaza 
* usar la URL de la página como texto ancla por regla general (aunque hay algunos usos legítimos, como cuando, por ejemplo, se quiere promocionar o hacer referencia a un nuevo sitio web)

#### Escribe textos concisos

Intenta redactar textos cortos y descriptivos, generalmente con varias palabras o una frase corta

**Evita**
* escribir texto ancla largo, como una frase larga o un párrafo corto.


#### Dale formato a los enlaces para que sean más fáciles de ver

Facilita a los usuarios la distinción del texto normal y el texto ancla de los enlaces. Tu contenido será menos útil si los usuarios no encuentran los enlaces o hacen clic por error.

**Evita** 
* usar CSS o un formato de texto que haga que los enlaces 
parezcan texto normal.

#### Utiliza el texto ancla también para los enlaces internos

Generalmente pensamos en los enlaces en términos de enlaces a páginas externas, pero si préstamos más atención al texto ancla que utilizamos para los enlaces internos esto podría ayudar a los usuarios y a Google a navegar mejor por tu sitio web.

**Evita**

* utilizar palabras clave de relleno de forma excesiva o muy largas sólo pensando en los motores de búsqueda. 
* crear enlaces innecesarios que no sirvan para que los usuarios naveguen por el sitio web

# Optimiza el uso de las imágenes

#### Utiliza el atributo “alt” para ofrecer información sobre las imágenes.

Las imágenes pueden parecer un componente muy sencillo de tu sitio web, pero puedes optimizar su uso. Todas las imágenes pueden tener un nombre de archivo definido y un atributo “alt”, de los cuales podemos aprovecharnos. El atributo “alt” te permite especificar texto que puede aparecer en vez de la imagen, si ésta no puede mostrarse por la razón que sea. 

¿Por qué utilizar este atributo? Si un usuario esta viendo tu página web con un navegador que no es compatible con las imágenes, o está utilizando tecnologías alternativas, como un lector de pantalla, el contenido del atributo “alt” ofrecerá información sobre la imagen. 

Otra razón es que si usamos una imagen como enlace, el texto en “alt” será tratado de forma similar a un texto ancla de un texto de enlace. Sin embargo, no recomendamos usar demasiadas imágenes como enlaces en tu barra de navegación, cuando los enlaces de texto pueden funcionar.

Por último, optimizar el nombre de archivo de tus imágenes y el texto en “alt” hace más sencillo entender tus imágenes para proyectos de búsqueda de imágenes como Búsqueda de imágenes de Google.


#### Guarda los archivos en directorios especializados y trabaja con ellos utilizando formatos de archivos estándar

En lugar de tener archivos de imágenes guardados en diferentes directorios y subdirectorios de tu dominio, plantéate reagrupar tus imágenes en un solo directorio (ej:. brandonsbaseballcards.com/ imagenes/).

Esto simplifica la ruta de tus imágenes. Usa archivos que estén ampliamente aceptados – La mayoría de navegadores soportan los formatos de imágenes JPEG, GIF, PNG y BMP. Es además una buena idea que la extensión que aparece en el nombre de tus archivos coincida con el tipo del mismo.


### Practicas Recomendadas


#### Usa nombres de archivo y texto en “alt” breves pero descriptivos.

Como en cualquier otra parte de la página que puede ser optimizada, los nombres de archivo y el texto en “alt” (para lenguajes ASCII) funcionan mejor cuando son cortos y descriptivos.

**Evita:**
* usar nombres genéricos como “imagen1.jpg”, “pic.gif” o “1.jpg” cuando sea posible (algunos sitios web con miles de imágenes pueden decidir darles los nombres a las imágenes de forma automática) 
* escribir nombres de archivos muy largos 
* llenar el atributo “alt” con muchas palabras clave o copiar y pegar frases enteras


####Ofrece texto en “alt” cuando utilizas las imágenes como enlaces

Si decides utilizar una imagen como un enlace, rellenar el texto en “alt” ayudará a Google a entender más sobre la página a la que estás enlazando. Imagina que estás escribiendo el texto ancla para un enlace de texto.

**Evita**

* escribir textos largos en “alt” que puedan ser considerados como spam 
* utilizar solo enlaces en imágenes para navegar por tu página


#### Ofrece un archivo Sitemap de imágenes

Un archivo Sitemap de imágenes puede ofrecer a Googlebot más información sobre las imágenes que se encuentran en tu sitio web. La estructura es similar al archivo de Sitemap XML de tus páginas web.

# Utiliza las etiquetas de cabecera de forma apropiada


Las etiquetas de cabecera (no confundir con la etiqueta HMTL o las cabeceras HTTP) se usan para presentar la estructura de la página a los usuarios. Estas etiquetas tienen seis tamaños, comenzando con el más importante, y terminando con el menos importante.

Ya que las etiquetas normalmente hacen más grande el texto que contienen que el del resto de la página, ésta se convierte en una pista visual para los usuarios sobre la importancia de ese texto y puede ayudarles a entender sobre el tipo de contenido que hay debajo del mismo.

Los diferentes tamaños de cabeceras se utilizan para crear una estructura jerárquica de tu contenido, haciendo más fácil a los usuarios navegar por el documento.

## Practicas Recomendadas

#### Imagina que estás escribiendo un esquema 

Esto es parecido a escribir un esquema para un gran proyecto. Piensa sobre papel cuáles son los puntos principales y los secundarios del contenido y luego decide dónde usar las etiquetas de cabecera de forma apropiada

**Evita:**
* Colocar texto en las etiquetas de cabecera que no ayudaría a definir la estructura de la página. 
* Usar las etiquetas de cabecera cuando otras etiquetas como y puedan ser más adecuadas cambiar de un tamaño de cabecera a otro sin ninguna lógica.


#### Usa las etiquetas de cabecera con moderación

Usa las etiquetas de cabecera cuando tenga sentido. Demasiadas etiquetas de cabecera en una página pueden hacer que los usuarios encuentren difícil de entender el contenido y ver dónde termina un tema y empieza el siguiente.

**Evita**

* El uso excesivo de las etiquetas de cabecera en las páginas. 
* Poner todo el texto de una página en una etiqueta de cabecera 
* Usar las etiquetas de cabecera para darle formato a un texto y no para presentar la estructura de la página.

# Haz un uso efectivo del robots.txt


#### Restingir a los rastreadores (bots) donde no sea necesario con el robots.txt

El archivo “robots.txt” les dice a los motores de búsqueda a qué partes de tu sitio pueden acceder y consecuentemente rastrear. Este archivo se debe llamar “robots.txt”, y tiene que estar en el directorio raíz de tu sitio. 

Puede que haya algunas páginas de tu sitio que no quieras que sean rastreadas si no van a ser útiles para los usuarios cuando las encuentren en los resultados de búsqueda. 

Si quieres evitar que los motores de búsqueda rastreen tus páginas, las Herramientas para webmasters de Google tienen un sencillo generador de robots. txt para ayudarte a crear el archivo.

Hay que tener en cuenta que si tu sitio usa subdominios y quieres que algunas páginas no sean rastreadas para ese subdominio, tendrás que crear un archivo robots.txt específico de ese subdominio. Para más información sobre robots.txt, te recomendamos esta guía del Centro de asistencia: cómo usar los archivos robots.txt.

 Hay unas cuantas maneras más de impedir que tu contenido aparezca en los resultados de búsqueda, como por ejemplo añadir la metaetiqueta “NOINDEX”, usar .htaccess para proteger directorios con contraseña.
 
 ### Practicas Recomendas

#### Usa métodos más seguros para el contenido delicado

No deberías quedarte tranquilo bloqueando solo con robots.txt material delicado o confidencial. 

Una de las razones es porque los motores de búsqueda aún podrían hacer referencia a esas URL que están bloqueadas (mostrando solamente la URL, sin título ni descripción) si hay enlaces a esas URL en alguna parte de Internet (registro de remitentes - referrer logs-).

Además, los motores de búsqueda que no siguen las normas de Robots Exclusion Standard podrían desobedecer las instrucciones de tu robots.txt. 

Por último, un usuario curioso podría estudiar los directorios y subdominios en tu robots.txt y adivinar la URL del contenido que no quieres que sea visto. Hay alternativas más seguras como encriptar el contenido o protegerlo con una contraseña en .htaccess.

**Evita**

* Permitir rastrear páginas de resultados de búsqueda muy parecidas - a los usuarios no les gusta salir de una 
* Página de resultados de búsqueda para llegar a otra que no añade ningún valor. 
* Permitir rastrear URL creadas como resultado de servicios de proxy.

# Ten en cuenta rel=“nofollow” para los enlaces

#### Combatir los comentarios spam con “nofollow”

Establecer el valor del atributo “rel” de un enlace a “nofollow” le dice a Google que algunos enlaces de tu sitio no deben seguirse ni pasar la reputación de tu sitio a las páginas con las que enlazas. Poner “nofollow” a un enlace se consigue usando rel=“nofollow” dentro de la etiqueta de ancla. 

¿Para qué puede servir esto? Si tu sitio tiene un blog con los comentarios públicos activados, los enlaces de esos comentarios pueden pasar tu credibilidad a páginas con las que no te sentirías cómodo enlazando tú mismo. Las páginas de comentarios en blogs son muy susceptibles de recibir comentarios spam. 

Usar nofollow en estos enlaces añadidos por los usuarios te asegura que no estás dando parte de tu muy lograda reputación a un sitio de spam. 

#### Añade de forma automática “nofollow” a las columnas de comentarios y a los tablones de mensajes

Muchos paquetes de software para blogs añaden automáticamente este atributo a comentarios de usuario, pero incluso es muy probable que se pueda añadir esta configuración manualmente a aquellos enlaces que no lo hacen. Este consejo también hace referencia a cualquier parte de tu sitio que acepte contenido generado por usuarios, como libros de visita, foros, etc. Si estás dispuesto a dar crédito a los enlaces añadidos por terceros (por ejemplo, si confías en algún usuario de tu sitio), entonces no hace falta usar nofollow en los enlaces. De todas maneras, enlazar a sitios que Google considera spam puede afectar a la reputación de tu sitio. El Centro de asistencia para webmasters tiene más consejos sobre cómo evitar comentarios spam, como por ejemplo usar CAPTCHA (imágenes distorsionadas o letras encriptadas) y activar la moderación de comentarios.

#### Usar “nofollow” para páginas individuales, todo el dominio, etc.

También puedes usar nofollow cuando estés escribiendo contenido para tu sitio y quieras hacer referencia a otra página web, pero sin comentar su credibilidad. 

Por ejemplo, imagina que estás escribiendo una entrada sobre los comentarios de spam y quieres mencionar un sitio que hace poco puso comentarios de spam en tu blog. Quieres advertir a los demás de lo que hacen en ese sitio, así que incluyes un enlace en tu texto, pero obviamente no quieres darle crédito con tu enlace. Este sería un buen uso de nofollow.

Por último, si te interesa poner nofollow en todos los enlaces de una página, puedes usar “nofollow” en la metaetiqueta “robots”, que se incluye en la etiqueta del código HTML de esa página.

# SEO para teléfonos móviles

## Comprueba si tu web está optimizada para Google
Como complemento a la campaña que Google está haciendo para concienciarnos de que optimicemos nuestra web para dispositivos móviles, el buscador ha lanzado una herramienta con la que saber si nuestra web está optimizada para móviles y si no lo está nos da recomendaciones para adaptarla. Puedes utilizar la herramienta desde el siguiente enlace: https://www.google.com/webmasters/tools/mobile-friendly/

## Completa la optimización con los consejos de  Pagespeed para móviles
<a href=https://developers.google.com/speed/pagespeed/insights/ target=blank>Pagespeed</a> es una magnífica herramienta de Google que nos ayuda a optimizar nuestras webs tanto en la versión ordenador como en la versión móvil. Para optimizar nuestra web para dispositivos móviles debemos corregir los errores que nos encontremos en la versión móvil de Pagespeed.

## Mejor  una web responsive que una versión móvil de tu web
Para Google es mejor una web responsive que crear una versión móvil de tu web.  Con la versión responsive sólo tendremos una web y esta se adaptará a todos los dispositivos donde se muestre, mientras que si tenemos una versión móvil en realidad tendremos dos webs, una para ordenadores y otra para dispositivos móviles. Aunque lo ideal es tener una web responsive,  no siempre es posible porque en muchos casos supone volver a maquetar y programar el sitio web y esto puede ser costoso.  Hay que valorar cual de las dos opciones nos conviene más para nuestro sitio.

## Crea un sitemap distinto para la versión móvil de tu web
Si utilizas la opción de una versión móvil tienes que crear un sitemap distinto para la versión de ordenador y la versión para dispositivos móviles.

## Evita tecnología que no funcione en los dispositivos móviles
Ten cuidado sobre todo con javascripts, videos o sliders que pueden no verse bien en móviles y que pueden ralentizar la carga de la web.

## Adapta el tamaño de  los title y las metadescripciones
Debes adaptar  los title  y metadescripciones al tamaño de los resultados de búsqueda de Google. Los title no pueden tener más de 60 caracteres y las descripciones no más de 100.

## Vigila la velocidad de carga
En la versión móvil es fundamental. Tienes que controlar sobre todo el peso de las imágenes. Cuanto más rápida cargue tu web mejor para el visitante y para posicionarnos.

## Implementar la etiqueta “canonical” y “alternate media”
Para evitar que Google posicione tu web móvil por encima de la versión de escritorio tienes que implementar de manera correcta las meta-etiquetas “rel=canonical” y “rel=alternate media” tanto en la versión móvil como en la de escritorio. Además implementar ambas etiquetas consolidara la autoridad de ambas páginas y sus enlaces.

La meta-etiqueta ```rel=canonical``` la tienes que implementar en todas las páginas de la versión móvil apuntado a sus respectivas páginas en la versión de escritorio. Este sería un ejemplo:

```
<link rel="canonical" href="http://www.ejemplo.com/versión-de-escritorio/página-de-ejemplo/" />
```

Al contrario que la anterior, la meta-etiqueta ```rel=alternate media``` tienes que implementarla en la versión de escritorio, solo tiene una peculiaridad, hay que indicar cuál será el tamaño maximo en el que se va a mostrar la versión móvil, tal que así:

```
<link rel="alternate" media="only screen and (max-width:640px)" href="http://m.ejemplo.com/página-de-ejemplo/" />
```

# Guía con precisión a los usuarios de móviles

#### Implementando versiones para ordenador y móviles de un sitio web

Uno de los problemas más comunes para los webmasters que poseen a la vez versiones de un sitio web para dispositivos móviles y para ordenador, es que los usuarios que utilizan el ordenador vean la versión para móviles o que los usuarios que acceden a través de un dispositivo móvil vean la versión para ordenador. Aquí tienes dos opciones viables para tratar con esta situación:


#### Redirige a los usuarios de móviles hacia la versión correcta

Cuando un usuario de móvil o un rastreador (como GooglebotMobile) accede a la versión de una URL para ordenador, puedes redirigirlos hacia la versión correspondiente de la misma página para móviles. Google advierte la relación entre las dos versiones de la URL y muestra la versión estándar para las búsquedas realizadas desde un ordenador y la versión para móviles cuando las búsquedas se realizan desde un dispositivo móvil. Si redireccionas a los usuarios, comprueba que el contenido en las URL para móviles/ordenador sea lo más parecido posible. 

Por ejemplo, si tienes un sitio de compras y se produce un acceso a la versión de una URL para ordenador desde un teléfono móvil, asegúrate de que el usuario es redireccionado hacia la versión para móviles de la página para el mismo producto y no hacia la página principal de la versión del sitio para móviles. 

De vez en cuando se encuentran sitios que utilizan este tipo de redireccionamiento en un intento por mejorar su clasificación en las búsquedas, pero esta práctica sólo perjudica a los usuarios por lo que se debería evitar a toda costa. Por otra parte, cuando se produce un acceso a una versión de una URL para móviles por parte de un navegador de un ordenador o por parte del robot de Google, no es necesario redirigirlos hacia la versión para ordenador.

Por ejemplo, Google no redirecciona automáticamente a los usuarios de ordenador desde su sitio para móviles hacia su sitio para ordenadores. En lugar de esto, existe un enlace que va de la versión para móviles hacia la versión para ordenadores.

Estos enlaces son especialmente útiles cuando el sitio para móviles no dispone de todas las funcionalidades de la versión para ordenadores. Si lo prefieren, los usuarios pueden navegar fácilmente hasta la versión para ordenadores.

#### Cambia el contenido en función del User-agent

En algunos sitios se utiliza la misma URL tanto para el contenido destinado a ordenadores como para el contenido destinado a móviles, pero su formato cambia en función del User-agent. En otras palabras, los usuarios de móviles y de ordenadores acceden a la misma URL (es decir, no se utilizan redireccionamientos), pero el contenido/formato cambia ligeramente dependiendo del User-agent. 

En este caso, la misma URL aparecerá tanto en la búsqueda para móviles como en la búsqueda para ordenador, y los usuarios de ordenador podrán ver una versión del contenido para ordenador, mientras que los usuarios de móvil podrán ver la versión para móviles del mismo. 

Sin embargo, ten en cuenta que si tu sitio web no se configura correctamente, éste podría incurrir en encubrimiento, lo que podría dar lugar a que el sitio web desapareciese de los resultados de búsqueda. 

El encubrimiento se refiere a un intento de mejorar la clasificación en los resultados de búsqueda mostrando contenidos distintos para el robot de Google y para los usuarios convencionales. Esto causa problemas tales como la aparición de resultados menos relevantes (las páginas aparecen en los resultados de búsqueda aunque su contenido realmente no esté relacionado con aquello que los usuarios ven/desean).

Por este motivo, nos tomamos el encubrimiento muy en serio. Entonces, ¿qué significa “la página que ve el usuario” cuando proporcionas dos versiones en una URL?

Como se explicaba en una entrada anterior, Google utiliza el robot de Google, “Googlebot”, para las búsquedas en la Web y el robot de Google para móviles, “Googlebot-Mobile”, para la búsqueda para móviles. Para mantenerte dentro de las directrices de Google, deberías mostrar al robot de Google el mismo contenido que vería un usuario cualquiera de ordenador, y al robot de Google para móviles lo mismo que se vería en el navegador de un dispositivo móvil convencional.

Está bien que los contenidos para el robot de Google sean distintos de los destinados al robot de Google para móviles. Un ejemplo de cómo se podría detectar tu sitio web como encubrimiento por error sería si tu sitio web devolviese un mensaje como “Por favor, accede desde un teléfono móvil” a los usuarios de ordenador, pero después devolviera la versión completa para móviles a ambos rastreadores (de forma que Googlebot recibe la versión para móviles). 

En este caso, la página que ven los usuarios que buscan en la web (por ejemplo, “Por favor, accede desde un teléfono móvil”) es distinta de la que Googlebot rastrea (por ejemplo, “Bienvenido a mi sitio”). 

De nuevo, se detecta encubrimiento ya que se quiere mostrar a los usuarios el mismo contenido relevante que los robots de Google, Googlebot o Googlebot-Mobile, rastrean.

# Promociona tu sitio de manera correcta

#### Aumenta el número de enlaces entrantes con la intención de añadir valor a tu sitio web

Aunque la mayoría de los enlaces hacia tu sitio llegarán gradualmente a medida que la gente descubra tu contenido mediante búsquedas u otras fuentes y enlacen a tu página, Google entiende que quieras dar a conocer todo el esfuerzo que has puesto en tu contenido. La promoción efectiva de nuevo contenido tiene como consecuencia una más rápida difusión de tu trabajo hacia aquellos que estén interesados en el tema. Como en la mayoría de los puntos tratados en este documento, llevar estas recomendaciones a los extremos podría incluso dañar el prestigio de tu sitio.

#### Cómo enviar avisos a través de blogs y ser reconocidos online

Para dar a conocer nuevos servicios o contenido que tengas en tu sitio, una muy buena idea es escribir un artículo sobre ello en tu propio blog. Otros webmasters que siguen tu sitio o están suscritos con un feed RSS también se enterarán. Poner un poco de esfuerzo en la promoción fuera de Internet puede ser muy provechoso también. Por ejemplo, si tienes un sitio web para tu negocio, asegúrate de que la URL aparezca en las tarjetas de presentación, la cabecera de tus cartas, etc. También puedes enviar a tus clientes boletines informativos periódicos para darles a conocer nuevo contenido en la página de la compañía. Si diriges un negocio de ámbito local, añadir la información de éste a Google Places te ayudará a contactar con clientes en Google Maps y la búsqueda web. El Centro de asistencia para webmasters cuenta con más información para promocionar tu negocio.

### Practicas Recomendadas

#### Conoce los sitios de redes sociales

Hay sitios que se han construido sobre la base de la interacción entre usuarios y que han permitido poner en contacto a gente interesada en ciertos temas con contenido relevante.

**Evita**
* Promocionar cada pequeña adición que hagas; hazlo sólo para cosas más grandes e interesantes 
* Involucrarte en programas donde tu contenido se promociona artificialmente

#### Intenta llegar a los que estén en una comunidad cercana a la tuya

Hay muchas probabilidades de que haya sitios que hablan de los mismos temas que tú. Establecer vías de comunicación con estos sitios suele ser beneficioso. Los temas de actualidad que aparecen en tu comunidad pueden darte ideas para escribir contenido o hacer una recopilación de recursos útiles.

**Evita:**
* Enviar peticiones masivas (spam) a todos los sitios que comparten tu temática 
* Comprar enlaces de otro sitio con el objetivo de aumentar tu PageRank en vez del tráfico.

# Introducción

El dominio en Internet, es la dirección que ingresamos en el navegador para acceder al sitio web deseado.

Ej: [www.css-tricks.com](http://www.css-tricks.com)

## Dominios de nivel superior

Los dominios de nivel superior (TLD, de sus siglas en inglés Top Level Domain) son el nivel más alto en la jerarquía de nombres en Internet, por ejemplo en ```www.ejemplo.com``` el dominio de nivel superior es .com.

La administración de estos dominios de nivel superior se lleva a cabo por la organización llamada ICANN que son las siglas de Internet Corporation for Assigned Names and Numbers.

## Dominios de internet genéricos

El dominio de Internet genérico (gLTD por sus siglas en inglés de generic top-level domain) es una sub-categoría de dominio de nivel superior (TLD), y es responsabilidad de la IANA (Internet Assigned Numbers Authority), el cual es un departamento más dentro de ICANN.

Los principales dominios de Internet genéricos más conocidos son **.com**, **.net**, **.org** y **.info**. Otros dominios como **.biz**, **.name** y **.pro** son asignados únicamente a organizaciones que demuestren su hecho. Ej: para registrar un dominio **.pro** se debe demostrar que el registrante es un profesional.

Existen tres clasificaciones de dominios de Internet genéricos:

* **No restringidos**: Son dominios disponibles para ser usados por cualquier organización o persona, sin restricción en cuanto al uso que se le dará (**.com**, **.net**, etc).
* **Patrocinados**: Son dominios que proponen diferentes empresas para establecer una regla de uso específico. Ej: **.tel** (para compañías de telefonía), **.edu** (Educación), etc.
* **Geográficos**: Son los que identifican al territorio geográfico, geopolítico o lingüístico. Ej: **.ar** (Argentina), **.be** (Bélgica), **.fr** (Francia), etc.

## Registro de dominios

Para poder disponer del dominio debemos registrarlo bajo nuestro nombre o el nombre de la empresa. Dependiendo el tipo de dominio que se quiera registrar serán diferentes los requerimientos y pasos a seguir.

**Registro de dominios en Argentina**

La entidad registrante de dominios de internet en Argentina es NIC.AR ([www.nic.ar](http://www.nic.ar)).

Para registrar un dominio, es necesario ingresar al sitio web, crearse un usuario, consultar por el dominio deseado y luego seguir los pasos para finalizar el registro. Actualmente (año 2015) se abona un costo anual de $160. Ej: [www.mercadolibre.com.ar](http://www.mercadolibre.com.ar). 

Para registrar un dominio **.com** se hace un trámite muy similar pero a través de otra entidad de registro de dominios .com. Ej: [www.godaddy.com](http://www.godaddy.com). Éste es uno de los sitios que se pueden utilizar.

# Introducción

El alojamiento web es el servicio que el servidor le provee al desarrollador web para poder almacenar archivos de código (html, css, js, php, etc), imágenes, vídeo, o cualquier contenido accesible vía web.

Al alojar los archivos en un servidor, tenemos la posibilidad de acceder a los mismos introduciendo una url específica en el navegador.

## Planes de hosting

Como todos sabemos, cada sitio web es diferente, acceden distintas cantidades de usuarios, ocupan diferente espacio en disco, etc. Por lo tanto es necesario contratar un servicio de hosting que cubra con los requerimientos de nuestra web.

Los servidores son empresas que almacenan computadoras con discos rígidos (en donde son alojados los sitios web), y cada una está equipada con distinto hardware. Esto, entre otros detalles técnicos, permite brindar distintos planes en los que difieren el espacio en disco, la memoria de los CPU, las cantidad de casillas de mail que se puedan crear, el ancho de banda que se le asignará al sitio, etc. Estos planes tienen un valor asignado que puede ser abonado de forma mensual o anual.

A continuación se muestra un ejemplo de uno de los servidores más conocidos del mercado:

![](https://coderhouse.gitbooks.io/clase-13-fundamentos/content/Captura%20de%20pantalla%202015-10-08%2017.24.58.png)

## Alojar sitio web en el servidor contratado

Una vez que elegimos el plan adecuado para nuestro sitio web recibiremos toda la información necesaria para poder subir los archivos al servidor y visualizar nuestra web finalmente online. Para realizar la subida de todos los archivos existen distintos métodos, el más común y generalmente más simple es a través de un cliente FTP.
 
Para elegir correctamente el plan podemos asesorarnos con el soporte técnico del hosting, que nos pedirá una serie de datos referidos a nuestro sistema web para poder darnos su opinión.

## Hosting y dominio (DNS)

Teniendo en claro lo que es un dominio en Internet, nos falta el paso de relacionarlo con el servidor que hemos contratado, donde se encuentran los archivos que forman el sitio web. Para esto, tenemos que informarle a la entidad registrante del dominio cual son los DNS de nuestro servidor.

La principal tarea de un servidor de DNS es traducir el nombre del dominio ([www.coderhouse.com](http://www.coderhouse.com)) en una dirección IP. 

Las direcciones IP (Internet Protocol) constan de un número único e irrepetible con el cual se identifica una computadora conectada a una red que corre el protocolo IP. Ésta computadora es la que nos brinda el servidor para alojar nuestro sitio.

Una dirección IP es un conjunto de cuatro números del 0 al 255 separados por puntos. Ej: la IP de coderhouse.com es: 184.107.100.88.

Para asignar los DNS al dominio debemos acceder al panel de la cuenta que hemos creado en la entidad registrante de dominios, buscar la opción de “Delegación de dominio”, o “DNS” (su nombre puede variar), y asignamos 2 o 3 de los DNS que figuren en el email que nos envió el servidor tras haber contratado el servicio de hosting. 

Por lo general una dirección DNS suele ser como en el siguiente ejemplo: ns1.panelboxmanager.com, ns2.panelboxmanager.com, ns3.panelboxmanager.com.

## Soporte técnico

Todos los servidores brindan soporte para sus clientes, con la finalidad de brindar un servicio estable y seguro. Los métodos más comunes son a través de un chat online, asistencia telefónica, un sistema de tickets, etc. Éste último está disponible en el panel de control, una vez que ya tengamos creada nuestra cuenta en el sitio del hosting. 

Ej: Se crea un ticket, en donde escribimos nuestra consulta, y luego recibimos la respuesta por parte de un asistente técnico del servidor. Esto simularía una conversación o un intercambio de emails).

## Alojamiento gratuito

Existen servicios de host gratuitos pero no son recomendables ya que no brindan un servicio a nivel profesional, solo puede servirnos para realizar alguna prueba.

# Introducción

Ya hemos aprendido cómo confeccionar correctamente un formulario en html. Lo que veremos en este capítulo será cómo enviar los datos del formulario por mail a una casilla de correos.

## Conexión

Para establecer la conexión correspondiente con el servidor, necesitamos autenticarnos con tres datos esenciales provistos por el servicio de hosting que hayamos contratado previamente: dirección de host, usuario y contraseña.

Para eso debemos abrir el Gestor de sitios:

![](https://coderhouse.gitbooks.io/clase-13-fundamentos/content/Captura%20de%20pantalla%202015-10-08%2017.39.34.png)

En esta imagen se puede ver que se creó un sitio llamado Coderhouse y se completaron los campos Servidor, Usuario y Contraseña. Luego al presionar Conectar pasamos a visualizar la estructura de directorios tanto del entorno local (izquierda) como del servidor remoto (derecha).

![](https://coderhouse.gitbooks.io/clase-13-fundamentos/content/Captura%20de%20pantalla%202015-10-08%2017.39.43.png)

De esta forma se visualiza el Sitio local y el Sitio remoto. Haciendo click derecho sobre los archivos podemos ver las distintas opciones para manipularlos (Subir, Descargar, Borrar, Crear Directorio, etc).

## Directorio raíz

Siempre que nos conectemos a un servidor vamos acceder al directorio raíz del mismo. En donde podemos encontrar una serie de carpetas que van a variar dependiendo del hosting que estamos utilizando.

Entre las carpetas que se listen, debemos identificar el directorio indicado para subir los archivos de nuestro sitio web. Esto también varía según el servidor, los nombres más comunes pueden ser: **public_html**, **htdocs**, **var**, **www**. De no estar seguros cuál es el directorio indicado, podemos consultarle al soporte técnico del hosting.

# Tips para un programador web

A continuación te detallamos algunos tips que todo programador debe tener en cuenta siempre!

**Comentar el código**

Es importante comentar el código en los lenguajes que estemos utilizando. En los estilos, en los códigos en Javascript, en los elementos ubicados en el html, etc. 

Esto nos facilitará la tarea a la hora de retomar el proyecto por algun cambio o actualización que nos haya pedido el cliente.

Otro ejemplo, que pasa muy seguido, es que el código que hemos desarrollado, sea consultado por otro programador, integrante del equipo de trabajo, un programador contratado por el cliente, o incluso uno mísmo si pasó mucho tiempo ya no recuerda los detalles.

**Código limpio**

Siempre hay que recordar que debemos separar el contenido html con imágenes y texto, de los estilos del diseño en archivos diferentes. Para eso siempre será necesario linkear un archivo estilos.css al html que hayamos creado. Esto permite trabajar de manera ordenada y eficiente.

**Análisis y síntesis**

Por lo general los tiempos para los desarrollos son ajustados, pero no debemos dejar de tener en cuenta que una vez que desarrollamos un script, podemos tomarnos unos minutos extra para corroborar que el código es óptimo.

En muchos casos un código que se repite muchas veces, se puede pensar un poco más y crear una función que al recibir parámetros cambie su comportamiento y nos arroje los resultados esperados.

**Google**

Generalmente todo empieza aquí. Nunca dudes en preguntar, no solo a tus colegas sino también a los motores de búsqueda. Un consejo que siempre aplico es “a alguien ya le pasó el error que te está ocurriendo en tu sitio!”. Y por lo general probando distintos términos de búsqueda terminarás encontrando la solución.

**Opinión de colegas**

Es muy importante que te mantengas rodeado de un buen equipo de trabajo o colegas. Siempre se aprende del que se tiene al lado, a veces aprendes qué hacer y otras qué no hacer!

Si tiene la oportunidad de consultarle a tus colegas acerca del código que has desarrollado, siempre es bueno tener una segunda opinión que podrá sin dudas optimizar o detectar algún punto débil en el funcionamiento. O quizás simplemente puedes ayudarlo a él en algo que esté haciendo, y te sirve a vos también para aprender.

**Trabajo en equipo y Técnicas de comunicación**

Para poder cumplir los objetivos de un proyecto es importante saber comunicarse con el resto de los que formen parte. Como el cliente, el diseñador, el administrador de la cuenta, un asistente, etc. Por lo tanto, nunca está demas preocuparse por aprender a transmitir de manera decuada el mensaje que queremos dar. De esta manera los demás podrán entender las necesidades que tenemos para poder llevar a cabo eficientemente nuestro trabajo.

**Mantenerse actualizado**

En internet siempre todo avanza constantemente. Las tecnologías cambian, las empresas de desarrollo de software, los celulares, las computadoras, etc. Es necesario estar al día de las tecnologías actuales para poder aplicarlas y poder brindar una solución actualizada del producto. Esto le permitirá al cliente estar a la altura de la competencia y así facilitar su estrategia de comunicación.

**Estudiar**

No dudes en leer un párrafo acerca de un código, una librería, una tendencia, un slider, etc. Para estar al día es necesario ver videotutoriales, leer artículos, libros para poder expandir nuestro conocimiento y habilidades profesionales.

**Espiar el código de los sitios que visitas**

Utiliza el Inspector de Elementos de tu navegador web para ver cómo hicieron algo que te gustó de la web que estás viendo. Más de una vez se aprenden técnicas y formas óptimas de lograr diferentes diseños o elementos.

**Librería personal de funcionalidades y plug-ins**

Armá tu propia librería de códigos. Guardá tus funciones de manera ordenada en archivos diferentes para poder tener un fácil acceso a ellas mientras estás desarrollando tus proyectos.

Por lo general los sitios web comparten muchas similitudes, como un Acordion, un Slider, una Galería de Imágenes. Por lo tanto no dudes en reutilizar tu código utilizando distintos estilos de diseño.


**Mantener adecuadamente tus herramientas de trabajo**

Ocúpate de tu computadora que es tu elemento de trabajo. Mantenla actualizada, limpia ordenada. Esto evitará que funcione lenta y haga tu día a día una frustración constante. 

Como así también se deben mantener actualizados los navegadores para desarrollar los sitios de manera óptima.

**Estándares web**

**Zona segura**

Revisa los diseños que recibas para maquetar, porque luego cuando el cliente lo ve en su computadora anticuada con una resolución menor a la más actual de todas, te dirán que no se ve correcamente. Muchas veces nos llegan diseños en medidas que no cumplen los estandares web y debemos saber trasmitirselo al cliente y a los diseñadores de manera adecuada.

**Optimización de contenido**

Recuerda siempre trabajar con archivos optimizados en su relación peso calidad. Tanto las imágenes (JPG, GIF, PNG), como en los archivos de texto. Evita usar espacios exagerados o comentarios muy extensos para alivinar al máximo el peso de tus archivos html, php, js, css, etc

# Navegadores o exploradores web más utilizados en internet
Tradicionalmente el navegador más utilizado de internet ha sido Internet Explorer, esta ventaja es debido a su característica de estar integrado en todas las instalaciones de Windows.

Durante los últimos años esta ventaja disminuye cada vez más, pese a las mejoras implementadas en la aplicacion. 
La disminución de su empleo por los usuarios se debe a la popularidad alcanzada por otros navegadores alternativos, que han conseguido superarlo en velocidad y rendimiento.

Algunos sitios de internet están especializados con la recopilación de estadísticas del uso de los navegadores, destacan: <a href=http://gs.statcounter.com/ target="_blank">StatCounter</a> (quizás el más popular), NetMarketShare y GlobalStats.
No obstante los resultados no son absolutos, factores como la zona geográfica, los sitios donde se muestrea el tráfico y otros influyen.

Nosotros solo podemos asegurar cuales son los navegadores más usados para entrar a nuestro sitio, usando las estadísticas que nos ofrece el servicio de Google Analytics. Quizás no representan la realidad del tráfico global, pero da una idea aproximada.

Los navegadores más usados para entrar a NorfiPC son los siguientes ordenados por su empleo:

* Google Chrome (alrededor del 65% del tráfico). Navegador de Google para PC y dispositivos portables.
* Android Browser. Navegador incluido en dispositivos que usan el SO Android.
* Safari. Navegador incluido en dispositivos de Apple como el IPhone e iPad, aunque también está disponible para la computadora.
* Mozilla Firefox. Navegador libre de internet para PC y dispositivos portables.
* Opera Mini. (Dispositivos portables).
* Internet Explorer. Incluido en Windows XP, Vista, 7 y 8.
* Opera (para PC).

Otros navegadores que constituyen menos del 1% del total del tráfico son: UC Browser, BlackBerry (dispositivos portables), Microsoft Edge (incluido en Windows 10), MxNitro de Maxthon (para PC) y Vivaldi (para PC).


### Características de los principales navegadores web


#### Características y cualidades de Google Chrome
* Navegador minimalista, es decir posee las funciones esenciales y básicas por lo que es ideal para personas con poco dominio en la navegación web.
* Velocidad súper-rápida del navegador, para eso emplea recursos como un motor de renderizado de Javascript V8 y prefetching (precarga) de DNS para mejorar el rendimiento en la carga de páginas web. Esta última característica es una innovación reciente, Google Chrome es el único navegador que la implementa por defecto, resuelve la relación IP/Nombre de dominio y la mantiene en su cache cierto tiempo por si es solicitada nuevamente. El sistema tradicional usado hasta ahora por los otros navegadores, es que Windows es el que la almacena y la libera al apagar el sistema.
Para ver el registro del prefetching de DNS que tienes actualmente en tu navegador escribe en la barra de direcciones **about:dns** te mostrará la dirección url, el nombre de host, tiempo de respuesta, hora a la que se resolvió, etc. 
* Es el navegador más favorecido a la hora de hacer una búsqueda web, solo es necesario escribir la palabra o termino de búsqueda en la barra de direcciones que es multiuso.
* Permite ver estadísticas de la memoria consumida en cada pestaña con sus detalles, inclusive la que consumen otros navegadores si se están usando simultáneamente en la misma PC. Para eso abre una nueva pestaña (CONTROL+T) y escribe: **about:memory**.
* Google ofrece la actualización automática del navegador, lo que asegura siempre tener instalada la última versión estable y tener disponible la blacklist, lista que contiene información sobre phishing (sitios de suplantación de identidad) y malware más reciente en la red.
* Ofrece similar a Internet Explorer la opción de navegar en forma de Incognito, las páginas a las que se accedan no quedarán registradas en el historial del navegador ni en el historial de búsquedas, y tampoco dejarán otros rastros en el equipo (como cookies).
* En la página de inicio (como introdujo Opera) muestra miniaturas de las páginas visitadas, lo que puedes usar como una especie de Bookmarks involuntarios.

#### Características, cualidades y ventajas de usar el navegador Internet Explorer

* Brinda un elevado nivel de seguridad, que a veces llega a ser desesperante pero muy efectivo, posee distintos niveles de seguridad dividido en zonas cada una con sus limitaciones.
* La exploración de InPrivate permite navegar por Internet sin guardar ningún dato de la sesión de exploración, como cookies, archivos temporales de Internet, historial y otros datos.
* Es el único navegador que ofrece soporte en las páginas web para ActiveX y VBScript.
* Compatible con paginas HTA, formato de páginas web que permiten interactuar con programas y archivos del equipo donde se ejecuten.
* Soporte para los applets de Java que funcionan mejor que en cualquier otro navegador.
* Al ser el explorador nativo de Windows puede descargar e instalar updates (actualizaciones) para el sistema operativo desde el sitio de Microsoft.
* Los Bookmarks, marcadores o favoritos son legítimos accesos directos que se pueden editar y modificar fácilmente por el usuario.
* A partir de la versión 8 incorpora nuevas funcionalidades como el uso de las WebSlice (Icono de color verde que puedes ver en esta página, en la barra de comandos del navegador), compatibilidad con el estándar CSS, la posibilidad de elegir otros motores de búsquedas, disponibilidad de multitud de complementos (llamados aceleradores), etc. 

#### Características, cualidades y ventajas de usar el navegador Mozilla Firefox

* Software de código abierto es un navegador totalmente configurable, tanto su funcionamiento, configuración, aspecto, add-ons o complementos. En su sitio web Mozilla ofrece toda la información técnica necesaria a desarrolladores y usuarios en general.
* Alto nivel de seguridad, efectiva la protección contra el spyware y otros tipos de malware, bloqueo asegurado contra pop-up y otras formas de publicidad comunes en la web, ActiveX no está permitido por considerarse un riesgo.
* Sus desarrolladores aseguran una fuente casi infinita de extensiones hechas para todo tipo de propósito.
* Permite crear y utilizar simultáneamente varios perfiles o preferencias en el mismo navegador, lo cual en la práctica es muy útil, es decir puedes tener una configuración diferente para usar Firefox en tus tareas laborales o estudiantiles y otra para tu uso privado o familiar, todo con el mismo navegador en la misma PC.

#### Opera
Es reconocido por su velocidad, seguridad, soporte de estándares (especialmente CSS), tamaño reducido y constante innovación. 
Implementó ya desde sus primeras versiones la navegación por pestañas, el Speed Dial, los movimientos del ratón en la navegación, personalización por sitio, y la vista en miniatura por pestaña, tiene su versión para móviles y tabletas.
Las últimas versiones de Opera usa el motor WebKit, el mismo que Chrome y Safari.
Usa un nuevo diseño, bastante más limpio.
La migración a Chromium trae una mejor compatibilidad, más rapidez y ahora las extensiones usan el mismo formato de Google Chrome.
Se introducen dos nuevas funciones: Discover y Stash.
La primera es una pestaña con las noticias más relevantes del día que se puede personalizar.
Stash es para guardar páginas y después poderlas rescatar, solo es necesario dar un clic en el icono del corazón.
La función Opera Turbo, ahora es llamado "Off the road" o "Todo terreno", ahora soportan SPDY para acelerar aún más la navegación.

#### Safari
Es el complemento indispensable para los usuarios de Mac OS X, para donde fue ideado inicialmente que iba a ejecutarse y donde están la gran mayoría de usuarios que lo utilizan dentro de alrededor del 4% de usuarios en el mundo. Es un navegador que se ha distinguido por su desempeño, velocidad y soporte de los estándares. Aunque Safari no es tan reconocido para usuarios de otros sistemas operativos diferentes a Mac OS, se ha vuelto una opción interesante desde que salió su versión para Windows.
Es el navegador predeterminado de todos los iDevice (iPhone, iTouch y iPad), pero es usado también en varios teléfonos y otros dispositivos portables que no son de Apple, por lo que es actualmente el navegador más utilizado en los móviles.


### Los navegadores más usados en teléfonos celulares y tabletas
A diferencia de en la computadora, los usuarios de los teléfonos o tabletas generalmente usan el navegador incluido en su dispositivo, aunque siempre existe la opción de elegir uno diferente al predeterminado.
Los navegadores más usados en los dispositivos portables, porque están incluidos en el sistema operativo son: Safari, Android Browser, Opera Mini y Blacberry.


### Navegadores alternos para usar en dispositivos portables
Actualmente es fácil instalar otros navegadores en los teléfonos celulares y tabletas, solo descargando la aplicación.
Los más descargados y usados son:

* Google Chrome
* Firefox
* Dolphin. Navegador muy eficiente y rápido disponible para el iPhone y Android, incluye características propias que lo hacen muy original como son el sonar (navegación mediante la voz), el panel para gestos (navegación mediante gestos), navegación de incognito, etc. Está disponible en GooglePlay y en la AppStore. http://dolphin-browser.com/
* UCBrowser. Navegador popular en Asia que según se dice está planeando la conquista del Oeste. Está disponible para Android, iOs, Java y Symbian, es extremadamente rápido y eficaz a la hora de navegar por Internet, teniendo más de 300 millones de usuarios. http://www.ucweb.com/

# OBJETIVOS DEL W3C
El objetivo del W3C es guiar la Web hacia su máximo potencial a través del desarrollo de protocolos y pautas que aseguren el crecimiento futuro de la Web. Debajo tratamos importantes aspectos de este objetivo, los cuales promueven la visión del W3C de Web Única.

# Principios
Los siguientes principios guían el trabajo del W3C.

## Web para todo el mundo
El valor social que aporta la Web, es que ésta hace posible la comunicación humana, el comercio y las oportunidades para compartir conocimiento. Uno de los objetivos principales del W3C es hacer que estos beneficios estén disponibles para todo el mundo, independientemente del hardware, software, infraestructura de red, idioma, cultura, localización geográfica, o habilidad física o mental. 

## Web desde cualquier dispositivo
La cantidad de dispositivos diferentes para acceder a la Web ha crecido exponencialmente. Actualmente, los teléfonos móviles, teléfonos inteligentes, PDAs, sistemas de televisión interactiva, sistemas de respuesta de voz, puntos de información e incluso algunos pequeños electrodomésticos pueden acceder a la Web.

## Visión
La visión del W3C para la Web incluye la participación, compartir conocimiento y, de esta forma, construir confianza a gran escala.

## Web de los Autores y Consumidores
La Web fue creada como una herramienta de comunicación para permitir el intercambio de información entre todo el mundo y desde cualquier lugar. Durante muchos años, para muchas personas la Web fue una herramienta de "solo lectura". Los blogs y wikis trajeron más autores a la Web y las redes sociales emergieron del próspero mercado para crear contenido y personalizar las experiencias en la Web. Los estándares del W3C han apoyado esta evolución gracias a la robusta arquitectura y a los principios de diseño. 

## Web de los Datos y Servicios
Algunas personas ven la Web como un repositorio gigante de datos enlazados mientras otros como un conjunto enorme de servicios que intercambian mensajes. Ambas vistas son complementarias y los requisitos de cada aplicación pueden ser los mejores determinantes para decidir que aproximación elegir para solucionar progresivamente los problemas complejos mediante tecnología Web. 

## Web de Confianza
La Web ha cambiado la forma en la que nos comunicamos. Al ocurrir esto, la naturaleza de nuestras relaciones sociales ha cambiado también. En la actualidad, las personas se "conocen en Internet", y llevan a cabo relaciones personales y comerciales sin haberse visto en persona anteriormente. El W3C reconoce que la confianza es un fenómeno social, pero el diseño de las tecnologías puede fomentar la confianza y la responsabilidad. A medida que cualquier actividad se hace a través de la Web, cada vez es más importante apoyar las interacciones complejas entre distintas partes alrededor del mundo.

# ¿Qué es Github Pages?

GitHub Pages es un servicio de alojamiento gratuito de GitHub para páginas web públicas y estáticas. Es mayormente utilizado para alojar blogs personales y sitios web de proyectos. Es una plataforma para blogging avanzado, ya que para su uso debes estar familiarizado con GitHub y por ende con la terminal o la linea de comandos.

La red esta llena de blogs, de propósitos tan diversos como sus temáticas. Cualquier persona con un poco de curiosidad puede hacerse un blog sencillo con herramientas como Blogspot y Tumblr, o algo un poco más elaborado con WordPress, una de las plataformas más populares. Sin embargo, siempre es importante que hayan alternativas y más si son de calidad y gratuitas.

Para crear una página  disponemos de la opción de generar de forma automática las páginas utilizando una herramienta gráfica, pero en este caso nos vamos a centrar en la creación y modificación de páginas web usando la línea de comandos con el comando git.

Tenemos dos alternativas para crear una página web con esta herramienta:

* **Páginas de usuario u organización:** Es necesario crear un repositorio especial donde se va a almacenar todos el contenido del sitio web. Si por ejemplo el nombre de usuario de Github es josedom24, el nombre del repositorio debe ser josedom24.github.io. Todos los ficheros que se van a publicar deben estar en la rama “master“. Por último indicar que la URL para acceder a la ṕagina sería http://josedom24.github.io.

* **Páginas de proyecto o repositorio:** A diferencia de las anteriores están asociada a cualquier repositorio que tengamos en Github (por ejemplo supongamos que el repositorio se llama “prueba“). En este caso los ficheros que se van a publicar deben estar en una rama del proyecto llamada gh-pages. La URL de acceso al sitio será http://josedom24.github.io/prueba.

# Creación manual de páginas

Mientras que las páginas de usuario son fáciles de crear, ya que simplemente debemos crear el repositorio y clonarlo en nuestro equipo (git clone) y empezar a crear ficheros que estarán guardados en la rama master, las páginas de repositorio pueden ser un poco más complejas ya que hay que crear la nueva rama que tenemos que llamar gh-pages, siguiendo el manual de Github Pages los pasos a dar son los siguientes:

```
$ git clone https://github.com/user/repository.git
# Clone our repository
# Cloning into 'repository'...
# remote: Counting objects: 2791, done.
# remote: Compressing objects: 100% (1225/1225), done.
# remote: Total 2791 (delta 1722), reused 2513 (delta 1493)
# Receiving objects: 100% (2791/2791), 3.77 MiB | 969 KiB/s, done.
# Resolving deltas: 100% (1722/1722), done.
```

A continuación tenemos que crear la nueva rama:

```
$ cd repository
$ git checkout --orphan gh-pages
# Creates our branch, without any parents (it's an orphan!)
# Switched to a new branch 'gh-pages'
$ git rm -rf .
# Remove all files from the old working tree
# rm '.gitignore'
```

Para terminar subiendo el primer fichero de nuestra página:

```
$ echo "My GitHub Page" > index.html
$ git add index.html
$ git commit -a -m "First pages commit"
$ git push origin gh-pages
```

# Cómo podemos construir nuestras páginas web

La forma más sencilla de construir nuestro sitio es subir a nuestro repositorio todos los ficheros necesarios: ficheros html, hojas de estilos, javascript, imágenes, etc. Si sólo tuviéramos esta opción de edición de páginas no tendríamos grandes ventajas para decidirnos a escoger este servicio de hosting.

Lo que realmente hace esta herramienta una opción muy potente es que Github Pages suporta Jekyll, herramienta escrita en Ruby que nos permite generar, de una forma muy sencilla, ficheros HTML estáticos. Aunque esta herramienta esta pensada para generar blogs, nosotros vamos a utilizar algunas de sus funcionalidades para crear páginas estáticas convencionales.

---------

## Usando Jekyll para crear páginas web

La principal característica de Jekylls es la generación de html estático a partir de dos recursos muy simples:

* Plantillas (templates): Ficheros que contienen el esqueleto de las página html que se van a generar. Estos ficheros normalmente se escriben siguiendo la sintaxis de Liquid.

* Ficheros de contenido: Normalmente escritos en sintaxis Markdown y que contienen el contenido de la página que se va a generar.

Por lo tanto una vez que tengo definidas mis plantillas, lo único que tengo que hacer es centrarme en  el contenido escribiendo los diferentes de ficheros de contenido.

----------

## Usando plantillas

Las plantillas son ficheros de texto con extensión html. Deben estar guardados en un directorio _layouts creado en la raíz de nuestro repositorio. Además del contenido html de las páginas que se van a generar, se pueden indicar distintas etiquetas que se sustituirán por diferentes valores. Veamos algunas etiquetas:

* La etiqueta más importante es {{ content }} que es sustituida por el contenido que definimos en los ficheros de contenido.

* La etiqueta {{ site.path }} será sustituida por el path del repositorio.

* Además se podrá definir en los ficheros de contenidos distintas variables que podrán ser sustituidas con etiquetas del tipo {{ page.nombredevariable }}.

Todas las referencia a ficheros de hojas de estilo, javascripts o imágenes que se definan en la plantilla deben estar guardados en nuestro repositorio.

-----------

## Usando Markdown para escribir el contenido de nuestras páginas

Los distintos contenidos de nuestras páginas serán definidos en ficheros Maarkdown con extensión md. La sintaxis de este lenguaje de marcas es muy sencilla y fácilmente convertible a html. Para practicar las distintas opciones puedes usar este editor online.

Sin entrar a definir la sintaxis del lenguaje, nos vamos a fijar en la primera parte de los ficheros donde se define la plantilla que se va a utilizar, y las distintas variables que son accesibles desde la plantilla.

```
---
layout: index

title: Servicios de red 
tagline: CFGM SMR
---
```

Con la variable layout indicamos el nombre del fichero html que corresponde a la plantilla que se va a usar para generar la página. Además hemos definido dos variables cuyo valor es accesible desde la plantilla con las etiquetas {{ pages.title }} y {{ page.tagline }}.

Por último indicar como se accede a las distintas páginas, suponiendo que tenemos definido una página de usuario en la URL josedom24.github.io, si tenemos un fichero en la raíz proyecto.md, sería accesible con la URL josedom24.github.io/proyecto. Si el fichero proyecto.md esta dentro de una carpeta llamada “ejemplo”, sería accesible con la URL josedom24.github.io/ejemplo/proyecto. De forma similar a como funcionan los servidores web si tenemos un fichero index.md no será necesario indicar el nombre en la URL.

