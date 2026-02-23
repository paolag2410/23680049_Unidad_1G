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

