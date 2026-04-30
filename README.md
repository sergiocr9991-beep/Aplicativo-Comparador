# Aplicativo-Comparador
# 🧠 Comparador de Precios Inteligente

Aplicación web interactiva para comparar productos y determinar la mejor opción en términos de costo por unidad. Diseñada con enfoque en experiencia de usuario, claridad visual y toma de decisiones basada en datos.

---

## 📌 Descripción

Este proyecto permite ingresar múltiples productos (hasta 4 opciones) con su precio y volumen, y calcula automáticamente cuál ofrece el mejor valor económico.

El sistema analiza el **costo por unidad base**, identifica el ganador y presenta resultados visuales claros, incluyendo:

- Producto más económico por unidad
- Porcentaje de ahorro frente a la siguiente opción
- Tabla comparativa ordenada
- Manejo de empates técnicos

---

## ⚙️ Tecnologías utilizadas

- HTML5
- CSS3 (TailwindCSS)
- JavaScript (Vanilla)
- Lucide Icons
- Google Fonts (Outfit)

---

## 🎯 Funcionalidades

### Comparación de productos
- Entrada de nombre, precio y volumen
- Cálculo automático de precio por unidad
- Ordenamiento por valor económico

### Escalabilidad dinámica
- 2 productos base
- Posibilidad de agregar hasta 4 opciones
- Activación/desactivación de inputs dinámicamente

### Validación de datos
- Evita valores nulos o negativos
- Feedback visual mediante notificaciones (toast)

### Resultado inteligente
- Identificación automática del producto ganador
- Cálculo de ahorro porcentual
- Manejo de empates técnicos

### Visualización avanzada
- UI tipo glassmorphism
- Animaciones suaves
- Indicadores visuales de ganador
- Tabla comparativa responsive

---

## 🧮 Lógica de cálculo

El sistema utiliza la siguiente fórmula:
