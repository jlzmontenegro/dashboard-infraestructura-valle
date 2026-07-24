# Dashboard de Contratación — Secretaría de Infraestructura (Gobernación del Valle del Cauca)

Dashboard interactivo y **autónomo** (un solo archivo `index.html`) de la contratación pública de la
Secretaría de Infraestructura de la Gobernación del Valle del Cauca, a partir de **SECOP II** (datos.gov.co).

## Características

- **Datos en vivo**: consulta la API de datos.gov.co (dataset `jbjy-vk9h`) al abrirlo, con un
  *snapshot* incorporado como respaldo si no hay conexión.
- **Sin dependencias externas**: Chart.js va incrustado; funciona incluso sin internet (con los datos de respaldo).
- **Filtros dinámicos**: rango de años (deslizador), categoría, tipo de contrato, estado y búsqueda —
  recalculan KPIs, gráficas y tablas.
- **Exportación**: botones para exportar a **CSV** y **PDF** según los filtros aplicados.
- **Clasificación por categoría** del objeto contractual y alertas (adiciones de tiempo, valor $0).
- Excluye del análisis los contratos en estado *Cancelado* / *Borrador*.

## Uso

Abre `index.html` en cualquier navegador, o visita el sitio publicado con GitHub Pages.

## Fuente

SECOP II — [datos.gov.co](https://www.datos.gov.co/) · Entidad: `SECRETARIA DE INFRAESTRUCTURA - GOBERNACION DEL VALLE`.
