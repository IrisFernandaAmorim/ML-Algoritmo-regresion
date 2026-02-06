# 🍋 Machine Learning Supervisado – Algoritmos de Regresión

Este repositorio acompaña una clase práctica de **Machine Learning Supervisado**, centrada en **algoritmos de regresión**, usando Python y Jupyter Notebook.

Está pensado para personas que están empezando en análisis de datos y Machine Learning.

---

## 🧠 La historia del proyecto

Imagina un **puesto de limonada** 🍋.

Cada día registramos:
- la temperatura
- la humedad
- si es fin de semana
- cuántas limonadas se vendieron

El objetivo es responder a una pregunta sencilla:

> **¿Cuántas limonadas venderemos mañana?**

A partir de este problema realista, aprendemos cómo funcionan los modelos de regresión.

---

## 🤖 ¿Qué es Machine Learning Supervisado?

Machine Learning Supervisado es cuando:
- tenemos **datos de entrada** (X)
- tenemos **la respuesta correcta** (y)
- y enseñamos al modelo usando ejemplos

Ejemplo en este proyecto:

- X → temperatura, humedad, fin de semana  
- y → ventas de limonada

El modelo aprende la relación entre X e y para hacer predicciones.

---

## 📈 ¿Qué es un problema de regresión?

Un problema de **regresión** es cuando queremos predecir un **número**.

Ejemplos:
- precio de una casa
- tiempo de entrega
- ventas diarias

En este proyecto:
> predecimos **cuántas limonadas se venden**

---

## 📊 Tipos de regresión usados en el proyecto

### 1️⃣ Regresión Lineal
- Usa **una sola variable**
- Dibuja una **línea recta**
- Ideal para empezar

Ejemplo:
> Temperatura → Ventas

---

### 2️⃣ Regresión Polinómica
- Usa una sola variable
- Dibuja una **curva**
- Sirve cuando una línea recta no es suficiente

Ejemplo:
> Mucho calor extremo puede bajar las ventas

---

### 3️⃣ Regresión Múltiple
- Usa **varias variables**
- El modelo aprende una **superficie**
- Se acerca más a la realidad

Ejemplo:
> Temperatura + Humedad + Fin de semana → Ventas

---

## 📁 Estructura del repositorio

```
ml-regresion-limonada/
│
├── data/
│   └── limonada_ventas.csv     # Dataset para prácticas
│
├── notebooks/
│   ├── ML_regresion.ipynb
│   │
├── README.md
└── .gitignore
```

## 📊 Dataset

El dataset es ficticio, creado solo para aprendizaje.

Cada fila representa un día de ventas del puesto de limonada.

Columnas principales:

- temperatura → grados Celsius

- humedad → porcentaje

- fin_de_semana → 1 = sí, 0 = no

- ventas → limonadas vendidas

## 🛠️ Librerías usadas

Este proyecto utiliza:

- pandas → manejo de datos

- numpy → cálculos numéricos

- matplotlib → gráficos

- scikit-learn → modelos de Machine Learning

- jupyter → notebooks interactivos

## 📦 Instalación de dependencias

Se recomienda usar un entorno virtual.

1️⃣ Crear entorno virtual
```
python -m venv venv
```

Activar:

- Mac / Linux:
```
source venv/bin/activate
```

- Windows:
```
venv\Scripts\activate
```

2️⃣ Instalar librerías
```
pip install pandas numpy matplotlib scikit-learn jupyter
```

▶️ Cómo usar este repositorio

Clona el repositorio:

```
git clone https://github.com/tu-usuario/ml-regresion-limonada.git
```

Entra en la carpeta:
```
cd ml-regresion-limonada
```

Abre los notebooks:

```
jupyter notebook
```

🧩 Qué viene después

Este proyecto prepara el terreno para aprender:

- evaluación de modelos
- división de datos (train / test)
- overfitting y underfitting
- pipelines de Machine Learning
- uso de modelos en aplicaciones reales

💬 Mensaje final

“Antes de escribir mucho código, entendemos el dibujo.
Si entiendes el gráfico, entiendes el modelo.”

¡Disfruta el aprendizaje! 🍋🚀

---

**Autora:** Iris Fernanda Amorim  
Python · Data · ML Supervisado

Proyecto educativo – uso libre para aprendizaje.