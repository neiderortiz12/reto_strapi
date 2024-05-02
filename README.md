# 🚀  Reto Strapi - FrontDojo

## Objetivo

### Levantar el proyecto de strapi.
En este paso levantar el proyecto de strapi. recuerda instalas la dependencias (Nodejs 20 o superior) el npm i y luego:

### `develop`

```
npm run develop
# or
yarn develop
```

Desarrollar una API de un blog utilizando Strapi, que incluya gestión de artículos y categorías, con funcionalidades extendidas para manejar imágenes de cabecera.
### Opcional: Enviar pantallazos del postman con el consumo.

## Plazo máximo
Lunes 6 de Mayo 11:59 p.m

## Modelo de Datos

### Artículo
- `titulo`: String (requerido)
- `contenido`: Text (requerido)
- `fecha_publicacion`: Date (requerido)
- `autor`: String
- `categorias`: Relación muchos a muchos con Categoría
- `imagen_cabecera`: Media (permite cargar una imagen que será la cabecera del artículo)

### Categoría
- `nombre`: String (requerido)
- `descripcion`: Text
- `imagen_cabecera`: Media (permite cargar una imagen que será la cabecera de la categoría)

