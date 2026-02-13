# Instrucciones para Imágenes

Coloca aquí tus 10 fotos en formato polaroid o normal.
Nombres requeridos: `foto1.jpg`, `foto2.jpg` ... hasta `foto10.jpg`.

El código actual usa marcadores de posición (placeholders) de internet.
Para usar tus fotos locales, edita `src/components/Gallery.astro` y cambia:
`src="https://placehold.co/..."`
por
`src={'/images/foto' + (i + 1) + '.jpg'}`
