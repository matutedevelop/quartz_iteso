---
tags:
  - DATA_SCIENCE
  - MATH
  - STATISTICS
---

La regression puede ser pensada de forma abstracta como el proceso por el cual intentamos, *estimar* el valor de una variable america (*ya sea continua, o discreta*) de una instancia. Puede ser llevada acabo atraves de diversos algoritmos como. 

El objetivo de la regresion es predecir un valor numerico, pueden ser el **numero** clientes que acudurian a un hotel que se piensa construir, el **numero** de clientes de un restaurante, **numero** de ventas que podria generar un producto x etc. Esto se logra cuando se conjetura un modelo [[funciones (matematicas)|una funcion]] y ajustando los parametros(*los coeficientes de las pinches variables*) del modelo para aumentar la eficacia de las estimaciones

# Tipos de regression

## Lineal

lo primero que se tiene es que se comparan dos variables vistas en un *scatter plot*




![[Pasted image 20241004172715.png]]
La regresion lineal practicamente lo que nos da, es que nos devuelve la ecuacion de la recta azul que parece explicar el comportamiento de los valores del atributo $A_{j}$



![[Pasted image 20241004172731.png]]

### Como se obtienen los parametros 

con el


![[metodo minimos cuadrados]]




Para verificar el ajuste del modelo, se emplea el coeficiente de Regresion $R^2 \in ()0,1)$ si el ajuste se acerca a 0 esta todo mal chavo, y si se acerca a uno, todo bien chavo $$R^2= \frac{S^2_{xy}}{S^2_{x}S^2_{y}}$$




## lineal multiple

Extension de la lineal, se consideran varias variables, y la estimacion esta dada por una [[suma vectorial]] donde los escalares de cada [[vector|basis]] son calculados cada uno con el [[metodo minimos cuadrados]].

piensese que se devuelve igual una *linea recta* pero en un [[Espacio vectorial- qué es, base y dimensión, axiomas, ejercicios| espacio vectorial]]



## No lineal

Hay algunas cuyo *modelo de estimacion* no es lo suficientemente satisfactorio si se trata tan solo de una linea recta  


---
# $\sigma$


Es necesario modelar la regresion con modelo de calculo en una *variable*?  entonces que es esa variable? *ans: hay muchos tipos de regresion chavo*