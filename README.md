# Tesis Miretti – Comparación de Autoencoders para Detección de Anomalías

Tesis de Maestría en Ciencia de Datos – ITBA.
Autoencoders para la Detección No Supervisada de Anomalías en Datos de Cardiotocografía: un Estudio Comparativo de Arquitecturas.

**Autora:** María Carolina Miretti (Leg. 106054)
**Directora:** Dra. María Juliana Gambini

## Datasets

Todos provienen del UCI Machine Learning Repository y se distribuyen bajo licencia CC BY 4.0.

### Dataset principal

**Cardiotocography (CTG)**
- Archivo: `fetal_health.csv`
- Fuente: https://archive.ics.uci.edu/dataset/193/cardiotocography
- DOI: 10.24432/C51S4N
- Autores: Campos, D. y Bernardes, J. (2000)
- 2126 registros, 21 variables clínicas. Variable objetivo `fetal_health`: 1 = normal (1655), 2 = sospechoso (295), 3 = patológico (176).

### Datasets secundarios (validación de generalización)

**Arrhythmia**
- Fuente: https://archive.ics.uci.edu/dataset/5/arrhythmia
- DOI: 10.24432/C5BS32
- Autores: Guvenir, H. A., Acar, B., Muderrisoglu, H. y Quinlan, R. (1997)
- 452 registros, 279 variables originales (274 utilizadas en la tesis).

**Heart Disease (Cleveland)**
- Fuente: https://archive.ics.uci.edu/dataset/45/heart-disease
- DOI: 10.24432/C52P4X
- Autores: Janosi, A., Steinbrunn, W., Pfisterer, M. y Detrano, R. (1989)
- 303 registros, 13 variables.

**Statlog (Heart)**
- Fuente: https://archive.ics.uci.edu/dataset/145/statlog+heart
- DOI: 10.24432/C57303
- 270 registros, 13 variables.

## Estructura del repositorio

- `fetal_health.csv`: dataset principal.
- `data/`: datasets secundarios (Arrhythmia, Cleveland, Statlog).
- `codigo/`: scripts y notebooks de los experimentos.
- `resultados/`: tablas y figuras.

## Reproducibilidad

Semilla aleatoria: 42. Python 3.10; TensorFlow/Keras y scikit-learn.
