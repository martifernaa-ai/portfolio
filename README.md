# Martí Fernández Garrigós · Portafolio

Perfil híbrido **negocio + tecnología**: herramientas internas que leen **Excel** y **PDF** y los convierten en **dashboards** y controles automáticos. Graduado en Contabilidad y Finanzas y estudiante de Ingeniería Informática, aplicando análisis de datos y automatización a procesos industriales reales.

🔗 **Web en vivo:** https://TU-USUARIO.github.io/portafolio/
💼 **LinkedIn:** https://www.linkedin.com/in/martí-fernandez-garrigos-1b9934265

> *[English version below](#english)*

---

## Español

Cada herramienta funciona en el navegador (sin instalar nada) y **se abre con datos de ejemplo ficticios**, para poder probarla sin subir ningún archivo. También puedes cargar tu propio Excel o PDF.

### Herramientas

| Herramienta | Qué hace | Entrada | Tecnología |
|---|---|---|---|
| **StockFlow** | Análisis de movimientos de inventario: entradas/salidas, top de artículos, tendencias, rotación, balance compras-ventas y mapas de calor. | Excel | JavaScript · SheetJS · ECharts |
| **Análisis de precios** | Evolución y comparativa de precios de compra por material, con variación interanual y trimestral, mapas de calor y alertas de volatilidad. | Excel | JavaScript · SheetJS · Chart.js |
| **BI de proveedores y pedidos** | Panel de gestión de pedidos y proveedores: pendientes, históricos y filtros por proveedor y artículo. | Excel | JavaScript · SheetJS · ECharts |
| **Comparador de precios de facturas** | Lee facturas en PDF, extrae los precios y los compara con una base de datos de referencia, marcando desviaciones y sobrecostes. | PDF | JavaScript · pdf.js · SheetJS |

### Stack

- **Datos:** Excel avanzado, Power Query, Power Pivot, VBA
- **Web:** JavaScript, HTML, SheetJS, pdf.js
- **Visualización:** ECharts, Chart.js
- **Negocio:** ERP, análisis de costes, KPIs
- **IA:** modelos de lenguaje aplicados al negocio

### Datos de ejemplo

Todos los datos incluidos son **ficticios** (Proveedor A/B/C, Artículo 1/2/3) y no corresponden a ninguna empresa. Sirven únicamente para demostrar el funcionamiento de las herramientas.

### Ejecutar en local

Como las demos cargan sus datos mediante `fetch`, deben servirse por HTTP (no abriendo el archivo con doble clic). Desde la carpeta del proyecto:

```bash
python -m http.server 8000
```

Y abre `http://localhost:8000`.

---

## English

**Business + technology hybrid profile:** internal tools that read **Excel** and **PDF** and turn them into **dashboards** and automatic controls. Accounting & Finance graduate and Computer Engineering student, applying data analysis and automation to real industrial processes.

Each tool runs in the browser (nothing to install) and **opens with fictional sample data**, so it can be tried without uploading anything. You can also load your own Excel or PDF.

### Tools

| Tool | What it does | Input | Tech |
|---|---|---|---|
| **StockFlow** | Inventory-movements analysis: inflows/outflows, top items, trends, turnover, purchase-sales balance and heatmaps. | Excel | JavaScript · SheetJS · ECharts |
| **Price analysis** | Evolution and comparison of purchase prices by material, with year-on-year and quarterly variation, heatmaps and volatility alerts. | Excel | JavaScript · SheetJS · Chart.js |
| **Suppliers & orders BI** | Orders and suppliers management panel: pending, history and filters by supplier and item. | Excel | JavaScript · SheetJS · ECharts |
| **Invoice price comparator** | Reads PDF invoices, extracts prices and compares them against a reference database, flagging deviations and overcharges. | PDF | JavaScript · pdf.js · SheetJS |

### Sample data

All included data is **fictional** (Supplier A/B/C, Item 1/2/3) and does not belong to any company. It exists only to demonstrate how the tools work.

### Run locally

The demos load their data via `fetch`, so they must be served over HTTP (not opened by double-clicking the file):

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

---

<sub>© 2026 Martí Fernández Garrigós</sub>
