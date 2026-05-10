# recipes-oni 🍵

Propuesta de producto para un sistema de gestión de recetas, desarrollada para una chef gastronómica con su propia casa de té.

## Contexto

El proyecto nace de la necesidad de organizar recetas de forma profesional — desde la elaboración de ingredientes base hasta el ensamble de productos finales — con control de costos integrado.

**Casos de uso:**
- Estudio y documentación de recetas durante la formación como chef
- Gestión de producción de la casa de té: tortas, sándwiches, tablas, scones, brunch

## Propuesta

El archivo [`propuesta-recetas.html`](./propuesta-recetas.html) compara dos soluciones posibles:

| | Excel / Google Sheets | App |
|---|---|---|
| Costo | Gratis | Desarrollo propio |
| Curva de aprendizaje | Ninguna | Baja |
| Escalabilidad | Limitada | Alta |
| Uso desde celular | Incómodo | Nativo |

### Funcionalidades requeridas

- Recetas base e ingredientes con cantidades
- Recetas compuestas (sub-recetas dentro de recetas)
- Múltiples unidades de medida: kg, g, litros
- Precios de insumos y cálculo automático de costo
- Plantilla replicable para nuevas recetas
- Escalado automático de porciones

### Funcionalidades diferenciales de la App

- Carga de receta por audio (dictado + pre-completado automático)
- Subida de fotos por plato
- Exportar ficha en PDF
- Búsqueda por nombre o ingrediente

## Roadmap (App)

```
Fase 1 — App de escritorio Windows
  └── Todo lo requerido + audio + fotos + PDF
  └── Funciona sin internet

Fase 2 — Web App
  └── Acceso desde cualquier dispositivo
  └── Backup en la nube
  └── Lista de compras inteligente
  └── Historial de precios de insumos
  └── Control de alérgenos
  └── Planificación de menú semanal
```

## Ver la propuesta

👉 [Ver propuesta online](https://pfernandezos.github.io/recipes-oni/propuesta-recetas.html)
