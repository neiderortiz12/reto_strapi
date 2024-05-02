# 🚀 Getting started with Strapi

Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/dev-docs/cli) (CLI) which lets you scaffold and manage your project in seconds.

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/dev-docs/cli#strapi-build)

```
npm run build
# or
yarn build
```

# Reto Strapi - FrontDojo

## Objetivo
Desarrollar una API de un blog utilizando Strapi, que incluya gestión de artículos y categorías, con funcionalidades extendidas para manejar imágenes de cabecera.
Opcional: Enviar pantallazos del postman con el consumo.

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

