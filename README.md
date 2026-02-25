# Unidad 1. Introducción a la graficación por computadora.  

La graficación por computadora (GC) es un campo multidisciplinario bastante amplio, donde tanto computólogos, matemáticos, físicos, ingenieros, artistas y otros practicantes comparten un mismo objetivo "mostrar un mundo a través de una ventana", nos podemos referir como mundo a un modelo digital, una simulación, o bien, cualquier representación visual que se busque mostrar, y como ventana a cualquier medio para mostrar imágenes, como un proyector, la pantalla de un monitor, tablet, entre otros.

   
# 1.1. Historia y evolución de la graficación por computadora.

## Década de los 50

### 1950: Primeras imágenes gráficas
<img width="400" height="314" alt="image" src="https://github.com/user-attachments/assets/1b805684-f64f-481e-a77a-3eeb2308fa6a" />

Ben Laposky, artista y matemático, crea las primeras imágenes gráficas utilizando un osciloscopio, las cuales fueron registradas en fotografía por el mismo. Entre las diferentes figuras que creó se encuentran figuras de Lissajous.

### 1951: Whirlwind Computer
<img width="240" height="180" alt="image" src="https://github.com/user-attachments/assets/d262d04a-c7fa-4291-ae43-9b95bc73a0ba" />

La Whirlwind Computer creada en el MIT, fue la primera computadora digital de procesamiento de video en tiempo real. Mostraba texto y gráficos en un gran osciloscopio. Incluía un dispositivo revolucionario: "the light pen", el cuál permitía a la computadora identificar el componente gráfico del CRT (pantalla) que era tocado con el lápiz.

### 1955: SAGE
<img width="400" height="299" alt="image" src="https://github.com/user-attachments/assets/cca379e9-f3cf-4341-ad0e-a8ceaed60eb1" />

SAGE (Semi-Automatic Ground Environment) fue una red de grandes computadoras que reunía y procesaba datos de diferentes estaciones de radar para crear una imagen unificada del cielo sobre una gran región. Fue creada durante la Guerra Fría. Su propósito era detectar naves soviéticas que ingresaran en espacio Norteamérica.

### 1958: Vertigo
<img width="333" height="500" alt="image" src="https://github.com/user-attachments/assets/7134c9e6-69c5-4b10-afd7-c681c5f8d048" />

La película Vertigo de 1958 da inicio con una secuencia animada creada por John Whitney, el cual es considerado el padre de la animación por computadora.

### 1959: DAC-1
<img width="218" height="262" alt="image" src="https://github.com/user-attachments/assets/39636975-d35c-4aea-aa13-0443bc7a820b" />

General Motors desarrolla el primer programa de diseño asistido por computadora, el DAC-1 (Design Augmented by Computers). Su propósito era digitalizar el diseño de un automóvil en 3D. El programa permitía rotar, escalar y cambiar el ángulo de la imagen.

## Década de los 60

### 1960: Computer Graphics
<img width="200" height="180" alt="image" src="https://github.com/user-attachments/assets/40efbd98-ac2a-47f1-8170-afa3e0564a7f" />

A William Fetter se le atribuye el término "Computer Graphics". En 1960, él y Vern Hudson, su supervisor en Boeing, acordaron usar el término para describir el uso de un trazador mecánico controlado por computadora para dibujar sobre papel, cintas o películas. Una de las imágenes más memorables de "Computer Graphics" fue una figura humana a la que Fetter llamaba "First man".

### 1962: Spacewar
<img width="400" height="284" alt="image" src="https://github.com/user-attachments/assets/5452163b-a771-4a98-aa08-39ed3e85dbd6" />

Un joven programador del MIT llamado Steve Russell crea Spacewar. Fue programado para el minicomputador DEC PDP-1, la cual usaba un tubo de rayos catódicos (CRT) como display. Además, su sistema operativo PDP-1 permitía a más de un usuario usar la computadora simultáneamente, lo que permitió a Spacewar ser un juego multijugador para 2 personas.

### 1962: Bresenham's line algorithm
<img width="300" height="429" alt="image" src="https://github.com/user-attachments/assets/393cb394-3c8f-4b59-8e78-abfdccd958b7" />

