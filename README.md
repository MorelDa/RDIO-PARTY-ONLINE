# Radio Party Online — PWA

PWA web lista para publicar en GitHub Pages o Vercel.

## Incluye
- Intro vertical `assets/intro.mp4`.
- En navegador: botón **TOCAR PARA ENTRAR** para iniciar la intro respetando las restricciones de autoplay.
- En PWA instalada: la intro intenta reproducirse automáticamente en silencio y entra sola al finalizar.
- Reproductor de Radio Party con el stream de Zeno.
- Botón grande central **PEDIDOS** que abre WhatsApp con un mensaje preparado.
- Botón **ESCRIBÍ AL WHATSAPP**.
- Instagram y Facebook.
- Manifest + Service Worker + iconos para instalación PWA.
- Diseño de una sola pantalla, sin scroll, responsive para móvil y escritorio.

## Publicación
### GitHub Pages
Sube todo el contenido del ZIP al repositorio y activa Pages desde la rama principal, carpeta `/root`.

### Vercel
Importa el repositorio o arrastra la carpeta del proyecto. No necesita build command.

## Importante sobre audio/autoplay
Los navegadores no permiten iniciar automáticamente un stream de radio con sonido de forma fiable. Por eso el botón de reproducción de la radio permanece disponible. El autoplay del vídeo de introducción en una PWA instalada se hace en silencio para cumplir las políticas del navegador.

## Archivos principales
- `index.html`
- `manifest.webmanifest`
- `sw.js`
- `assets/intro.mp4`
- `assets/radio-party-logo.png`
- `assets/favicon-source.png`
