# MesaClick

Esqueleto visual de la aplicación **MesaClick** (Fase 1: Maquetación).  
En esta etapa el proyecto contiene únicamente estructura y presentación (**HTML5** y **CSS3**), sin programación todavía.

## Estructura y requisitos del código

- **Dos páginas enlazadas:**
  - Página de inicio sobre el tema del proyecto (`MesaClick`).
  - Página con un formulario maquetado (sin funcionalidad aún).
- **HTML5 semántico:**
  - Uso de `<header>`, `<nav>`, `<main>`, `<footer>`.
  - Al menos una lista (`<ul>` o `<ol>`), una imagen (`<img>`) y un enlace (`<a>`).
- **Hoja de estilos externa (`.css`):**
  - Un único archivo `.css` enlazado a ambas páginas.
  - Uso de selectores de etiqueta, de clase (`.clase`) y de ID (`#id`).
  - Paleta de colores consistente en todo el sitio.

## Flujo de trabajo con Git

- Rama principal: `main`
- Rama de desarrollo (Fase 1): `fase-1-maquetacion`

```bash
# Trabajar en la rama de la fase
git checkout fase-1-maquetacion

# Guardar y subir cambios
git add .
git commit -m "Descripción de los cambios"
git push -u origin fase-1-maquetacion
```

Al finalizar la fase, unir `fase-1-maquetacion` a `main` mediante **Merge** o **Pull Request**.
