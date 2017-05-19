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
 
## Acerca de temas de presentación y complementarios (Por actualizar)

 - Regresión Jackknifed.
 - Bootstrap.
 - Problema de Waldegrave.
 - Distancia de Cook.
 - El rol de la probabilidad en la Teoria de Señales.

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
