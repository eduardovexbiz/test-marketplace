# Flujo de devoluciones — Vexbiz

Este repositorio tiene todo lo necesario para implementar el flujo de devoluciones del marketplace de Vexbiz.

| Archivo | Qué es |
| --- | --- |
| [`ESPECIFICACION.md`](ESPECIFICACION.md) | **Especificación técnica**: flujo, preguntas del formulario, reglas de negocio, estados, modelo de datos, endpoints, criterios de aceptación y casos de prueba. Es la fuente de verdad. |
| [`prototipo/index.html`](prototipo/index.html) | Prototipo navegable del formulario del cliente. Ábrelo en el navegador para ver los textos y la lógica de validación. |

## Importante sobre el prototipo

El prototipo es **solo una referencia** de textos y lógica, no el diseño final:

- El paso 1 del prototipo (datos del pedido y del cliente) **no se implementa**. En producción esos datos salen de la sesión iniciada y del pedido seleccionado. Ver la sección "Punto de entrada y datos precargados" de la especificación.
- Los productos y la tienda del prototipo son datos de muestra.
- El diseño final sigue los estilos del marketplace.

Si el prototipo y la especificación no coinciden, manda la especificación.

## Pendientes antes de producción

- [ ] Dirección decide qué pasa con la comisión del 5% cuando hay reembolso.
- [ ] Legal revisa los plazos de 7 y 30 días.
- [ ] Decidir si "saldo a favor" sale en el MVP.
- [ ] Definir el calendario de días hábiles para el plazo de 48 h.

Contacto: Eduardo Marcano — Coordinación de Operaciones, Vexbiz Suministros.
