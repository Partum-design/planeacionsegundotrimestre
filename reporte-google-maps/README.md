# Reporte de reseñas de Google Maps · Laboratorios BIOS

Sitio estático de una sola página con el **reporte de métricas de reseñas de Google Maps** de Laboratorios BIOS. Corte de datos: **6 de agosto de 2026**.

Es un proyecto autocontenido: solo HTML, CSS y JS en línea, sin dependencias ni build.

## Contenido

| Sección | Qué muestra |
|---|---|
| Portada | Alcance del reporte y fecha de corte |
| 01 · Calificaciones | Calificación y número de reseñas de cada ficha de Google, más el promedio general (2.9★ · 288 reseñas · 5 sucursales) |
| 02 · Temas | Desglose aproximado de los temas mencionados en las reseñas de cada sucursal, con prioridad de intervención y lectura general |
| Cierre | Nota de fuente de los datos |

## Fichas incluidas

- Laboratorio Bios — Sucursal Cantú (Plaza Cantú, Cuautitlán Izcalli) — 2.8★ · 146 reseñas
- Laboratorio Médico Diagnóstico BIOS (Soriana Paseo la Joya, Cuautitlán) — 3.0★ · 62 reseñas
- Laboratorio BIOS (Súper Plaza Las Haciendas, Cuautitlán Izcalli) — 2.8★ · 47 reseñas
- BIOS laboratorios (Soriana Mercado Tepalcapa, Cuautitlán Izcalli) — 2.5★ · 19 reseñas
- Laboratorio Médico Diagnóstico BIOS (Ejido San Francisco Tepojaco) — 3.5★ · 14 reseñas
- Plaza Tauro (San Martín, Tultepec) — 5.0★ · 1 reseña · ficha de la plaza, no de una sucursal BIOS

## Notas metodológicas

- Los porcentajes por tema son **aproximados**: una misma reseña puede tocar varios temas, así que no suman 100%.
- Plaza Tauro se excluye del desglose por tema (solo tiene 1 reseña) y del promedio general.
- Los datos provienen de las fichas públicas de Google Maps de cada sucursal.

## Uso local

No requiere instalación. Abre `index.html` en el navegador, o sirve la carpeta:

```bash
python3 -m http.server 8000
```

## Estructura

```
.
├── index.html   # reporte completo (markup + estilos + scripts)
└── assets/      # logos BIOS / Partum y favicon
```

---

Partum Design × Laboratorios BIOS
