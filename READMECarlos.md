---
# Laboratorio-Clon-Visual
## Clon: Netflix Qué componentes Bootstrap utilizamos: 
## Mafer: carrusel de imágenes con autoreproducción, carousel-caption
## ● Qué parte desarrolló el participante:
## 🎯 Carlos: Grid system

## ¿Qué plataforma clonamos?
**Netflix** - Plataforma de streaming
---
## 🧩 Componentes Bootstrap que utilicé

| Componente | Propósito |
|------------|-----------|
| `container-fluid` | Ancho completo estilo Netflix |
| `row` + `col` | Sistema de filas y columnas |
| `row-cols-2`, `row-cols-sm-3`, `row-cols-md-4`, `row-cols-lg-5`, `row-cols-xl-6` | Control de columnas por dispositivo |
| `g-2`, `g-sm-3` | Espaciado entre tarjetas |

---

## 🎨 Estilos personalizados que creé

| Clase CSS | Propósito |
|-----------|-----------|
| `.movie-card` | Tarjetas de acción, dramas y populares (imagen 2:3 + título centrado) |
| `.comedy-card` | Tarjetas de comedias (imagen 16:9 + título + descripción + botón "Ver más") |
| `.trending-card` | Tarjetas de tendencias (imagen 2:3 + título + botón "Reproducir") |
| `.row-title` | Títulos de cada fila |
| `.netflix-header` | Barra de navegación superior |
| `.movie-row` | Espaciado entre filas |

### Efectos interactivos

- **Hover en tarjetas:** Escala (1.05) + sombra para efecto flotante estilo Netflix
- **Hover en botones:** Cambio de color para feedback visual

---

## 🎨 Colorimetría aplicada

```css
/* Fondo principal estilo Netflix */
body {
    background-color: #141414;
}

/* Fondo de todas las tarjetas */
.movie-card, .comedy-card, .trending-card {
    background-color: #1f1f1f;
    border: none;
    color: white;
}

/* Botón rojo Netflix */
.btn-danger-custom, .btn-play {
    background-color: #e50914;
}

.btn-danger-custom:hover, .btn-play:hover {
    background-color: #f40612;
}
/* Adriana: Navbar Para la navbar se utilizo una plantilla de bootstrap en combinacion con otra her herramiento de navegacion y pestanas */
/* Israel: Cards acción */
/* Bruno: Cards... Maquetación de tarjetas de contenido responsivas (Cards) con animaciones interactivas de zoom y personalización de botones temáticos mediante CSS y Bootstrap. */
/* Miguel: Cards comedias */
/* Rodrigo: Formularios */
/* Mafer: Sección principal ● Revisa el siguiente link sobre markdown : https://www.markdownguide.org/cheat-sheet/ */
