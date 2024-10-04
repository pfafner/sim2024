# Modelación y Simulación 2024

Este es un curso introductorio a la modelación y simulación computacional, y en general al cómputo científico. Tiene como objetivo cubrir algunos temas relacionados con métodos numéricos computacionales, y se estudian algoritmos para cálculo científico y su implementación computacional. Se estudian tres grandes temas: 

(1) Modelación continua y discreta, principalmente mediante EDO.
(2) Optimización numérica continua y discreta,
(3) Simulación de fenómenos mediante distribuciones de probablidad. 

La primera parte el curso se enfoca en relacionados con modelos diferenciales: estudiamos algunas EDO y EDP clásicas, desde el enfoque de la construcción del modelo diferencial. Aprederemos algunas técnicas para analizar cualitativamente los modelos diferenciales, y aprenderemos algoritmos numéricos para la solución de EDOs y sistemas de EDOs. Introducimos algunos elementos de modelación con EPDs y un algoritmo de diferencias finitas para su solución numérica.

En el segundo bloque, introducimos los temas de optimización numérica. Iniciamos formulando problemas de programación lineal, y sus propiedades, e introducimos el algoritmo Simplex. Veremos aplicaciones de programación lineal en problemas de transporte y problemas de asignación. En seguida, hacemos una revisión de algunos métodos de optimización no lineal, principalmente los métodos de gradiente, así como métodos de la familia de gradiente conjugado y métodos quasi-Newton. El tema culmina una introducción a algunos métodos de optimización combinatoria y discreta. 

En la parte final del curso hacemos uso de distribuciones de probabilidad, para modelar aquellos fenómenos en los que interviene algún componente estocástico. Abordaremos algoritmos numéricos para la generación de muestras aleatorias de distribuciones de probabilidad, y aplicaremos estos algoritmos al estudio de ciertos problemas de modelación. Hacemos una revisión de teoría de colas, y cómo simularlas de forma computacional. Finalmente, introducimos algunos métodos de estadística bayesiana para simulación.

**Importante!!** El curso cuenta con una parte práctica extensiva, en la que el estudiante implementará en código computacional cada uno de los algoritmos estudiados. Parte fundamental del curso consiste en utilizar las herramientas aprendidas en varios proyectos aplicados donde se trabajará con datos reales y comunicar los resultados mediante reportes técnicos y seminarios.


# Prerrequisitos

Se recomienda que los estudiantes antes del curso estén habituados con los temas:
* Cálculo en una y varias variables
* Álgebra lineal y álgebra matricial
* Ecuaciones diferenciales ordinarias
* Probabilidad y estadística
* Un curso de Programación.


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-sim2024.pdf){:target="_blank"}

### Horario
<div id='id-horario'/>

* Martes de 16:30 a 18:50 CIT-301, y Jueves de 17:20 a 18:50 CIT-215.

### Office Hours
<div id='id-office'/>

* Viernes de 18:00 a 19:00.


# Material del curso
<div id='id-material'/>

