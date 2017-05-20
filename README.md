# Inferencia estadística básica

## Lectura previa
 - [Seeing Theory: A visual introduction to probability and statistics](http://students.brown.edu/seeing-theory/).
 - [STA 101 Labs](http://www2.stat.duke.edu/~mc301/101_labs/).
 - [Lectures on Statistics Robert Ash](http://www.math.uiuc.edu/~r-ash/Stat.html).
 
## Software
 
 ### R Markdown 

[R Markdown](http://rmarkdown.rstudio.com/index.html) es un framework para ciencia de datos de manera que puede crear reportes dinámicos con R, además de ejecutar y guardar código. Por ejemplo sea un tabla en markdown con R.

```{r , results='asis', echo=FALSE}
cat("x | y", "--- | ---", sep="\n")
cat(apply(df, 1, function(X) paste(X, collapse=" | ")), sep = "\n")
```

R Markdown soporta formatos de salida estáticos y dinámicos que incluye  hTML, pdf,  beamer-latex, html5T, shiny,etc.

Más información:

* [Lecciones de R Markdown ](http://rmarkdown.rstudio.com/lesson-1.html).

En las notas se usan los *los folletos(handout) de [Edward Tufte](http://rmarkdown.rstudio.com/tufte_handout_format.html)*. El estilo de Tufte es conocido por su amplio uso de notas al margen, la estrecha integración de gráficos con el texto, y una establecida tipografía. Se puede instalar como un paquete de R  de la siguiente forma:

```
install.packages("tufte", type = "source")
```

### R Notebooks
Un R Notebooks es un documento R Markdown, que permite mostrar independientemente e interactivamente , código R y sintaxis de  otros lenguajes. Es una manera fácil de generar reportes, análisis estadísticos, visualización de datos.

Más información en  la página [http://rmarkdown.rstudio.com/r_notebooks.html](http://rmarkdown.rstudio.com/r_notebooks.html).
 
 ## Acerca de temas de presentación y complementarios.
 
 Lista de temas, que extienden las notas de  los repositorios [Curso-R](https://github.com/C-Lara/Curso-R) y [Curso-Probabilidad](https://github.com/C-Lara/Curso-Probabilidad), parte del curso  *CM-274 Introducción a las Probabilidades y Estadística* . 

 - Estrategias generales para el diseño de Algoritmos
    * Búsqueda exhaustiva.
    * Vuelta atrás.
    * Disminuir y conquistar.
    * Transformar y conquistar.
    * Greedy.
 - Técnicas de Análisis
    * Análisis de un algoritmo no recursivo. Ejemplo: Square Build-Up. 
    * Análisis de un algoritmo recursivo. Ejemplo: Torres de Hanoi.
    * Invariantes. Ejemplos.
 - Complejidad de Kolmogorov.
    * Complejidad algorítmica. Probabilidad algorítmica.
    * Razonamiento inductivo. 
    * Incompatibilidad e Incompresibilidad
 - Herramientas de álgebra lineal numérica
    * Estructura matricial y complejidad algoritmica.
    * Resolución de ecuacions lineales con matrices factorizadas.
    * Factorización LU, Cholesky y LDLT.
    * Eliminación de bloques. Complemento de Schur.
    * Algoritmos.
 - Descomposición QR, transformaciones de Householder y rotaciones Givens. Algoritmos.
 - El procedimiento de Gram-Schmdidt, descomposición QR, mínimos cuadrados. Algoritmos.
 - Métodos de Gradiente conjugado. Algoritmos y complejidad.
 - Métodos de subespacios de Krilov. Algoritmo de Arnoldi y Lanczos.
 - Descomposición por valores singulares (SVD). Algoritmos.
   * Métodos de subespacios : PCA, MDS, FDA y CCA.
   * Propiedades variacionales de autovalores y valores singulares.
   * Matrices diferenciales.
 - Algoritmos de Grafos
   * Algoritmos del camino más corto: Dijstra, Floyd-Warshall.
   * Problema del árbol generador mínimo.
   * Algoritmo BFS y DFS. 
   * Algoritmo de Boruvka -Solling.
 - Flujo de redes 
   * Redes de transporte y cortes.
   * Teorema del máximo flujo y el mínimo corte.
   * Capacidad residual y red residual.
   * Algoritmo de Ford-Fulkerson. Modificación del algoritmo de Ford-Fulkerson por Edmonds-Karp.
   * Tiempo de complejidad del Algoritmo de Ford-Fulkerson.
   * Algoritmo de Edmonds-Karp.
   
  - Algoritmo PageRank
    * Importancia en la Web. Motores de búsqueda.
    * La web y la teoria de Grafos. 
    * Implementación.
 - El grafo aleatorio de Erdos-Renyi
    * Grafos aleatorios. 
    * El modelo de Erdos-Renyi.
    * Aplicaciones.
 - Prueba del teorema fundamental de Programación Lineal. El método del Simplex. Algoritmos.
 - Métodos de puntos interiores. Algoritmos. 
 - Test de primalidad de Miller-Rabin.
 - Grupos que actúan en conjuntos
   * Grupos de permutaciones. La rotación de un cuadrado.
   * El grupo simétrico. Ejemplos.
   * El grupo diedro. Ejemplos.
   * El ciclo de descomposición de una permutación.
 
 - Cadenas de Markov y Martingalas
    * Matrices de transición. Cadenas de Markov y grafos.
    * Cadenas de Markov irreducibles. Distribuciones invariantes.
    * Martingalas. Teorema de convergencia de Martingalas.
    * Tiempos de parada.
 - Caminos aleatorios
   * Definiciones.
   * El principio de reflección. El teorema de Ballot.
   * Retorno al cero. 
   * Lema de Nelson. 
 - Métodos de Montecarlo
    * Definiciones.
    * Método tradicional de integración de MonteCarlo.
    * Caso particular: Simulación de Variables aleatorias.
    * El método Bootstrap.
    * El método  Jackknife.
 - Procesamiento de señales
    * La transformada discreta de Fourier. Las transformaciones de señales discretas.
    * Inversa y dualidad de la transformada discreta de Fourier.
    * FFT. Derivación.
    * La transformada de Fourier bidimensional y  marcaa de agua digital.
    * Imágenes híbridas.
 - Determinismo y Autómatas Finitos
   * Computación. Autómatas finitos deterministicos(DFA) y no deterministicos (NFA). Automáta pushdown (PDA).
   * Máquinas de Turing.
   * Problema de la detención para máquinas de Turing.
   * El mundo de los autómatas celulares.
   
 - Lenguaje natural
   * Métricas en las palabras. Segmentación de palabras.
   * Criptoanálisis con N-gramas.
    
 - Análisis de regresión  y la distancia de Cook.
 - Problema de Waldegrave
   * Introducción a la teoria de Juegos.
   * Solucion del problema. Explicación.
   * El juego Le Her.
  - Ingeniería de factores
    * Métodos de Filtrado
    * Métodos de envoltura
    * Métodos embebidos. Ejemplos.
   - Grupos de algoritmos del Machine Learning
     * Introducción al Machine Learning. Tipos de aprendizaje.
     * Métodos basados en regresión.
     * Algoritmos basados en distancia.
     * Métodos de regularización.
     * Algoritmos basados en árboles.
     * Algoritmos Bayesianos.
     * Algoritmos de agrupación.
     
   - Análisis de componentes principales (PCA)
     * Aplicacion. Eigenfaces para el reconocimiento facial.
 
 

## Lista de temas

 - Transformaciones  de variables aleatorias.
 - El Jacobiano.
 - Funciones generadoras de momentos.
 - Muestreo desde una población normal. 
 - Las distribuciones  T y F.
 - Estimadores  de orden.
 - Ley débil de los grandes números.
 - El teorema del Límite Central.
 - Estimacion.
 - Intervalos de confianza.
 - Prueba de hipótesis. 
 - Pruebas chi-cuadrados.
 - Estimadores suficientes.
 - Teorema de  Rao-Blackwell.
 - Teorema de Lehmann-Scheffé.
 - Estimadores suficientes completos para la clase exponencial.
 - Estimadores Bayesianos.
 - Correlación.
