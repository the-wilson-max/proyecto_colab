# Predicción de Precios de Viviendas en California

Este proyecto utiliza distintos modelos de regresión (lineal, polinomial y red neuronal) para predecir el valor medio de las viviendas en California utilizando el dataset `California Housing` de `scikit-learn`.

---

## 🎯 Objetivo

Predecir el precio promedio de una vivienda utilizando variables como:

- Número promedio de habitaciones (`AveRooms`)
- Edad de la vivienda (`HouseAge`)
- Ingreso medio por zona (`MedInc`)
- Número promedio de dormitorios (`AveBedrms`)

---

## 🧪 Metodología

1. **Carga y limpieza de datos**
   - Se eliminan outliers extremos para mejorar la precisión.
   - Se seleccionan las variables más significativas.

2. **Modelos implementados**
   - 📈 Regresión Lineal Múltiple
   - 🔁 Regresión Polinomial (grado 2)
   - 🤖 Red Neuronal (Keras con TensorFlow)

3. **Evaluación**
   - Se usaron métricas de regresión: `R²` y `MSE`.
   - Se graficaron los valores reales vs. predichos.

4. **Estructuras usadas**
   - Condicionales (`if`), bucles (`for`), listas, diccionarios, arrays (`numpy`).

---

## 📊 Resultados

| Modelo                     | R² Score | MSE    |
|---------------------------|----------|--------|
| Regresión Lineal Múltiple | 0.5223   | 0.4553 |
| Regresión Polinomial (g2) | 0.5430   | 0.4356 |
| Red Neuronal (Keras)      | 0.5531   | 0.4247 |

La red neuronal mostró el mejor rendimiento general.

---

## 📁 Estructura del Proyecto

