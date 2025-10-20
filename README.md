# 🌐 Proyecto Web – Lenguajes de Marcas (EVA1)

## 👥 Grupo
**Nombre del grupo:** {{grupo}}  
**Tema elegido:** {{tema}}  
**Curso:** 1º DAM – IES {{nombre_centro}}

---

## 📝 Descripción del proyecto
Este proyecto consiste en el **desarrollo completo de una web estática** utilizando **HTML5 y CSS3**, aplicando los conocimientos adquiridos en los primeros bloques de la asignatura:  
estructura semántica, texto, enlaces, listas, tablas, formularios, imágenes, objetos multimedia y diseño responsive.

El objetivo es construir una **web temática** (cine, deportes, viajes, tecnología, gastronomía, etc.) correctamente estructurada, accesible y validada según los estándares W3C.

---

## 🧩 Estructura del sitio
El sitio web está compuesto por **al menos tres páginas HTML** enlazadas entre sí.

**Estructura recomendada:**
/
├── index.html # Página principal
├── seccion.html # Página con contenido adicional
├── contacto.html # Formulario de contacto
├── css/
│ └── style.css
├── img/
│ ├── logo.png
│ └── galeria/
└── assets/
└── video.mp4


---

## ⚙️ Requisitos técnicos

### HTML
- Estructura semántica (`<header>`, `<nav>`, `<main>`, `<footer>`).
- Jerarquía correcta de encabezados (`h1 → h2 → h3`).
- Uso de listas (`<ul>`, `<ol>`), enlaces (`<a>`), imágenes (`<img>` con `alt`).
- Inclusión de al menos un elemento multimedia (`<video>`, `<audio>` o `<iframe>`).
- Tabla semántica (`<caption>`, `<thead>`, `<tbody>`, `<th scope="">`).
- Formulario funcional con validación HTML5 (`required`, `type`, `pattern`).

### CSS
- Uso de **selectores**, **colores**, **tipografía** y **bordes**.
- **Flexbox** para alinear o distribuir contenido.
- **CSS Grid** en alguna sección.
- **Responsive Design** mediante `@media (max-width: 768px)`.
- Pseudoestados (`:hover`, `:focus`) y pequeñas transiciones.
- Contraste de color correcto y accesibilidad visual.

### Accesibilidad y metadatos
- Atributos `alt` descriptivos en imágenes.
- Enlaces con texto significativo.
- `<meta charset="UTF-8">`, `<meta name="description">`, y `<title>` únicos.
- Favicon configurado.
- HTML y CSS **validados en W3C**.

---

## 📱 Diseño Responsive
El sitio debe adaptarse correctamente a dispositivos móviles.  
Asegúrate de:
- Reestructurar columnas en pantallas pequeñas.
- Ocultar o simplificar el menú si es necesario.
- Usar imágenes fluidas (`max-width: 100%`).

---

## 🧮 Evaluación

| Criterio | Peso |
|-----------|------|
| Estructura HTML semántica y correcta | 20% |
| Aplicación de CSS (layout, diseño, responsive) | 25% |
| Accesibilidad y validación | 15% |
| Formularios, tablas y multimedia | 20% |
| Presentación, limpieza de código y documentación | 20% |

> Además, se valorará el uso adecuado de **Git y GitHub**: commits frecuentes, mensajes descriptivos y colaboración entre los miembros del grupo.

---

## 🧾 Memoria final (entrega en PDF)
Debe incluir:
1. Objetivo y descripción de la web.  
2. Estructura y organización de carpetas.  
3. Decisiones de diseño (colores, tipografía, maquetación).  
4. Capturas de pantalla (versión escritorio y móvil).  
5. Resultados de validación W3C.  
6. Dificultades encontradas y soluciones aplicadas.

---

## ⚙️ Validación automática (Actions)
Cada vez que subas código a la rama `main`, GitHub ejecutará un **validador automático de HTML y CSS**.

Puedes consultar los resultados en la pestaña **Actions** de este repositorio.  
✅ Si todo está correcto, aparecerá el indicador **verde (✔️)**.

---

## 🚀 Visualización del proyecto
Tu web se publica automáticamente con **GitHub Pages**.

📍 URL del proyecto:  
👉 [{{link}}](https://{{link}})

---

## 📋 Checklist de autoevaluación
- [ ] HTML válido (sin errores en validator.w3.org)  
- [ ] CSS válido  
- [ ] Uso correcto de etiquetas semánticas  
- [ ] Contenido multimedia presente  
- [ ] Tabla y formulario accesibles  
- [ ] Diseño responsive funcional  
- [ ] GitHub Pages activo  
- [ ] Memoria final en PDF entregada  
- [ ] Historial de commits completo  

---

## 🧑‍💻 Autores
| Alumno/a | Tareas principales |
|-----------|--------------------|
| {{Alumno 1}} | HTML y estructura general |
| {{Alumno 2}} | Estilos CSS y diseño responsive |
| {{Alumno 3}} | Formulario, validación y pruebas |

---

## 📅 Fechas de entrega
| Fase | Fecha límite | Tipo de entrega |
|------|---------------|----------------|
| HTML base (estructura) | dd/mm/yyyy | Commit parcial |
| Añadir estilos CSS | dd/mm/yyyy | Commit parcial |
| Responsive y formulario | dd/mm/yyyy | Commit parcial |
| Entrega final + memoria | dd/mm/yyyy | Commit final o Pull Request |

---

## 🏁 Recomendaciones finales
- Trabajad en ramas separadas y haced **Pull Requests** hacia `main`.  
- Revisad la pestaña **Actions** tras cada push.  
- Comprobado en W3C:  
  - [Validador HTML](https://validator.w3.org/)  
  - [Validador CSS](https://jigsaw.w3.org/css-validator/)  
- Mantened el código limpio y bien indentado.  
- Incluid comentarios breves cuando sea necesario.

---

## 📚 Licencia
Proyecto académico desarrollado en el módulo **Lenguajes de Marcas y Sistemas de Gestión de Información (LMSGI)**  
© 2025 – IES {{nombre_centro}}.  
Uso educativo y sin fines comerciales.
