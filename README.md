# Trabajo01 individual Teoría de la Decisión 2026

## Descripción 
 
Este repositorio contiene la resolución de dos problemas de **Teoría de la Decisión bajo Incertidumbre**.
El objetivo de este trabajo es utilizar el sistema de control de versiones: **Git** y la plataforma **Github**, con **R** y **RStudio**, 
así como el código **R** en el repositorio [https://github.com/calote/TDecisionCodigo](https://github.com/calote/TDecisionCodigo) relacionado con los métodos de decisión bajo incertidumbre, para la resolución de los problemas planteados.

Para ello, se ha incluido el archivo en **R** que contiene las funciones necesarias: _teoriadecision_funciones_incertidumbre.R_
 
## Contenido

1. **Problema 1**: Tabla de  decisión con valores inventados y resuelto con cada uno de los métodos o funciones individuales de Incertidumbre por separado (tanto en situación favorable como desfavorable).
2. **Problema 2**: Un problema con  un enunciado que se refiera a una situación real y su resolución se llevará a cabo con la función R que devuelve la resolución de todos los métodos en una única tabla. 

Cada uno de los problemas, incluye también 5 preguntas de Verdadero o Falso, en las que al menos hay una verdadera y una falsa.

## Metodología
Los métodos empleados han sido los siguientes:

**Wald (Criterio pesimista o minimax-maximin)**: En el peor de los casos, se obtiene lo mejor posible. Es un enfoque conservador.

**Optimista (Criterio maximax)**: Es el enfoque opuesto al de Wald, para cada alternativa, se supone que pasará lo mejor y se elige la que dé mejor valor.

**Hurwicz**: Combina las actitudes pesimista y optimista. Se usa un coeficiente de optimismo $\alpha$ para ponderar los mejores y peores resultados de cada opción.

**Savage (Criterio de costes de oportunidad)**: Aquí se trata de minimizar el "arrepentimiento" por no prever correctamente el estado de la naturaleza, es decir, la diferencia entre lo que se podría haber ganado y lo que realmente se ganó. Se selecciona la opción que minimiza el máximo arrepentimiento. 

**Laplace**: Este criterio asume que todas las situaciones son equiprobables y se elige la opción con el mejor promedio de resultados.

**Punto Ideal**: Consiste en seleccionar la opción cuya distancia a un punto ideal (el mejor resultado posible en cada criterio) sea mínima.
 