Jack Elton Bresenham mientras estaba en el MIT desarrolló un algoritmo para determinar cuáles son los puntos en una matriz bidimensional que deben ser pintados para formar lo más cercano posible a una línea recta entre 2 puntos dados. Este algoritmo es uno de los primeros descubiertos en gráficos por computadora (Computer Graphics).

### 1963: Sketchpad
<img width="220" height="176" alt="image" src="https://github.com/user-attachments/assets/c7cc0f7a-9dda-4158-9b89-6f94f9bee6c1" />

Ivan Sutherland diseña el programa Sketchpad como parte de su tesis doctoral en el MIT. Sketchpad fue el primer programa que permitía la manipulación directa de objetos gráficos y también es considerado el padre de los programas CAD actuales.
Con ayuda de un lápiz óptico el usuario podía dibujar directamente sobre la pantalla, seleccionar elementos gráficos para modificarlos y mover a través de la pantalla los elementos seleccionados. El programa ofrecía botones con diferentes funciones que podían ser utilizadas por el usuario al presionar los botones con el lápiz óptico, por lo tanto, también fue precursor de la interfaz gráfica de usuario (GUI). Además, Sketchpad introdujo el concepto de "zoom".

### 1963: Primer mouse
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/2a8698d1-ed34-4f1b-ac97-a56af5b2a430" />

A Doug Engelbart se le ocurrió la idea básica para el primer "mouse" en 1961 mientras estaba en una conferencia sobre gráficos de computadora. En 1963 gracias a los resultados de su investigación "Augmenting Human Intellect: A Conceptual Framework" recibe un pequeño financiamiento de ARPA con el cuál forma un pequeño equipo para estudiar y obtener datos sobre la eficiencia de diferentes dispositivos de la época que permitían usar un cursor en pantalla. Entre dichos dispositivos se encontraba un prototipo creado por el ingeniero Bill English: un dispositivo de mano con ruedas perpendiculares montadas en un bloque de madera con un botón en la parte superior. Este fue el primer mouse.

### 1967: Parche de Coons
<img width="400" height="266" alt="image" src="https://github.com/user-attachments/assets/4e725854-cfbf-4164-8c49-14c60ba80300" />

En junio de 1967, Steven Coons publica "Surfaces for Computer-aided Design of Space Forms". En este trabajo, Steven muestra una forma matemática de describir superficies a través de un objeto conocido como "Coons Patch". Este trabajo fue el antecesor de técnicas más modernas para describir superficies tales como: b-spline surfaces y NURB surfaces. Estas técnicas son utilizadas en la actualidad para representar curvas y superficies gráficamente en la computadora.

## Década de los 70

### 1971: Sombreado Gouraud
<img width="386" height="384" alt="image" src="https://github.com/user-attachments/assets/bfe30c2b-1517-4549-8125-c9bdb13d9ed0" />

Es una técnica usada en gráficos 3D que simula efectos de luz y color sobre superficies de objetos. Fue publicada por Henri Gouraud.

### 1972: Pong
<img width="351" height="480" alt="image" src="https://github.com/user-attachments/assets/4e4db5bc-0130-4a3a-ad41-1280bcdbb658" />

Publicado por Atari y lanzado el 29 de noviembre de 1972, Pong se volvió el primer videojuego con éxito comercial.

### 1973: Westworld
<img width="314" height="480" alt="image" src="https://github.com/user-attachments/assets/4b6f9b07-54a6-4587-8bb2-c16244c5089d" />

La película Westworld escrita y dirigida por Michael Crichton fue la primera en tener una secuencia de animación digital como parte de los efectos especiales. La secuencia fue creada por los artistas: John Whitney y Gary Demos.

### 1974: Mapeo de texturas
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/abdeb3ca-32ee-49b9-ad42-106e80dd8a19" />

Es un método para definir información de la superficie de un objeto gráfico en 3D. Un mapa de textura contiene información sobre la apariencia de la superficie de un modelo en 3D. La técnica original fue iniciada por Edwin Catmull.

### 1975: Sombreado Phong
<img width="400" height="173" alt="image" src="https://github.com/user-attachments/assets/41288076-1145-4a19-9603-82d56936cdd7" />

El sombreado de Phong es un modelo empírico de iluminación local. Es una técnica de sombreado en objetos 3D. Fue desarrollado por Bui Tuong Phong y publicado en su tesis doctoral de 1975.

