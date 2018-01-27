---
title: "Estadística I"
subtitle: "Notas de clase"
author: "Kevin Pérez C, Profesor asistente"
output: 
  ioslides_presentation:
    logo: logou.png
    keep_md: yes
    hitheme: tomorrow
    incremental: true
    widescreen: true
    transition: slower
    mathjax: local
    self_contained: false
---

<style>
body {
text-align: justify}
</style>




## Contenido | Cápitulo I - Conceptos y definiciones. 

- Definición y ramas de la Estadística 
- Población y Muestra  
- Parámetro, estadística y estimación  
- Tipos y clasificación de variables

## Contenido | Cápitulo II - Distribuciones de frecuencia

- Distribuciones de frecuencia para datos agrupados
- Distribuciones de frecuencia para datos no agrupados
- Interpretación en el contexto de la Administración  
- Caso de uso 

## Contenido | Cápitulo III - Estadísticas de resumen 

- Medidas de tendencia central 
- Medidas de posición 
- Medidas de variabilidad 
- Medidas de asimetría y apuntamiento 
- Caso de uso 

## Contenido | Cápitulo IV - Representaciones gráficas y AED

- Diagramas de barra, histogramas, polígonos de frecuencia, etc
- Análisis exploratorio de datos 
- Caso de uso 

## Contenido | Cápitulo V - Asociación de variables. 

- Distribuciones conjuntas 
- Distribuciones marginales 
- Covarianza y correlación en variables continuas 
- Correlación en variables categóricas 
- Caso de uso

## Referencias 

- Llinas Solano, Humberto, Estadística descriptiva y distribuciones de probabilidad. Ediciones Uninorte, 2006.

- Martínez Bencardino, Ciro. Estadística y Muestreo. Ecoe Ediciones. Bogotá. 2003.

- Rincon, Luis, Curso elemental de estadística y probabilidad, UNAM, México, 2010.

- Webster, Allen L, Estadística aplicada a los negocios y a la economía, Tercera edición, MacGraw - Hill, 2001.   


## Cápitulo I - Conceptos y definiciones | ¿Qué es Estadística?

La _**Estadística**_ se ocupa del manejo de la información que pueda ser cuantificada. Implica esto la descripción de conjuntos de datos y la inferencia a partir de la información recolectada de un fenómeno de interés. La función principal de la estadística abarca: Resumir, Simplificar, Comparar, Relacionar, Proyectar. Entre las tareas que debe enfrentar un estudio estadístico están:

- Delimitar con precisión la población de referencia o el conjunto de datos en estudio, las unidades que deben ser observadas, las características o variables que serán medidas u observadas.

- Estrategias de Observación: Censo, Muestreo, Diseño de Experimental

- Recolección y Registro de la información


## Cápitulo I - Conceptos y definiciones | ¿Qué es Estadística?

-  Depuración de la información.

- Construcción de Tablas.

- Análisis Estadístico:

      * Producción de resúmenes gráficos y numéricos.
      * Interpretación de resultados.

## Cápitulo I - Conceptos y definiciones | Población y Muestra 

A grandes rasgos podemos decir que una _**Población**_ es el conjunto de toda posible información, o de los objetos, que permite estudiar un fenómeno de interés. 

- Una _**muestra**_ es un subconjunto de información representativa de una población.

- Las _**Variables**_ resultan ser aquellas _características de interés_ que desean ser medidas sobre los objetos o individuos seleccionados. En la mayoría de los casos lo que se pretende es estimar, a partir de la información recolectada de una muestra, características desconocidas de los objetos en dicha población de interés.

## Cápitulo I - Conceptos y definiciones | Población y Muestra 

- Las características desconocidas de una población serán llamadas _**Parámetros**_. Las características calculadas a partir de una muestra son llamadas _**Estadísticas**_. Una Inferencia es una generalización obtenida a partir de una muestra aleatoria.

- Cuando una estadística se utiliza para estimar un parámetro se dice _**Estimador**_ y las realizaciones del estimador en una muestra seleccionada se dicen _**Estimaciones**_

## Cápitulo I - Conceptos y definiciones | Ramas de la estadística 

- _**Estadística descriptiva:**_ Es el conjunto de métodos usados para la organización y presentación (descripción) de la información recolectada. La información recolectada puede ser catalogada de dos maneras: Datos Cualitativos y Cuantitativos.

- _**Estadística inferencial:**_ Comprende los métodos y procedimientos para deducir propiedades (hacer inferencias) de una población, a partir de una pequeña parte de la misma (muestra).

## Cápitulo I - Conceptos y definiciones | Tipos de variables 

- **Numéricas (Cuantitativas):** Valores numéricos 

    * _Continuas_: Número infinito de valores dentro de un rango determinado
    * _Discretas_: Conjunto especifico de valores que pueden ser contados o enumerados 
   
- **Categóricas (Cualitativas):** Un número limitado de distintas categorías
    
    * _Nominales_: Indican pertenencia o relación con una categoria definiendo un atributo 
    * _Ordinales_: Número finito de valores dentro de un rango determinado

