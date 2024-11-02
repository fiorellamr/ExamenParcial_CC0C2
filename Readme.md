

# Examen Parcial de Procesamiento del lenguaje natural

**Nombre:** Fiorella Meza Rodriguez

**Código Estudiantil:** 20192730G

En este repositorio se encuentra la resolución del examen que se puede encontrar en formato PDF.
Para el desarrollo del examen se implementaron varios métodos de modelado de lenguaje, incluyendo cálculos de probabilidades con diferentes técnicas de suavizado y modelos de embeddings. Se utiliza un corpus en español, y el proyecto está dividido en múltiples secciones.

## Tabla de Contenidos

1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Requisitos](#requisitos)
3. [Estructura del Proyecto](#estructura-del-proyecto)




---

### Descripción del Proyecto

Este proyecto es un conjunto de implementaciones en Python para el modelado de lenguaje.

- Cálculo de probabilidades de bigramas con diferentes métodos de suavizado.
- Modelos de lenguaje de n-gramas con retroceso (`backoff`) y retroceso estúpido (`stupid-backoff`).
- Implementación de Brown Clustering de forma inicial y con mejoras. 
- Implementación de LSA de forma inicial y con mejoras.
- Embeddings de palabras mediante los modelos CBOW, Skip-Gram con negative sampling, y GloVe.
- Evaluación de los modelos con pruebas de analogías semánticas.

### Requisitos

Para ejecutar este proyecto, se necesitan las siguientes bibliotecas de Python:

- `numpy`
- `collections`
- `time`
- `math`
- `tracemalloc`
- `json`
- `requests`
- `scipy`

Instalarlas usando `pip install`:

```bash
pip install numpy requests scipy
```

### Estructura del Proyecto

El proyecto se divide en las siguientes secciones:

- `Parte 1`: Se responden los ítems a al d
- `Parte 2`: Se responden los ítems e al h
- `Parte 3`: Se implementa Brown Clustering, LSA, CBOW, Skip-gram y GloVe, así como sus mejoras en cuánto a complejidad.
