# MesaClick — Informe breve de Fase 1

## Alcance del aporte

Revisión del código de la rama `fase-1-maquetacion` para documentar el alcance de la maqueta y dejar un recorrido de comprobación para el informe del equipo. Aporte documental de `noelfrias`.

## Estructura y evidencia

| Archivo | Qué aporta a la maqueta |
| --- | --- |
| [index.html](../index.html) | Entrada al sitio. El formulario enlaza a esta página para volver al inicio. |
| [formulario.html](../formulario.html) | Pantalla «Hacer pedido». Incluye un selector de plato obligatorio, una cantidad obligatoria con mínimo y valor inicial de 1 y un área de observaciones opcional. |
| [css/estilos.css](../css/estilos.css) | Hoja de estilos externa compartida, según la estructura del proyecto. El HTML del formulario la enlaza mediante una ruta relativa. |

El botón «Hacer pedido» está declarado como `type="button"`. Los atributos `required` y `min` describen restricciones de los campos, pero pulsar ese botón por sí solo no realiza el envío ni dispara la validación de un envío. La Fase 1 documentada en el [README](../README.md) cubre la estructura HTML y la presentación CSS.

## Recorrido de comprobación manual

1. Abre `index.html` y `formulario.html` desde una copia local de la rama. En la pantalla de pedido, pulsa el enlace de inicio y comprueba que lleva a `index.html`.
2. Vuelve al formulario. Comprueba que el selector ofrece «Pollo a la plancha», «Pasta con salsa de tomate» y «Ensalada de la casa», que la cantidad inicia en 1 y que las observaciones se identifican como opcionales.
3. Revisa el HTML del formulario para confirmar `required` en el selector, `min="1"` en la cantidad y `type="button"` en «Hacer pedido». Usa esta revisión al describir el alcance del prototipo en el informe.

El recorrido queda propuesto para reproducir la comprobación en el navegador. Las observaciones de este documento provienen de la revisión del código y del README.
