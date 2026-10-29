# Astra · Estudios interactivos

Dos escenas 3D originales inspiradas en las referencias visuales: **Harbor Jelly**, un puerto en miniatura, y **Hammerhead**, un tiburón martillo de peluche. Implementadas con Three.js y Vite, sin servicios de backend ni claves privadas.

## Desarrollo

Requiere Node.js 22.12 o posterior.

```sh
npm ci
npm run dev
```

## Producción

```sh
npm run build
npm run preview
```

La carpeta `dist` contiene el sitio estático para desplegar. Subir el código a GitHub no publica automáticamente una web.

## Interacción

- Alternar entre puerto y tiburón con el botón superior.
- Arrastrar para orbitar; rueda o gesto de pellizco para acercarse.
- Ajustar color, iluminación y velocidad de las animaciones.
- Activar giro automático, restablecer cámara y exportar una imagen PNG.

El puerto incluye grúas, contenedores, edificios, barcos, agua animada y un faro. El tiburón tiene ojos, dientes, aletas, relieve procedural y movimiento flotante. Las escenas son recreaciones estilizadas; no son reproducciones exactas de las imágenes de referencia.

## Validación

La compilación se verifica con `npm run build`. Se necesita un navegador con WebGL para revisar el renderizado y los controles. Las fuentes de Google son opcionales: hay fuentes de sistema de respaldo.
