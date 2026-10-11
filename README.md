# EZLINK — sitio web corporativo

Landing page responsive para EZLINK, empresa de gestión de cobranzas por call center. Incluye secciones comerciales y de oportunidades laborales.

## Archivos
- `index.html`: contenido y estructura.
- `style.css`: estilos responsive.
- `script.js`: menú móvil, animaciones y enlaces configurables de WhatsApp.
- `assets/`: carpeta preparada para el logotipo oficial y otros recursos.

## Probar en tu computadora
1. Descomprime la carpeta.
2. Abre `index.html` en Chrome, Edge o Firefox.
3. Necesitas conexión a internet para cargar las fotografías de Unsplash y las fuentes de Google Fonts.

## Configurar WhatsApp
Abre `script.js` y busca al inicio:

```js
const EZLINK_CONFIG = {
  whatsappNumber: "",
};
```

Cuando RR. HH. confirme el número comercial, escríbelo entre comillas con código de país, solo dígitos. Para Bolivia, el formato empieza con `591`. No incluyas `+`, espacios ni guiones. Ejemplo ficticio de formato: `"59170000000"`.

Hasta configurar el número, los botones muestran un aviso y no intentan abrir un chat.

## Colocar el logotipo oficial
Cuando tengas el archivo del logo:
1. Guárdalo en `assets/`, por ejemplo como `logo-ezlink.svg` o `logo-ezlink.png`.
2. En `index.html`, reemplaza los dos bloques `.brand` por una imagen, por ejemplo:

```html
<a class="brand" href="#inicio" aria-label="EZLINK, ir al inicio">
  <img class="official-logo" src="assets/logo-ezlink.svg" alt="EZLINK — Gestión de Cobranzas">
</a>
```

3. Añade a `style.css`:

```css
.official-logo {
  width: 190px;
  max-height: 54px;
  object-fit: contain;
}
```

Adapta el ancho a las proporciones del logo real.

## Publicar en Hostinger
1. Entra a hPanel y abre el administrador de archivos del dominio.
2. Abre `public_html`.
3. Sube `index.html`, `style.css`, `script.js` y la carpeta `assets`.
4. Comprueba que `index.html` esté directamente dentro de `public_html`.
5. Abre tu dominio y revisa la versión móvil.

## Antes de publicar
- Confirmar el número de WhatsApp comercial.
- Reemplazar el logotipo temporal por el oficial.
- Validar con EZLINK los textos, servicios y requisitos laborales.
- Sustituir las fotos de stock por imágenes autorizadas de la empresa, si están disponibles.
- Agregar datos reales de contacto, dirección y redes oficiales si corresponde.

## Nota sobre contenido
No se han añadido métricas, años de experiencia, clientes ni garantías de recuperación no confirmadas. Los textos sobre servicios y reclutamiento deben ser aprobados por la empresa antes de publicar.
