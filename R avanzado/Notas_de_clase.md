---
title: "Programación avanzada en R"
subtitle: "Programa de Estadística - Notas de clase"
author: "MSc. Kevin Pérez C, Docente auxiliar"
output: 
  ioslides_presentation:
    logo: logo.png
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




## Contenido | Cápitulo I - Fundamentos de R

- Estructuras de datos en R
- Subconjuntos de objetos en R (Indexación)
- Operaciones vectorizadas 
- Fechas y Horarios 
- Manipulación de cadenas de caracteres 

## Contenido | Cápitulo II - Estructuras de la programación en R 

- Estructuras de control 
- Llamado a funciones 
- Escritura de funciones 
- Ambientes de trabajo y funciones (_Lexical Scoping_)
- _Debugging_ - _Profiling_
- Simulación en R

## Contenido | Cápitulo III - Programación funcional en R 

- Que es la programación funcional 
- Conceptos de la programación funcional 
- _Scope_ - _Closures_
- _Higher-Order Functions_
- _Filter, Map, and Reduce_

## Contenido | Cápitulo IV - Programación paralela en R

- _Benchmarking_
- Códigos eficientes en R
- Mejora del rendimiento: velocidad y memoria
- _Profiling_
- _The parallel Package_

## Contenido | Cápitulo V - _Interfacing_ R a otros lenguajes 

- Comenzando con C ++
- Atributos y clases 
- _Rcpp sugar_
- _The STL_
- _Snow_

## Contenido | Cápitulo V - Programación orientada a objetos 

- Sistemas POO
- _S3_
- _S4_
- Otros sistemas _RC_, _R6_

## Contenido | Cápitulo V - Paquetes en R 

- _The devtools Package_
- Documentación
- Datos dentro del paquete 
- _Testing_
- Reglas del CRAN y licencias 
- Diseño de software   
- _Cross Platform Development_
- Integración continua 

## Contenido | Cápitulo VI - Seminario: Procesamiento escalable de datos 

- Trabajando con grandes volúmenes de información 
- Procesamiento y análisis de datos con _bigmemory_
- Trabajando con _iotools_
- Big Data con R: _Spark_ y _R_ el paquete _Sparklyr_ 

## **Referencias**

- Advanced R, Hadley Wickham, Chapman & Hall’s R Series, New York, 2013.
- Mastering Software Development in R , Roger d. Peng et all, LeanPub. 2016. 
- R Programming for Data Science, Roger d. Peng. LeanPub. 2015. 
- R for Data Science: Import, Tidy, Transform, Visualize, and Model Data, Hadley Wickham et all, O’REiLLY, New York, 2016.
- The Art of R Programming: A Tour of Statistical Software Design, Norman Matloff, New York, 2013.  
