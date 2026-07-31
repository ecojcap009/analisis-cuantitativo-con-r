# Análisis Cuantitativo con R — Notebooks de estudio

Cuadernos de Jupyter (kernel R) con implementaciones ejecutables de los conceptos
tratados en cada capítulo del libro *Análisis cuantitativo con R: matemáticas,
estadística y econometría*. Son apuntes de estudio propios: código R comentado,
explicaciones en mis propias palabras y verificación de resultados, no una copia
del texto del libro.

## Contenido

| Notebook | Capítulo | Temas |
|---|---|---|
| [Cap01_Estructura_Lenguaje_Sintaxis_R.ipynb](Cap01_Estructura_Lenguaje_Sintaxis_R.ipynb) | I | Instalación, sintaxis, vectores, matrices, funciones, `apply`, `data.frame`, listas, fórmulas, factores |
| [Cap02_Algebra_Lineal_Calculo_R.ipynb](Cap02_Algebra_Lineal_Calculo_R.ipynb) | II | Álgebra vectorial/matricial, ecuaciones, descomposición matricial, cálculo diferencial e integral, EDO, optimización, variable compleja |
| [Cap03_Analisis_Datos_Estadistica_Descriptiva_R.ipynb](Cap03_Analisis_Datos_Estadistica_Descriptiva_R.ipynb) | III | Importación de datos, exploración, estadísticos descriptivos, visualización |
| [Cap04_Distribuciones_Probabilidad_R.ipynb](Cap04_Distribuciones_Probabilidad_R.ipynb) | IV | Combinatoria, distribuciones discretas y continuas, Teorema del Límite Central |
| [Cap05_Inferencia_Estadistica_R.ipynb](Cap05_Inferencia_Estadistica_R.ipynb) | V | Intervalos de confianza, contrastes de hipótesis, regresión lineal (MCO), ANOVA |
| [Cap06_Programacion_Simulacion_R.ipynb](Cap06_Programacion_Simulacion_R.ipynb) | VI | Generación de valores aleatorios, simulación de Monte Carlo, verificación del TCL |

Cada notebook sigue la numeración de secciones del capítulo correspondiente del libro
(p. ej. `2.3` = Sistemas de ecuaciones lineales), con celdas de código autocontenidas y
referencias de página para quien quiera consultar la fuente original.

## Sobre el contenido y los derechos de autor

Este repositorio **no incluye el texto ni las páginas del libro**. El libro es una obra
con copyright vigente:

> Liviano Solís, D. & Pujol Jover, M. (2017). *Análisis cuantitativo con R:
> matemáticas, estadística y econometría*. Editorial UOC. ISBN 978-84-9116-804-1.

Lo que contiene este repositorio es código R original ejecutable y explicaciones
propias, escritas a partir del estudio del libro — no una reproducción de su
contenido. Si necesitas el libro, puedes adquirirlo directamente en
[Editorial UOC](https://www.editorialuoc.com).

## Cómo ejecutar

Los notebooks requieren un kernel de R (`IRkernel`). Para ejecutarlos:

```bash
# Instalar el kernel de R para Jupyter (una sola vez, desde una consola de R)
# install.packages('IRkernel')
# IRkernel::installspec()

jupyter lab
```

También pueden abrirse directamente en Google Colab seleccionando **Runtime → Change
runtime type → R**.

## Licencia

El código de estos notebooks se publica bajo licencia MIT (ver [LICENSE](LICENSE)).
Esta licencia cubre únicamente mi código y mis anotaciones; no se extiende al
contenido del libro citado, cuyos derechos pertenecen a sus autores y a Editorial UOC.