**No.**  | **Fecha**    | **Tópicos**                                                   | **Recursos**
-------- | ------------ | ------------------------------------------------------------- |  ---------------------------------
01       | 04.07.2024   | Inicio del curso. | 
02       | 09.07.2024   | Generalidades sobre modelación. <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"} |  
03       | 09.07.2024   | EDO: clasificación, soluciones, teorema de existencia y unicidad. <br/> | [Apuntes de EDO](lectures/Apuntes_EDO.pdf){:target="_blank"} 
04       | 11.07.2024   | Ejemplos existencia y unicidad. Análisis cualitativo de soluciones. <br/> | [Análisis cualitativo](lectures/Analisis_Cualitativo.pdf){:target="_blank"} 
05       | 16.07.2024   | Campos direccionales. Diagramas de fase.  |  
06       | 16.07.2024   | Ecuaciones autónomas. Puntos de equilibrio.  | 
L1       | 18.07.2024   | **Entrega:** <br/> ejercicios 1, 2 y 3, jueves 25 de julio. <br/> ejercicios 4 y 5, jueves 01 de agosto. | [Lab 01](labs/Lab01.pdf){:target="_blank"} <br/>  
07       | 25.07.2024   | Algoritmos numéricos para hallar ceros. Método de Newton multidimensional. | Burden-Faires, Cap. 2 <br/> Burden-Faires, Cap. 10
08       | 30.07.2024   | Clasificación de puntos de equilibro en R2. | [Clasificación](https://terpconnect.umd.edu/~petersd/246/stab.html){:target="_blank"} 
09       | 30.07.2024   | Solución numérica de EDOs: Método de Euler, Heun, y método de Taylor de orden 2. | Burden-Faires, Cap. 5 
L2       | 01.08.2024   | **Entrega:** <br/> ejercicios 1 y 4, jueves 01 de agosto. <br/> ejercicios 2, 3 y 5, jueves 08 de agosto. | [Lab 02](labs/Lab02.pdf){:target="_blank"} 
10       | 06.08.2024   | Método de Runge-Kutta orden 4. Solución de sistemas de EDO. | Burden-Faires, Cap. 5  
L3       | 08.08.2024   | **Para entregar: martes 20 de agosto** <br/>  | [Lab 03](labs/Lab03.pdf){:target="_blank"} 
11       | 22.08.2024   | Modelos de población. <br/>  |   
12       | 27.08.2024   | Simulación de modelos de población. <br/>  |   
L4       | 29.08.2024   | **Para entregar: jueves 05 de septiembre** <br/>  | [Lab 04](labs/Lab04.pdf){:target="_blank"} 
13       | 03.09.2024   | Modelos de difusión. <br/>  |   
L5       | 05.09.2024   | **Para entregar: jueves 19 de septiembre** <br/>  | [Lab 05](labs/Lab05.pdf){:target="_blank"} 
14       | 19.09.2024   | Programación Lineal. Forma estándar. <br/> |  
15       | 24.09.2024   | Bases y soluciones básicas. Algoritmo Simplex. <br/> [Ejemplo 1](code/Ejemplo1.ipynb){:target="_blank"} [Ejemplo 3](code/Ejemplo3.ipynb){:target="_blank"} | Taha, Cap. 1 a 3
L6       | 26.09.2024   | **Para entregar: jueves 03 de octubre** <br/>  | [Lab 06](labs/Lab06.pdf){:target="_blank"} 
16       | 01.10.2024   | Modelo de transporte. Modelo de asignación. <br/> | Taha, Cap. 5
17       | 03.10.2024   | Fundamentos de optimización continua. <br/> [Aula 20](aulas/Aula20.pdf){:target="_blank"} | 
18       | 03.10.2024   | Optimización 1-dimensional. <br/> [Aula 21](aulas/Aula21.pdf){:target="_blank"} | 


# Proyectos
<div id='id-proyectos'/>

## Primer Proyecto 

**No.**  | **Fecha**    | **Tópicos**                                                     | **Recursos**
-------- | ------------ | --------------------------------------------------------------- |  ---------------------
1        |    |             | 

# Referencias
<div id='id-ref'/>

### Textos: 

* [S. Ross (2022). *Simulation*. 6th Ed.](http://library.lol/main/173766BF2DE3D62A9816564E7CDA4239){:target="_blank"}

* [K. Atkinson, W. Han y D. Stewart (2009). *Numerical Solution of Ordinary Differential Equations*.](https://homepage.divms.uiowa.edu/~atkinson/papers/NAODE_Book.pdf){:target="_blank"}

### Referencias adicionales:

* [R. Burden, A. Burden, D. J. Faires (2017). *Análisis numérico.*](http://library.lol/main/87525D7D988D11F87963D6832EAA9493){:target="_blank"}

* [J. Matousek, B. Gärtner, (2007). *Understanding and Using
Linear Programming*.](http://library.lol/main/4E0F73DC6A1E36D157A69F09D3834452){:target="_blank"}

* [M. Martcheva (2010). *An Introduction to Mathematical Epidemiology*.](http://library.lol/main/B49DE076CF4518052FFBA1E0B8D3BD1F){:target="_blank"}

* [C. Robert y G. Casella (2004). *Monte Carlo Statistical Methods*.](http://library.lol/main/A910C1F6887E40EE92E4394860CFCAB8){:target="_blank"}

* [C. Robert (2007). *The Bayesian Choice*.](http://library.lol/main/8AEA3ED2A08F9CAA0D58873CE3A6A45B){:target="_blank"}

* [B. Zeigler, A. Muzy y E. Kofman (2019). *Theory of Modeling and Simulation*.](http://library.lol/main/E2ECE9CB0E7D0B070742712BF34FB081){:target="_blank"}

* [J. A. Sokolowski y C. M. Banks (2010). *Modeling and Simulation Fundamentals*.](http://library.lol/main/F4F7B06B2CFA15FD273DBFE01B09D8EA){:target="_blank"}
    

--- 