### 1976: Futureworld
<img width="252" height="396" alt="image" src="https://github.com/user-attachments/assets/c76eba29-ced5-4020-ba66-b452832dbecd" />

La secuela directa de Westworld fue la primera película en utilizar animación 3D. La animación tridimensional fue utilizada únicamente para animar la cara de una mano. Cabe aclarar que este efecto no fue agregado a la película en postproducción como sucede en la actualidad, todavía falta tiempo para la aparición de estas técnicas.

### 1977: Apple II
<img width="400" height="266" alt="image" src="https://github.com/user-attachments/assets/ef72f4f6-d539-49ba-b8f8-ce1b6855b8ca" />

Apple presenta la primera computadora personal con pantalla a color.

### 1978: Mapeo de relieve
<img width="400" height="250" alt="image" src="https://github.com/user-attachments/assets/1f120b3a-7f91-4d96-b4ec-8969f8ccd2de" />

El mapeo de relieve es una técnica en gráficos por computadora para hacer que una superficie renderizada parezca más realista. Fue introducido por James Blinn.

### 1979: Ray tracing
<img width="399" height="500" alt="image" src="https://github.com/user-attachments/assets/bf74dfe7-5c03-45df-8225-6118b86db95d" />

John Turner Whitted presentó el ray tracing en su trabajo: "An improved illumination model for shaded display". Su algoritmo demostró ser una solución práctica para definir una iluminación global en gráficos por computadora.

## Década de los 80

### 1982: Tron
<img width="400" height="288" alt="image" src="https://github.com/user-attachments/assets/802c19e8-52e6-4c22-8a8a-6c6ccacad3f9" />

La película Tron, de Steven Lisberger, fue la primera película en utilizar técnicas de CGI para crear una secuencia completa de 15 minutos abriendo la puerta a la digitalización del cine.

### 1984: Polhemus
<img width="400" height="225" alt="image" src="https://github.com/user-attachments/assets/632471be-8157-44ff-91f3-dcbbc07d4ac1" />

Wavefront Tech crea Polhemus el primer software de diseñado 3D.

### 1986: Primer cortometraje de Pixar
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/b3624051-4c62-4f57-9b7b-09e52b325659" />

Uno de los antecedentes de Toy Story, Luxo Jr. fue un cortometraje de apenas 2 minutos que se ha vuelto de culto en la cultura de la animación.

### 1987: VGA
<img width="400" height="313" alt="image" src="https://github.com/user-attachments/assets/3c902f98-384e-4d79-b5aa-4b5a209bbdee" />

El VGA (Video Graphics Array) es un estándar para la salida de video de las computadoras. Fue introducido por IBM.

### 1989: VESA
<img width="400" height="194" alt="image" src="https://github.com/user-attachments/assets/a40c4c45-88be-4130-ae1f-9735304034b5" />

La VESA (Video Electronics Standards Association) es una asociación internacional de fabricantes de electrónica. Fue fundada inicialmente para desarrollar pantallas de video con una resolución común de 800x600 pixeles.

## Década de los 90

### 1990: Renderman
<img width="400" height="203" alt="image" src="https://github.com/user-attachments/assets/0f747f3a-48ef-4e10-9770-845a26fa7fe8" />

Renderman es un software desarrollado por Pixar para renderizar complejas imagenes tridimensionales en granjas de renderizado con muchos equipos.

### 1991: La Bella y la Bestia
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/d0b3160c-a3d3-4256-842f-8f55b526df71" />

Película de Pixar donde se utilizó ampliamente los gráficos generados por computadora. Se uso Renderman para renderizar los gráficos tridimensionales.

### 1992: OpenGL
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/7e560875-0cfb-47bc-9de5-3a8ed6e41ad1" />

Fue originalmente desarrollada por Silicon Graphics Incorporated (SGI). Se volvió un estándar que define una API para crear aplicaciones que generen gráficos 2D y 3D.

### 1993: Mosaic
<img width="400" height="346" alt="image" src="https://github.com/user-attachments/assets/9c8216bc-f227-4ac9-9517-c9b5ae0c8213" />

Marc Andressen en la Universidad de Illinois crea el primer navegador web gráfico: Mosaic. Permitía visualizar páginas web en sistemas operativos Mac, Windows y demás.

### 1993: Jurassic Park
<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/21ccc698-cc6c-436f-90e2-d436afc7440e" />