## Cápitulo I - Conceptos y definiciones | Escalas de medición de las variables 
- Nominal 

- Ordinal 

- Intervalo 

- Razón 

## Cápitulo I - Conceptos y definiciones | Nominales 

- Se usa para asignar casos individuales a categorías

- Los estudiantes de UPB vienen de muchos Municipios diferentes

- El municipio de origen es una variable Nominal 

## Cápitulo I - Conceptos y definiciones | Ordinales 

- Utilizada para ordenar casos de nominas 

- Los municipios se pueden ordenar según el tamaño de la población 

- La clasificación por tamaño es una variable ordinal

## Cápitulo I - Conceptos y definiciones | Intervalos 

- Se usa para ordenar los casos donde la distancia o intervalo entre cada valor es igual

- Cada país tiene una longitud y latitud

- La longitud y la latitud son variables de intervalo

## Cápitulo I - Conceptos y definiciones | Razón 

- Igual que las variables de intervalo, pero tienen un "cero absoluto"

- Población (población de 0 = extinto)

- Temperatura °C (la escala de Celsius)

## Cápitulo I - Conceptos y definiciones | Resumen

De acuerdo con la posible relación que pudieran guardar los valores de una variable, se cuenta por lo menos con cuatro escalas de medición. Las variables `cualitativas` pueden ser clasificadas de acuerdo a dos escalas: `escala nominal` o `escala ordinal`. Mientras que las variables _**cuantitativas**_ pueden clasificarse por: _**escala de intervalo**_ o _**escala de razón**_.

## Cápitulo II - Distribuciones de frecuencia | Introducción 

La organización de los datos constituye la primera etapa de su tratamiento, pues, facilita los cálculos posteriores y evita posibles confusiones. La organización va a depender del número de observaciones distintas que se tengan y de las veces que se repitan cada una de ellas.

## Cápitulo II - Distribuciones de frecuuencia | Datos no agrupados 

Cuando se tiene un gran número de observaciones pero muy pocas distintas, se organizan en una tabla de frecuencias, es decir, cada uno de los valores acompañado de la frecuencia con la que se presenta. 


## Cápitulo II - Distribuciones de frecuencia 
La tabla 
$$\begin{array}
{|c|c|}
\hline
Valor & Frecuencia \\
\hline
2 & 4  \\
4 & 4  \\
5 & 3  \\
6 & 2  \\
7 & 3  \\
8 & 3  \\
9 & 1  \\
\hline
\end{array}$$

Indica que el valor 2 se repite 4 veces, el valor 4 se repite 4 veces, el valor 5 se repite 3 veces, etc ...   

## Cápitulo II - Distribuciones de frecuencia 

Para efectuar cálculos, sea cuál sea el tipo de distribución, se disponen
los datos de la siguiente forma:

$$\begin{array}
{|c|c|c|c|c|}
\hline
x_i & f_i & F_i & h_i & H_i \\
\hline
x_1 & f_1 & F_1 & h_1 & H_1\\
x_2 & f_2 & F_2 & h_2 & H_2\\
\vdots & \vdots & \vdots & \vdots & \vdots   \\
x_r & f_r & N_r = n & f_r & H_r =1\\
\hline
\end{array}$$
Donde:  

- $n$ representa al número total de observaciones (datos) en la muestra
- $x_i$: variable es la variable de interés.

## Cápitulo II - Distribuciones de frecuencia 

- $f_i$ es la frecuencia absoluta, definida como la cantidad de veces que se repite la observación (dato) en la muestra.  
- $F_i$ es la frecuencia absoluta acumulada, que se obtiene como la suma acumulada de las frecuencias absolutas, $\sum_{i=1}^r f_i$
- $h_i$ es la frecuencia relativa, definida como el cociente (división) de las frecuencias absolutas entre el tamaño de la muestra, $\frac{f_i}{n}$
- $H_i$ es la frecuencia relativa acumulada, que viene dada por la suma acumulada de las frecuencias relativas acumuladas, $\sum_{i=1}^r f_i$

## Cápitulo II - Distribuciones de frecuencia 

- _**Ejemplo 1:**_ Durante el mes de Enero, en la ciudad de Montería, se han registrado las siguientes temperaturas máximas:
32, 31, 28, 29, 33, 32, 31, 30, 31, 31, 27, 28, 29, 30, 32, 31, 31, 30, 30, 29, 29, 30, 30, 31, 30, 31, 34, 33, 33, 29, 29. Construir la tabla de frecuencias.

- _**Ejemplo 2:**_ El número de veces que han ido al cine en el último mes los alumnos de una clase es: 2, 3, 0, 1, 5, 3, 2, 1, 2, 3, 5, 0, 5, 4, 1, 1, 1, 2, 0, 1, 2. Construir la tabla de frecuencias. 

- _**Ejercicio:**_ En un grupo de estudiantes se considera el número de ensayos que necesita cada uno para memorizar una lista de seis pares de palabras. Los resultados fueron: 5, 8, 3, 9, 6, 7, 10, 6, 7, 4, 6, 9, 5, 6, 7, 9, 4, 6, 8, 7.


