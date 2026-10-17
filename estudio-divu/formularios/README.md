# Formularios de Divú

Los formularios viven en el WordPress de Divú. Esta carpeta solo documenta cómo los lee el agente.
**No hay copias aquí** para no tener versiones paralelas: la versión buena es la que tiene Cynthia.

| Formulario | Archivo | Estado |
|---|---|---|
| Brief exprés de diseño | `brief-diseno-divu.html` | Vigente. Incluye "¿Cómo nos conociste?", "¿Quién aprueba?", presupuesto hasta $1,500+ e insumos obligatorios. |
| Formato de Briefing Divú (brief completo) | `briefing-divu.html` | Vigente. **Pendiente de revisar.** |
| Brief de audiovisual (7 oct) | `brief-moodboard-av.html` (Drive) | **Obsoleto. No usar.** No está conectado al receptor. |

## Receptor (Apps Script)

- Proyecto: "Proyecto sin título" (ID `1bPslCxJQ2DOsiDp-nkoJ_m-7413RXobKP9oWOKksO2LpUxCSYWlxw1yl`),
  cuenta estudiodivu@gmail.com. Independiente (no vinculado a la hoja). **No se toca.**
- URL /exec: `https://script.google.com/macros/s/AKfycbwyUb1HamFcSDdQ5wq9yUOkP-FznDAJaUyOpcaY53Hm7OCDtH78PevoSqiQQkDgwrqGaQ/exec`
- Por cada brief:
  1. Agrega una fila en la hoja "Solicitudes Divú", pestaña **Solicitudes**, con Estado = "Nueva".
  2. Crea una carpeta en "Briefs Divú" (Drive, ID `1szK2e9_xyXQmCGL4A7t--P8ds6P1NzFJ`) con las
     imágenes y `brief.json`.
  3. Manda a estudiodivu@gmail.com: "Nueva Solicitud · {folio} · {marca} · {servicio}".
  4. Manda al cliente la confirmación automática (opción A): "Recibimos tu solicitud · Estudio Divú · {folio}",
     sin precio ni fecha.
- Probado el 17/10/2026 con el folio BRF-261017-8R2E.

## Piezas del brief exprés → código DIV y Kraljic

El formulario ya calcula código y Kraljic. "Otra cosa" llega como DIV-DIS-002 Rutinario:
el agente lo revisa con las notas del cliente.

| Pieza | Código | Kraljic |
|---|---|---|
| Post o carrusel para redes | DIV-DIS-002 | Rutinario |
| Flyer, afiche o banner | DIV-DIS-002 | Rutinario |
| Logo o identidad nueva | DIV-DIS-001 | Estratégico |
| Refrescar mi marca | DIV-DIS-005 | Apalancado |
| Empaque o etiqueta | DIV-DIS-004 | Estratégico |
| Ilustración o personaje | DIV-DIS-003 | Cuello de Botella |
| Presentación o brochure | DIV-EDI-003 | Rutinario |
| Otra cosa | DIV-DIS-002 | Rutinario (revisar) |

## Ocasión del formulario → hito de negocio

| Respuesta | Hito |
|---|---|
| un lanzamiento | Lanzamiento |
| renovar mi imagen | Rebranding |
| una promoción o temporada | Campaña de temporada (Black Friday, Q4…) |
| un evento | Evento |
| mis redes de todos los días | Contenido (posible retainer) |
| abrir mi negocio | Apertura |
| otra cosa | Otra (revisar notas) |
