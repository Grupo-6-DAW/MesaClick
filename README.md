# MesaClick

Aplicación web para la reserva y gestión de mesas en restaurantes.  
En esta **Fase 1 (Maquetación)** el proyecto reúne únicamente la estructura semántica en **HTML5** y la presentación visual en **CSS3**, sin programación ni lógica de backend todavía.

## Estructura del proyecto

```text
MesaClick/
├── index.html             # Página de inicio del proyecto
├── formulario.html        # Página con el formulario de reserva maquetado
├── css/
│   └── estilos.css        # Hoja de estilos compartida por ambas páginas
├── img/
│   └── mesaclick-banner.jpg
└── README.md
```

## Convenciones técnicas

- **HTML5 semántico:** uso de `<header>`, `<nav>`, `<main>`, `<section>` y `<footer>`, junto con listas (`<ul>`), imágenes (`<img>`) y enlaces (`<a>`) entre páginas.
- **CSS3 externo (`css/estilos.css`):**
  - Paleta de colores centralizada mediante variables en `:root` (`--color-primario`, `--color-secundario`, `--color-fondo`, `--color-superficie`, `--color-texto`, `--color-borde`).
  - Combinación de selectores de etiqueta, de clase (`.tarjeta`, `.boton-principal`, etc.) y de ID (`#encabezado-principal`, `#menu-navegacion`, etc.).

## Cómo visualizarlo localmente

1. Clona el repositorio y ubica la rama correspondiente.
2. Abre `index.html` directamente en tu navegador o usando la extensión **Live Server** en VS Code.

## Flujo de trabajo con Git

- `main`: rama principal estable.
- `fase-1-maquetacion`: rama de integración para la Fase 1.
- Ramas personales por integrante para desarrollar y subir sus aportes antes de integrarlos a `fase-1-maquetacion`.

```bash
# Guardar cambios en tu rama
git add .
git commit -m "Descripción clara de los cambios"
git push -u origin <tu-rama>
```

Al completar la fase, se unirá `fase-1-maquetacion` con `main` mediante **Merge** o **Pull Request**.
