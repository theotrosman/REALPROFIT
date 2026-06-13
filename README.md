# Real Trends · Profit

Módulo de **rentabilidad y repricing** para vendedores de Mercado Libre Argentina, pensado como una funcionalidad embebida dentro de la app de Real Trends.

## Qué resuelve

En Argentina la inflación licúa el margen nominal y Mercado Libre actualiza sus comisiones varias veces al año (además de diferenciar cargos por provincia). Vender al mismo precio mes a mes termina en pérdida sin que el vendedor lo note.

Este módulo:

- Calcula **lo que de verdad queda** en cada venta, descontando comisión de ML, envío, costo financiero de las cuotas, fee de Mercado Pago e impuestos.
- **Ajusta los precios automáticamente** cuando suben los costos, para defender el margen real (no el nominal).
- Incluye un **simulador** que muestra el equilibrio entre precio, ganancia y competitividad, con un precio recomendado.

## Demo

Prototipo de una sola página en `index.html` (HTML + CSS + JS vanilla, sin dependencias). Datos de ejemplo precargados.

```bash
python -m http.server 4500
# abrir http://localhost:4500
```

## Estado

Prototipo visual para demo. Los datos son de ejemplo y los cálculos son orientativos.
