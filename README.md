# Template para charlas de la comunidad de RustLangES
![ezgif com-gif-maker](https://github.com/RustLangES/template_presentations/assets/56278796/0ab6cd23-86fa-4dea-af26-b8d93ef99c23)

## Guia de Inicio
Para ejecutar en desarrollo, solo corre

- `npm install`
- `npm run dev`
- visita http://localhost:3030

Edita el archivo [slides.md](./slides.md) para ver los cambios.

> [!IMPORTANT]
> Lee los comentarios que hay en el archivo para tomar en cuenta al momento de hacer tus cambios

## Despliegue de tu presentacion
- Opcion 1 (desplegar como web):
    - `npm run build` aunque probablemente quieras correrlo como `npm run build -h` para ver las opciones que trae
    - Despliega la carpeta `dist` que se genera
    - Para hacerlo mas facil se incluye un archivo `Docker` lo que te permite desplegarlo con docker en la plataforma que desees
    - Tambien incluye el archivo de configuracion para [fly.io](https://fly.io) y para [netlifly](https://netlifly.com) (Recuerda darles un vistaso para cambiar ciertos parametros necesarios)
- Opcion 2 (como pdf):
    - `npm run export`
    - Probablemente tengas que desactivar ciertos efectos para que el pdf se visualize correctamente

Lee mas acerca de SlidDev en su [documentacion](https://sli.dev/).
