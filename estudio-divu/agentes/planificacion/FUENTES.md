# Fuentes del agente de Planificación

Todas en la cuenta **estudiodivu@gmail.com** (Trello: cuenta `estudiodivu`). Solo lectura.

| Fuente | Dónde | ID / enlace |
| --- | --- | --- |
| Divú · Backoffice | Google Sheets, pestañas Pedidos, Pagos y Horas | `1xCJgGtklUFC5fsIUF4QASGvS_KjGUk70hruJXqCFObk` |
| Proyectos | Trello, tablero de pedidos en curso (una tarjeta por pedido; ignora la tarjeta "PLANTILLA") | https://trello.com/b/3Qqh0VgV/proyectos |
| Solicitudes | Trello, tablero del agente de Ventas (solo para contar solicitudes nuevas de la semana) | https://trello.com/b/fmQkk065/solicitudes |
| Calendario | Google Calendar `estudiodivu@gmail.com` | — |
| Plan de Ejecución | Claude Doc (opcional) | https://claude.ai/artifact/TTqEqTy57QdyTgRATujB4T |

## Columnas que usas en Pedidos

ID · Fecha · Estado · Deadline · Categoría Kraljic · Estado en la app · Fecha último estado ·
Última acción del cliente. Busca las columnas **por nombre de encabezado**, nunca por posición.

## Columnas que usas en Pagos

Fecha · ID pedido · Concepto · Monto (USD) · Método · Estado ("Pendiente" o "Recibido").

## Columnas que usas en Horas

Fecha · ID pedido · Cliente · Categoría Kraljic · Tarea · Horas · Con IA.

## Estados del Backoffice

Nueva · Brief enviado · En producción · En revisión · En riesgo · Entregado · Pausado · Cancelado.
"Estado en la app" trae el estado detallado del portal (por ejemplo "Esperando anticipo").

## Notas

- TSLA está en pausa desde el 26 oct 2026: si aparecen horas o pedidos de TSLA, sepáralos y no los cuentes en las ~17 h.
- Las filas de prueba (cliente con "prueba" o "test" en el nombre o el correo) no cuentan.
