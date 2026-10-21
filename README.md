# ANWAY — landing con transición de notebook al hacer scroll

Versión experimental de la landing de ANWAY basada en HTML, CSS y JavaScript nativo.

## Qué cambia
- En escritorio, la escena del hero permanece fija durante un tramo del scroll.
- La tapa de la notebook se abre progresivamente, el contenido de la pantalla revela una miniatura de la propia landing de ANWAY y la escena se acerca.
- Al terminar el tramo, la página continúa con sus secciones originales.
- En móvil se desactiva la apertura 3D para priorizar legibilidad y rendimiento.
- Se respeta `prefers-reduced-motion`.

## Cómo probar
Abrí `index.html` con Live Server en VS Code y desplazate lentamente por el hero.

## Importante sobre el efecto 3D
Esta es una primera implementación visual usando transformaciones 3D de CSS; **no utiliza todavía un modelo 3D real `.glb`**. Es útil para validar el ritmo y la experiencia. Para un resultado cinematográfico más realista, el siguiente paso sería sustituir la tapa CSS por un modelo articulado con Three.js y sincronizar la bisagra y cámara con el scroll.

## Antes de publicar
- Sustituí el número de WhatsApp de ejemplo y el email.
- Probá la experiencia en distintos navegadores y dispositivos.
- Verificá que la transición no afecte la accesibilidad ni el rendimiento.
