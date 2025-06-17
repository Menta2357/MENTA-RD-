# MENTA–RD₉

**Modelo estructural para localizar los ceros de la función zeta de Riemann mediante resonancia digital.**

Utiliza la suma digital iterada en base 9 (`RD₉`) aplicada a una red de osciladores acoplados a los ceros reales conocidos. Sin evaluar `ζ(s)`, sin derivadas, y con error medio < 0.013.

## Fórmula base

\[
ζ_{RD}(t) = \sum_{n=1}^{N} RD₉\left[\sin\left(\frac{π·t}{tₙ}\right)\right]
\]

## Contenido

- `zeta_rd.py`: Código para generar ζ_RD(t)
- `zeros_riemann.csv`: Primeros 1000 ceros reales
- `resultados.md`: Errores y hallazgos
- Imágenes utilizadas para divulgación

## Resultados

- Detecta ceros reales de ζ(s) sin evaluarla
- Error medio estructural: 0.0126
- Máximo error: 0.025
- 100% ceros localizados bajo umbral ε < 0.05

## Licencia

Este proyecto se distribuye bajo licencia Apache 2.0.
