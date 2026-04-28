# LandscapePortraitAndroid

Aplicación Android sencilla para trabajar la adaptación de layouts en modo vertical (portrait) y horizontal (landscape).

## Descripción

La app muestra la ficha de un producto (videojuego) simulando un detalle de ecommerce.

Se han implementado dos layouts distintos:

- **Vertical (portrait)** → contenido en columna con scroll:
  - Imagen del producto
  - Título
  - Precio
  - Descripción
  - Botón de compra

- **Horizontal (landscape)** → contenido sin scroll:
  - Imagen a la izquierda
  - Información y botón a la derecha

El cambio entre layouts se realiza automáticamente al girar el dispositivo.

## Tecnologías utilizadas

- Android Studio
- Kotlin
- XML (Layouts)

## Estructura

- `res/layout/activity_main.xml` → diseño vertical
- `res/layout-land/activity_main.xml` → diseño horizontal

## Objetivo

Aprender a adaptar interfaces en Android según la orientación del dispositivo utilizando carpetas de recursos específicas.

## Vídeo

[Ver vídeo](./Video/video.mp4)

## Autor

Proyecto individual
