# bda-modulo-3-evaluacion-final-Ani-sabina
La forma general se conserva ✅

## Comparando ambos gráficos:

- Antes
concentración principal aproximadamente entre 50.000 – 100.000
distribución asimétrica hacia la derecha (right skewed)
cola larga con salarios altos hasta ~400.000

- Después
sigue existiendo la misma concentración principal
la cola derecha se mantiene
no desaparecen los valores extremos

Interpretación:
El proceso de imputación no alteró la estructura global de la distribución.

## Aumenta la frecuencia en la zona central (esperable) ✅

- En el gráfico después de imputar se ve:
barras más altas en el rango central (~60k–90k)

Esto ocurre porque:
los valores faltantes fueron reemplazados
el algoritmo encontró registros similares y asignó valores dentro del patrón dominante

- Interpretación:
Los valores imputados se integraron en el rango salarial más frecuente del dataset.

## Se analizó la distribución de la variable Salary antes y después del proceso de imputación mediante KNNImputer.

Tras comparar ambos histogramas, se observó que la forma general de la distribución se mantiene estable, conservando la asimetría positiva original y el rango de valores extremos.

No se detectaron concentraciones artificiales de valores, lo que indica que la imputación generó estimaciones consistentes con la estructura original de los datos.

