# ANWAY — landing page

Landing page responsive hecha con HTML semántico y CSS puro. No requiere JavaScript ni frameworks.

## Archivos
- `index.html`: estructura y contenido.
- `styles.css`: estilos, paleta y responsive.

## Cómo verla
Abrí `index.html` en tu navegador. Para desarrollo local también podés usar la extensión Live Server de VS Code.

## Antes de publicar
1. En `index.html`, reemplazá `549XXXXXXXXXX` del enlace de WhatsApp por tu número real con código de país, sin `+`, espacios ni guiones. También reemplazá `contacto@tudominio.com` en el atributo `action` del formulario por tu dirección real. El formulario usa `mailto:`: abre el cliente de correo del visitante y no envía datos a un servidor.
2. Reemplazá la vista conceptual de la notebook del hero y los proyectos conceptuales por capturas, descripciones y enlaces de proyectos reales cuando estén disponibles. La notebook actual es una maqueta CSS, no una captura de producción.
3. Actualizá el texto, el año del footer y los datos de contacto según tu marca.
4. La tipografía se carga desde Google Fonts; si querés evitar peticiones externas, quitá los enlaces a Google Fonts del `<head>` y se usarán las fuentes de respaldo del sistema.

## Personalización rápida
Los colores principales están declarados como variables CSS al comienzo de `styles.css`:
- `--green: #252D2B`
- `--champagne: #DCC8A6`
- `--ivory: #F0E7DB`