Fue la primera película donde los efectos generados por gráficos de computadora compartían pantalla al mismo tiempo con actores reales. En este caso, creando el efecto de que los dinosaurios eran reales.

### 1995: Toy Story
<img width="400" height="210" alt="image" src="https://github.com/user-attachments/assets/eee7330b-248c-446c-88fb-9312966fdb79" />

Fue la primera película animada 3D generada completamente por computadora.

### 1999: GeForce 256
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/f1cf013c-b145-4308-b61d-8603c4d4f682" />

Nvidia lanza su primera familia de productos NVIDIA GeForce.

## 2000

### 2001: Final Fantasy
<img width="400" height="196" alt="image" src="https://github.com/user-attachments/assets/6382fea8-fbb8-46a8-a2d2-66fdae3ce578" />

La película animada Final Fantasy: The Spirits Within fue el primer intento serio en crear humanos animados de manera fotorrealista.

### 2003: Id Tech 4
<img width="400" height="225" alt="image" src="https://github.com/user-attachments/assets/2ba4daed-b775-4a08-9387-875ce5094605" />

Motor gráfico para el videojuego Doom 3 desarrollado por id Software. Para su época, presentó gráficos muy avanzados que requerían mucha potencia para ser corridos.

### 2015: Interactive Global Illumination
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/af1d6408-f247-400a-8aa3-3a4594ddf22d" />

Las técnicas de iluminación global continuaron mejorando.

### 2018: Real-time Ray Tracing
<img width="400" height="219" alt="image" src="https://github.com/user-attachments/assets/df4a21a3-0a5d-4b3c-b43a-4dd821de01d5" />

Se volvió tendencia utilizar Ray Tracing en tiempo real y era normal verlo en los videojuegos de la época para mejorar la experiencia del jugador.

## Actualidad
<img width="400" height="225" alt="image" src="https://github.com/user-attachments/assets/c746e4fc-d497-49e6-b7ab-da33ca6c3d44" />

En la actualidad los gráficos generados por computadora forman parte fundamental del entretenimiento. Las diferentes técnicas de graficación por computadora y las capacidades del hardware han evolucionado tanto que hoy en día es posible sumergir al usuario en un mundo de fantasía totalmente digital.

Incluso nuestros smartphones cuentan con una tarjeta de video potente a pesar de su reducido tamaño.
En los diferentes ámbitos donde se utiliza la graficación se han creado una gran variedad de herramientas que facilitan y automatizan varias tareas relacionadas a la creación de gráficos, por ejemplo: los motores de videojuegos.

# 1.2. Áreas de aplicación.

La graficación por computadora se utiliza en múltiples áreas:

1. Industria del entretenimiento: Creación de películas o caricaturas sintéticas, publicidad, efectos visuales y videojuegos.
2. Ingeniería Mecánica: Diseño de prototipos virtuales de partes mecánicas para su construcción, utilizando sistemas CAD/CAM (Computer-Aided Design/ Computer-Aided Manufacturing).
3. Arquitectura: Uso del software CAD para la creación de planos de alguna estructura arquitectónica, visualizaciones de espacios antes y después de una construcción planeada.
4. Diseño: Diseño y creación de productos, haciendo uso de sistemas CAD/CAM, promoviendo la creatividad del diseñador al permitirle experimentar con varias formas antes de producir la idea final.
5. Patrimonio cultural: Reconstrucciones virtuales de templos, monumentos, piezas antiguas, o bien, reconstrucciones hipotéticas de escenas.
6. Medicina: Simulaciones virtuales de cirugías para entrenamiento y visualización de datos dados por algún instrumento de diagnóstico.

Asimismo, se han ido desarrollando un gran número de áreas de especialización, las cuales han ido evolucionando de acuerdo a las necesidades de los usuarios y al avance tecnológico en el hardware y software. Las principales suelen ser las siguientes:

