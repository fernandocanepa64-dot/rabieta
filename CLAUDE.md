# CLAUDE.md

Contexto para Claude cuando trabaja en este repositorio. Responder siempre en **español (Argentina)**.

## Quién soy

Fernando Cánepa (fcanepa@rabieta.com.ar). Tengo dos roles:

1. **Gerente Regional de Cervecería Rabieta, región Reginald Lee.** Respondo por el **volumen** y el **market share** de la región.
2. **Gerente de Ventas de Facón.**

Cuando un pedido sea ambiguo, preguntá a cuál de los dos negocios se refiere (Rabieta o Facón) antes de mezclar datos.

## Para qué uso este repo

- Forecast de volumen de ventas (por ejemplo, el de **latas**. Para actualizarlo está el skill `rabieta-forecast-latas`).
- Análisis de volumen y market share por región, canal, cliente y SKU.
- Reportes y presentaciones para la dirección y para el equipo comercial.

## Glosario del negocio

- **Volumen**: se mide en **hectolitros (HL)**.
- **Market share**: fuente **Scentia**. Se mide **en volumen y en valor**; aclarar siempre cuál se está mostrando.
- **Reginald Lee**: región a mi cargo. Abarca la **Provincia de Buenos Aires desde Quilmes hasta Necochea**, con límite en **Tandil**.
- **Latas**: formato de envase con forecast propio.
- **Facón**: cerveza de **República Artesanal**.

## Cómo quiero que trabajes

- **Números primero.** Empezá con la conclusión y el dato clave (variación vs. año anterior, vs. presupuesto, vs. mes anterior), después el detalle.
- **Siempre comparar**: real vs. presupuesto, vs. año anterior (YoY) y vs. forecast.
- **No inventes datos.** Si falta información, decilo y preguntá. Marcá claramente qué es real y qué es estimado.
- **Formatos de entrega**: Excel para datos y forecast, PowerPoint para presentaciones, texto breve para resúmenes.
- **Formato numérico argentino**: punto para miles y coma para decimales (1.234,5). Fechas en DD/MM/AAAA.
- Mantené separados los datos de **Rabieta** y los de **Facón**.

## Estructura del repo

<!-- TODO: completar a medida que se agreguen carpetas -->
- `data/`: datos de ventas crudos (sin editar a mano)
- `forecast/`: archivos de forecast
- `reportes/`: salidas (Excel, PPT, PDF)

## Calendario y cierres

- El mes cierra a **fin de mes**. Con el cierre se cargan los datos reales y se actualiza el forecast.
