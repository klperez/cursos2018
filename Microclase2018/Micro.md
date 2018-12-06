---
title: "Regresión Lineal"
subtitle: "Micro clase"
author: "MSc. Kevin Pérez C"
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




## Regresión lineal 

La regresión lineal es una metodología de ajuste de curva que utiliza la técnica de mínimos cuadrados para estimar los parámetros que determinan la asociación entre dos variables.

Concretamente se quiere:

- Investigar la naturaleza de la relación
- Construir modelos que describan la relación 
- Predecir el comportamiento de una de ellas a partir de valores de la otra

## Modelo de regresión lineal 

El modelo de regresión lineal simple se puede esquematizar de manera matemática de la siguiente forma:

- El modelo $Y_i =  \mu_i + \epsilon_i = \beta_0 + \beta_1 X_i + \epsilon_i$ donde $\epsilon_i$ son iid $N(0, \sigma^2)$
- Los parámetros $\beta_0$ y $\beta_1$ Son estimados vía _MC_
  $$\hat \beta_1 = Cor(Y, X) \frac{Sd(Y)}{Sd(X)} ~~~ \hat \beta_0 = \bar Y - \hat \beta_1 \bar X$$
- $E[Y ~|~ X = x] = \beta_0 + \beta_1 x$
- $Var(Y ~|~ X = x) = \sigma^2$

## Interpretación de los coeficientes 

La interpretación general se puede enunciarse teniendo en cuenta que son dos los coeficientes y del sentido que tienen en la relación de las variables con respecto a las medidas en las que estas vienen dadas, entonces teniendo en cuenta esto se tiene que:

- $\beta_0$ (El intercepto) es el valor esperado de la respuesta cuando el predictor es 0, esto es, 
$$
E[Y | X = 0] =  \beta_0 + \beta_1 \times 0 = \beta_0
$$
- $\beta_1$ (La pendiente) es el cambio esperado en la respuesta por el cambio de 1 unidad en el predictor.
$$
E[Y ~|~ X = x+1] - E[Y ~|~ X = x] =
\beta_0 + \beta_1 (x + 1) - (\beta_0 + \beta_1 x ) = \beta_1
$$

## Interpretación de los coeficientes 

Para el intercepto hay que tener en cuenta, que no siempre es de interés, por ejemplo, cuando $X = 0$ siendo ($X$ supongamos la presión arterial o la estatura de una persona, etc.) se pierde el sentido de la interpretación, por tanto al considerar 
$$
Y_i = \beta_0 + \beta_1 X_i + \epsilon_i
= \beta_0 + a \beta_1 + \beta_1 (X_i - a) + \epsilon_i
= \tilde \beta_0 + \beta_1 (X_i - a) + \epsilon_i
$$

Entonces, cambiar los valores de  X por un valor $a$ afecta el intercepto, pero no la pendiente. A menudo, $a$ se establece en $X$ para que el intercepto se interprete como la respuesta esperada en el valor promedio de $X$, con lo que podemos hacer interpretable el intercepto.

## Interpretación de los coeficientes 

Ahora, consideremos el impacto de cambiar las unidades de $X$ para hacer interpretable la relación entre $X$ e $Y$. Por ejemplo: Sea $X$ la altura medida en $m$ y $Y$ el peso medida en kg. Entonces $\beta_1$ está dado en $kg/m$. Convertir $X$ a $cm$ implica multiplicar $X$ por 100 $cm/m$. Para obtener $\beta_1$ en las unidades correctas, tenemos que dividir por 100 $cm/m$ para que 
$$
X m \times \frac{100cm}{m} = (100 X) cm
~~\mbox{and}~~
\beta_1 \frac{kg}{m} \times\frac{1 m}{100cm} = 
\left(\frac{\beta_1}{100}\right)\frac{kg}{cm}
$$


## Predicción 

Si nos interesara predecir el resultado en un valor particular del predictor, digamos $X$, el modelo de regresión funciona de la siguiente manera:

$$
\widehat{Y} = \hat \beta_0 + \hat \beta_1 X
$$

## Galton's Data

Veamos los datos utilizados por Francis Galton en 1885. Galton fue un estadístico que inventó el término y los conceptos. De regresión y correlación, fundó la revista Biometrika,además era el primo de Charles Darwin.


```r
library(UsingR); data(galton)
head(galton)
```

```
##   child parent
## 1  61.7   70.5
## 2  61.7   68.5
## 3  61.7   65.5
## 4  61.7   64.5
## 5  61.7   64.0
## 6  62.2   67.5
```





 