7. Renderización: Es el proceso para generar una imagen final dada una entrada ordenada de datos, se suele clasificar dependiendo del algoritmo que se use, generalmente se toma como referencia el tiempo que a éste le tome en producir una imagen sintética (Real time rendering, Offline rendering), o bien, el tipo de técnica de renderizado que utilice (Photorealistic rendering, non-photorealistic rendering o information visualization).
8. Modelado: Es la especificación matemática del mundo a representar, es decir, se describen los objetos y sus propiedades de un modo que éstos puedan ser almacenados en la computadora, por ejemplo, una manzana puede ser descrita como un conjunto de puntos 3D, los cuales forman caras ordenadas, con un modelo de iluminación especifico para describir cómo interactúa la luz con la manzana.
9. Animación: Es la creación de una secuencia de imágenes con una computadora, que tiene como finalidad producir la ilusión de movimiento. Si bien, hace uso de las dos áreas anteriores, no se encarga del estudio de éstas, pues su objetivo es añadir alguna animación sobre un rango de tiempo específico a los modelos, con la cual modifica algún aspecto de éstos, como su color, posición, apariencia, entre otros.

Y entre algunas otras áreas de relevancia se encuentran:

10. Simulación: Es el proceso en el que un modelo matemático es ejecutado y representado con una computadora, la cual es usada para simular un comportamiento y su repercusión en el mundo real, o bien, dentro de un sistema físico impuesto, permitiendo revisar la fiabilidad del modelo, por lo cual es útil para modelar sistemas en física, astrofísica, climatología, química, biología, economía, ingeniería, etc. Por ejemplo, el movimiento de las partículas del agua en una ola, o bien, la simulación en tiempo real de un escenario de entrenamiento, como volar un avión. Las simulaciones garantizan un menor costo y mayor seguridad para los usuarios.
11. Fotografía Computacional: Es el uso de las técnicas de graficación por computadora, visión artificial y proceso digital de imágenes empleadas para mejorar el potencial de la fotografía digital y la calidad de la captura digital de imágenes, desarrollando otras formas de capturar objetos, escenas y ambientes. Permitiéndonos producir equipos fotográficos de bajo costo capaces de identificar caras, hacer reenfoques, panorámicas, e incluso hacer que el resultado luzca similar o mejor al de un equipo caro.
12. Escaneo en 3D: Es el proceso de colectar información de objetos del mundo real para crear un modelo 3D, desarrollando muchos dispositivos y algoritmos para obtener la geometría y apariencia del objeto real, dichos modelos son utilizados para crear visualizaciones.
13. Proceso Digital de Imágenes: Es la aplicación de técnicas y algoritmos para la manipulación de imágenes 2D, para obtener información de éstas, o bien, mejorar su calidad.
14. Realidad Virtual: Es la simulación de un entorno virtual en 3D generado por computadora, que intenta hacer experimentar al usuario una sensación de estar inmerso en él. Aunque puede ser proyectado simplemente en la pantalla de un dispositivo como un monitor, se suelen utilizar otras tecnologías tales como cascos de realidad virtual, guantes, o incluso diseñar espacios, para intensificar las sensación de realidad y que además le permita una mejor interacción con el mundo virtual, creando imágenes realistas, sonidos y otras sensaciones.
15. Realidad Aumentada: Es la visualización de un espacio real en donde a los objetos tangibles de éste se les añade información gráfica generada por computadora, es decir, elementos virtuales son agregados al mundo real, cubriendo total o parcialmente a objetos del entorno, y permitiéndole al usuario interactuar en tiempo real dentro de este espacio mixto.

# 1.3. Aspectos matemáticos de la graficación.

"le invito a contemplar alguna de las imágenes que más abajo aparecen…

<img width="320" height="198" alt="image" src="https://github.com/user-attachments/assets/daabccbf-ba8d-41b1-8ac0-2c6bfb350ae2" />
<img width="320" height="262" alt="image" src="https://github.com/user-attachments/assets/7b07b1fd-da4e-43ab-9f8f-31a2edd315b9" />

Es fácilmente apreciable, además de su indudable belleza, su semejanza con estructuras naturales con las habitualmente nos tropezamos. Sin embargo, todas ellas son producto de “matemáticas experimentales” (que no aplicadas), o dicho de otro modo, han sido confeccionadas sin salir del laboratorio matemático cuyo material es, esencialmente, un ordenador y algunos conceptos
matemáticos sabiamente utilizados."

La geometría fractal ocupa en cierta medida este vacío y puede usarse para diseñar fielmente
desde la intrincada silueta de una simple hoja hasta la evolución del árbol.
Primero para introducirnos al el mundo de los Fractales, lo primero que hay que contar son las palabras que dan inicio al libro "Fractals Everywhere" ("Fractales en todos Lados") de Michael F. Barnsley, uno de los pioneros y más importantes divulgadores e investigadores del tema:

