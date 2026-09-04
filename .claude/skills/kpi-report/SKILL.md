---
name: kpi-report
description: Convierte datos de rendimiento de marketing (redes, email, promociones, reseñas) en un informe claro con conclusiones accionables. Usar cuando haya datos concretos que resumir o una campaña que cerrar con resultados.
---

# KPI report

Proceso para pasar de datos crudos a un informe que alguien pueda usar para
decidir el siguiente paso, sin inventar ni sobreinterpretar cifras.

## Pasos

1. **Exige datos reales.** Si no te han dado cifras, exportaciones o
   capturas concretas, pídelas explícitamente. No generes un informe con
   números de ejemplo presentados como si fueran reales.
2. **Da contexto a cada métrica**: compárala con un periodo anterior o un
   objetivo, no la presentes aislada. "1.200 alcances" no dice nada sin
   saber si es más o menos que antes.
3. **Separa métricas de vanidad de métricas de negocio**: alcance y "me
   gusta" importan menos que reservas, ventas de un producto concreto o
   reseñas nuevas — prioriza estas últimas en las conclusiones si están
   disponibles.
4. **Distingue correlación de causalidad**: si una campaña coincidió con una
   subida, formúlalo como hipótesis razonable, no como causa probada, salvo
   que los datos la sostengan con claridad.
5. **Si un dato falta o es insuficiente** para concluir algo con confianza,
   dilo explícitamente en el informe en vez de rellenar el hueco con una
   suposición.
6. **Prioriza 2-3 conclusiones accionables** sobre listar todas las métricas
   disponibles. Si una conclusión apunta a un problema de otro área
   (reputación, contenido, promoción), indica a qué agente pasarlo.
7. Si conviene visualizar los datos (por ejemplo, evolución en el tiempo),
   carga la skill `dataviz` antes de construir cualquier gráfico.

## Salida

```
Resumen ejecutivo: [3-4 líneas]
Métricas clave: [métrica — valor — comparación/contexto]
Conclusiones accionables: [2-3, priorizadas]
Datos insuficientes para concluir sobre: [si aplica]
```
