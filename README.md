# Unidad 1. Introducción a la graficación por computadora.  

La graficación por computadora (GC) es un campo multidisciplinario bastante amplio, donde tanto computólogos, matemáticos, físicos, ingenieros, artistas y otros practicantes comparten un mismo objetivo "mostrar un mundo a través de una ventana", nos podemos referir como mundo a un modelo digital, una simulación, o bien, cualquier representación visual que se busque mostrar, y como ventana a cualquier medio para mostrar imágenes, como un proyector, la pantalla de un monitor, tablet, entre otros. Por lo que nos podemos dar una idea de las multiples aplicaciones que se pueden obtener en este campo sobre los diferentes ámbitos, veamos algunas de estas aplicaciones:

1. Industria del entretenimiento: Creación de películas o caricaturas sintéticas, publicidad, efectos visuales y videojuegos.
2. Ingeniería Mecánica: Diseño de prototipos virtuales de partes mecánicas para su construcción, utilizando sistemas CAD/CAM (Computer-Aided Design/ Computer-Aided Manufacturing).
3. Arquitectura: Uso del software CAD para la creación de planos de alguna estructura arquitectónica, visualizaciones de espacios antes y después de una construcción planeada.
4. Diseño: Diseño y creación de productos, haciendo uso de sistemas CAD/CAM, promoviendo la creatividad del diseñador al permitirle experimentar con varias formas antes de producir la idea final.
5. Patrimonio cultural: Reconstrucciones virtuales de templos, monumentos, piezas antiguas, o bien, reconstrucciones hipotéticas de escenas.
6. Medicina: Simulaciones virtuales de cirugías para entrenamiento y visualización de datos dados por algún instrumento de diagnóstico.

Asimismo, se han ido desarrollando un gran número de áreas de especialización, las cuales han ido evolucionando de acuerdo a las necesidades de los usuarios y al avance tecnológico en el hardware y software. Las principales suelen ser las siguientes:

7. Renderización: Es el proceso para generar una imagen final dada una entrada ordenada de datos, se suele clasificar dependiendo del algoritmo que se use, generalmente se toma como referencia el tiempo que a éste le tome en producir una imagen sintética (Real time rendering, Offline rendering), o bien, el tipo de técnica de renderizado que utilice (Photorealistic rendering, non-photorealistic rendering o information visualization).
8. Modelado: Es la especificación matemática del mundo a representar, es decir, se describen los objetos y sus propiedades de un modo que éstos puedan ser almacenados en la computadora, por ejemplo, una manzana puede ser descrita como un conjunto de puntos 3D, los cuales forman caras ordenadas, con un modelo de iluminación especifico para describir cómo interactúa la luz con la manzana.
9. nimación: Es la creación de una secuencia de imágenes con una computadora, que tiene como finalidad producir la ilusión de movimiento. Si bien, hace uso de las dos áreas anteriores, no se encarga del estudio de éstas, pues su objetivo es añadir alguna animación sobre un rango de tiempo específico a los modelos, con la cual modifica algún aspecto de éstos, como su color, posición, apariencia, entre otros.

   
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