"La geometría Fractal cambiará a fondo su visión de las cosas. Seguir leyendo es peligroso. Se arriesga a perder definitivamente la imagen inofensiva que tiene de nubes, bosques, galaxias, hojas, plumas, flores, rocas, montañas, tapices, y de muchas otras cosas. Jamás volverá a recuperar las interpretaciones de todos estos objetos que hasta ahora le eran familiares."

Ésta geometria tiene su origen en el concepto de proceso iterativo introducido hace ya 300 años por Isaac Newton y Gottfried Leibniz. De forma esquemática, un proceso iterativo consta de: una unidad de entrada compuesta por un dato inicial. Esta unidad de entrada alimenta la unidad de proceso, cerebro pensante del proceso iterativo, que manipula la información recibida y produce un nuevo dato que constituye la unidad de salida. Este nuevo dato será posteriormente utilizado por la unidad de entrada para volver a alimentar la unidad de proceso, y así sucesivamente.

<img width="620" height="450" alt="image" src="https://github.com/user-attachments/assets/cbfa29f6-b878-4a2b-b705-91884f060953" />

Observamos además que después de un número suficiente de iteraciones el resultado obtenido es prácticamente el mismo, que por cierto responde a un animal matemático con nombre propio, el triángulo de Sierpinski.
También es tan sorprendente como fácilmente comprobable que, tomando una imagen inicial distinta, el resultado “final” es el mismo.

Un grupo de matemáticos comenzó a darse cuenta que en la naturaleza se daba muy seguido el fenómeno de irregularidades y que no eran excepciones como se suponía. Los primeros que comenzaron a demostrar teóricamente esta problemática fueron Cantor (con su famoso y casi místico conjunto de Cantor – Figura 2) y Peano. Hasta llegar a los años de 1880 con Poincaré, al que se lo conoce como el padre de la Teoría del Caos.

<img width="232" height="153" alt="image" src="https://github.com/user-attachments/assets/b6b134ea-be6e-40f4-b691-af20c38980d1" />

Segun lo antes mencionado . . .
¿Que es Geometria Fractal?

<img width="250" height="247" alt="image" src="https://github.com/user-attachments/assets/3b257261-f1d8-4ed1-ac84-282b15ed27da" />

Geometría Fractal es geometría que no distingue entre conjunto matemático y objeto natural. Este nuevo paradigma engulle paradigmas anteriores proyectando un modelo que inagura una nueva zona o región de lo real.

# 1.4. Modelos del color: RBG, CMY, HSV y HSL.

## ¿Qué es un modelo de color?
Un modelo de color establece un conjunto de colores primarios a partir de los que, mediante mezclas, se pueden obtener otros colores hasta cubrir todo el espectro visible, además del propio blanco, negro y grises, y aún más. Por ejemplo, hay colores, como el marrón o el magenta, que no están presentes en el espectro visible, y es nuestro cerebro el que lo interpreta a partir de la combinación de ondas con diferentes longitudes.

Los modelos de color más comunes son RGB (utilizado en monitores) y CMYK (utilizado para impresión), que veremos más adelante.

### Modelos aditivos y sustractivos

Hay dos tipos de modelos de color, los aditivos y los sustractivos. Un modelo aditivo se basa en la adición o mezcla de los colores básicos como forma para obtener el blanco.

Un modelo sustractivo se basa en la mezcla de los colores primarios de dicho modelo para «sustraer la luz», es decir, para obtener el negro, que como comentábamos en el artículo de la luz, es la ausencia de luz.

Si recordamos del primer artículo, cuando empleamos el término «color» en realidad nos referimos al «matiz» o «croma». Y junto a los colores también tenemos los tres casos especiales: el blanco, el negro y los grises.

### Modelo RGB
Volviendo a los modelos de color más habituales en fotografía, el modelo RGB define como colores primarios el rojo, el verde y el azul. La combinación de los tres genera blanco. La ausencia de los tres genera negro. Las diferentes mezclas entre ellos representarían toda la gama de color. De nuevo, los grises se representarían con diferentes intensidades de cada color, pero siempre los tres con el mismo valor.

El modelo RBG se utiliza cuando se representa color mediante haces de luz (pantallas o monitores). Un pixel en un monitor se representaría mediante tres subpíxeles o células: una roja, una verde y una azul, correspondiendo cada una a un LED o diodo emisor de luz del respectivo color.

