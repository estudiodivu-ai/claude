# Hoja "Solicitudes Divú" (Google Sheets)

https://docs.google.com/spreadsheets/d/1KvQmkSVQL-F-FHHizq_a96M2js0OZjYOMR7xZ_0eCmI/edit
Pestaña: **Solicitudes** (rango `Solicitudes!A:AG`). Fila 1 = encabezados (congelada).

El **receptor de Apps Script** crea la fila. El agente **solo completa** sus columnas y nunca
borra ni reescribe lo que llenó el cliente.

| Col. | Columna | La llena |
|---|---|---|
| A | Fecha de entrada | Receptor |
| B | Empresa | Receptor |
| C | SPOC | Receptor |
| D | Correo | Receptor |
| E | WhatsApp | Receptor |
| F | Servicio | Receptor |
| G | Código DIV | Receptor |
| H | Kraljic | Receptor |
| I | Ocasión | Receptor |
| J | Rango de presupuesto | Receptor (`0-300`, `300-800`, `800-1150`, `1150-1500`, `1500+`, `Por definir`) |
| K | Tier sugerido | **Agente** |
| L | Fecha pedida | Receptor (AAAA-MM-DD) |
| M | ¿Cabe en capacidad? | **Agente** (Sí / Justo / No / Sin estimar) |
| N | Cómo nos conoció | Receptor |
| O | Origen (asistida/no asistida) | Receptor (el agente lo verifica con la tabla de reglas) |
| P | Alertas | **Agente** |
| Q | Decisión | **Agente**, solo cuando Cynthia mueve la tarjeta (Aceptada / Reserva / Rechazada) |
| R | Estado | Receptor ("Nueva"); luego **agente** = columna de Trello |
| S | Link a la tarjeta | **Agente**. Si está vacío, la solicitud está sin procesar. |
| T | Folio | Receptor (BRF-AAMMDD-XXXX) |
| U | Formato | Receptor (p. ej. "Brief exprés de diseño") |
| V | Aprobación | Receptor ("Solo yo" / "Somos varios") |
| W | Sesión sugerida | Receptor |
| X | Insumos | Receptor |
| Y | Carpeta del brief | Receptor (link a Drive) |
| Z | Mensaje único | Receptor |
| AA | Entregables | Receptor |
| AB | Canales | Receptor |
| AC | Tono | Receptor |
| AD | Nº imágenes | Receptor |
| AE | Links de referencia | Receptor |
| AF | Carpeta del cliente | Receptor |
| AG | Específicas del servicio | Receptor |
