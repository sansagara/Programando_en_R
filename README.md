# Programando en R

Traducción al español del curso [R_Programming_Alt de swirl](https://github.com/swirldev/swirl_courses/tree/master/R_Programming_Alt). 

**Descripción**

El paquete de R [swirl](http://swirlstats.com/) permite crear cursos interactivos que se ejecutan desde la propia consola de R, por lo cual el estudiante puede ejecutar la instrucciiones directamente en R en la medida que avanza su curso. Existen varios cursor en el repositorio de swirl, pero todos estan en ingles.

**Objetivo**

El objetivode este proyecto es disponer un completo curso interactivo de R en el idioma español para aquellos hispanohablantes interesados en aprender este lenguaje de programación.

**Prerrequisitos**

Para acceder a este curso debes tener instalado el paquete [swirl](http://swirlstats.com/):

```{r}
install.packages('swirl')
```

**¿Como ejecutar el curso?**

Para realizar este curso debemos primero instalarlo desde este repositorio en github, así:

```{r}
library(swirl)
install_course_github('josersosa','Programando_en_R')
```

Y lo iniciamos con:

```{r}
swirl()
```

Al comienzo nos solicita un nombre para identificarnos y almacenar los avances en el caso que deseemos pausar el curso. Las primeras informaciones estan en ingles porque provienen del paquete swirl. Luego seleccionamos el curso _Programando en R_ y a partir de ahí todo estará traducido.

Por último, cuando hayamos terminado, podemos desinstalar el curso con:

```{r}
uninstall_course("Programando_en_R")
```


**Avance del proyecto**

Hasta ahora tiene una avance del **8.3%** en la traducción.