Si los tres diodos están apagados, obtendríamos el negro. Si están encendidos a diferentes intensidades, obtendríamos colores, si están todos encendidos con la misma intensidad y al máximo, tendríamos el blanco, y si la intensidad es menor pero igual en los tres diodos, obtendríamos grises.

### Modelo CMYK
Es un modelo sustractivo y se utiliza en impresión a partir de pigmentos de tres colores básicos: C – cian, M – magenta y Y – amarillo. La K viene del negro, ya que la combinación de los tres anteriores produce un negro poco puro, de ahí que se añada al modelo un pigmento negro puro. Al contrario que en RGB, donde el negro es la ausencia de luz, en CMYK el blanco se representa aquí como ausencia de pigmentos.

Los colores intermedios se producen a partir de la mezcla en distintas proporciones de los pigmentos base.

Hay una relación entre los modelos RGB y CMYK, ya que con la mezcla a igual parte de cada uno de los colores básicos de un modelo obtenemos los primarios del otro.

En RGB (rojo, verde, azul):
1. Rojo y verde en iguales proporciones: obtenemos amarillo – Y de CMYK
2. Rojo y azul en iguales proporciones: obtenemos el magenta – M
3. Verde y azul en iguales proporciones: obtenemos el cian – C

En CMYK (cian, magenta, amarillo):
1. Cian y magenta en igual proporción: obtenemos el azul
2. Cian y amarillo en igual proporción: obtenemos el verde
3. Magenta y amarillo en igual proporción: obtenemos el rojo

### Modelo HSV y HSL
Estos modelos incluyen otros dos parámetros adicionales al matiz o croma para obtener el color, que son la saturación (en ambos) y el valor (en HSV) o la luminosidad o tono (en HSL). De ahí sus siglas: HSL (H – hue o matiz, S – saturation o saturación, L – luminosity o luminosidad/tono), HSV (idem excepto V de value o valor).

La diferencia entre HSV y HSL es que en HSV la saturación va del color puro al blanco, y en HSL la saturación va del color puro al gris medio, y el tono, en HSV va desde el negro al color, y en HSL va desde el negro al blanco. De ahí que HSL sea el que se utiliza más comúnmente en fotografía.

Lightroom, que se basa en HSL, dispone de controles para alterar H – matiz, S – saturación y L – Tono para los siguientes colores: rojo, naranja, amarillo, verde, cian, azul, violeta y magenta.

Siguiendo con Lightroom, éste nos permite fijar la saturación entre gris y color puro para esos 8 colores. Respecto al matiz, nos permite virar los 8 colores a los adyacentes que comentaba en el artículo de luz y color, por ejemplo, para el rojo, desde magenta a naranja.

Por último, respecto al tono, Lightroom nos permite oscurecer cada uno de esos 8 colores hasta el negro, o bien aclararlo hasta llegar al blanco.

Si utilizásemos un programa basado en HSV, el control del matiz sería similar, el control de la saturación nos permitiría llevar un matiz dado a su expresión más pura, o bajar su saturación hasta llegar el blanco, raro, ¿verdad?. Y respecto al tono, nos permitiría para un matiz dado, bajar su tono hasta el negro o subirlo hasta el color puro, también raro, ¿verdad?.

(En este apartado puedes colocar un tutorial de como iluminar un cubo y sus caras, en blender)

# 1.5. Representación y trazo de líneas y polígonos.

# Referencias
Introducción a la graficación por computadora. (s. f.). https://proyectodescartes.org/iCartesiLibri/materiales_didacticos/GraficacionComputadora/index.html?page=12
Sutori. (s. f.). Sutori. https://www.sutori.com/es/historia/historia-y-evolucion-de-la-graficacion-por-computadora--HWxiLPJRpHqkjwYoadxpmheZ
Valdes, A. S. (2013, 14 septiembre). 1.4 Aspectos matemáticos de la Graficación (Geometría fractal). https://graficacionito.blogspot.com/2013/09/14-aspectos-matematicos-de-la.html
Antonio. (2016, 19 junio). Modelos de color (RGB, CMYK, HSV/HSL). Antonio Herrera. https://ahenav.wordpress.com/2014/04/09/modelos-de-color/
