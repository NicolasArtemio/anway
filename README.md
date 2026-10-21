# ANWAY — landing page

Landing page responsive hecha con HTML semántico y CSS puro. Sin frameworks ni librerías externas: solo ~16 líneas de JavaScript nativo en el pie del documento, únicamente para que el formulario arme el mail y abra el cliente de correo.

## Archivos
- `index.html`: estructura y contenido.
- `styles.css`: estilos base, paleta, tipografía, contraste, menú móvil, botón de WhatsApp y responsive. Todo en un solo archivo.
- `og.png`: imagen de preview 1200×630 para compartir en redes.

## Cómo verla
Abrí `index.html` en tu navegador. Para desarrollo local también podés usar la extensión Live Server de VS Code.

## Antes de publicar
Estos tres datos son **placeholders**: el sitio no funciona bien hasta que los reemplaces.

1. **Número de WhatsApp** — en `index.html`, el `href` del botón `.button-wa`:
   `https://wa.me/54XXXXXXXXXX?...` → tu número con código de país, **sin `+` ni espacios**.
2. **Email** — dos lugares en `index.html` (el `href` del `mailto:` y el texto visible en `.contact-alt`).
3. **Dominio** — `<link rel="canonical">` y `<meta property="og:image">` en el `<head>`: `https://TUDOMINIO.com/`.
   El `og.png` ya está generado; solo subilo a la raíz del dominio.

Después: reemplazá los proyectos conceptuales por capturas reales, y actualizá el año del footer y los datos de contacto.

## Personalización rápida
Los colores principales están declarados como variables CSS al comienzo de `styles.css`:
- `--green: #252D2B`
- `--champagne: #DCC8A6`
- `--ivory: #F0E7DB`
- `--muted: #5A5F57` (gris con contraste AA)
- `--green-wa: #1FA855` (verde de WhatsApp)
