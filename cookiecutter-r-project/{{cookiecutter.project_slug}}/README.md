# {{ cookiecutter.project_name }}

Este proyecto ha sido generado con [Cookiecutter](https://github.com/cookiecutter/cookiecutter).

## Estructura

.
├── R/
│ ├── global.R
│ ├── src/
│ └── scripts/
├── docs/
├── data/
│ ├── raw/
│ └── clean/
├── outputs/
│ ├── reports/
│ └── files/


## Descripción

- `R/global.R`: Definición de rutas con `here::here()`.
- `R/src/`: Código fuente reutilizable.
- `R/scripts/`: Scripts ejecutables de análisis o procesamiento.
- `data/`: Datos crudos y limpios.
- `outputs/`: Reportes y archivos generados.
- `docs/`: Documentación del proyecto.

## Cómo empezar

Abre el proyecto en RStudio y asegúrate de tener el paquete `here` instalado.

```r
install.packages("here")
```
