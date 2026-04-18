# 🌐 Clean Diagonal Sections

Un proyecto HTML + CSS que crea secciones con divisiones diagonales modernas usando `clip-path`, sin vectores ni cálculos complejos.

---

## ✨ Vista del proyecto

Este diseño simula el estilo de landing pages modernas, con cortes diagonales limpios entre secciones.

---

## 🧠 Concepto

El efecto se logra usando:

- HTML estructurado en secciones
- CSS con `clip-path: polygon()`
- Sin JavaScript
- Sin SVG
- Sin cálculos matemáticos manuales

---

## 🚀 Tecnologías usadas

- HTML5
- CSS3

---

## 📁 Estructura del proyecto
/project
├── index.html
├── styles.css
└── README.md

---

## 🎨 Cómo funciona

Cada sección usa `clip-path` para recortar su forma y crear diagonales entre bloques.

Ejemplo:

```css
.blue {
  clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
}
