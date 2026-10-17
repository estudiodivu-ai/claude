# Formularios de Divú

Los formularios viven en el WordPress de Divú. Esta carpeta solo documenta cómo los lee el agente.
**No hay copias aquí** para no tener versiones paralelas: la versión buena es la que tiene Cynthia.

| Formulario | Archivo | Estado |
|---|---|---|
| Brief exprés de diseño | `brief-diseno-divu.html` | Vigente. Incluye "¿Cómo nos conociste?", "¿Quién aprueba?", presupuesto hasta $1,500+ e insumos obligatorios. |
| Formato de Briefing Divú (brief completo) | `briefing-divu.html` | Vigente. 9 escenas, catálogo completo por línea y preguntas específicas por línea. |
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

## Lo que calculan los formularios antes de llegar a la hoja

- **Origen** según "¿Cómo nos conociste?" (tabla en `REGLAS-DE-NEGOCIO.md`).
- **Sesión sugerida:** Estratégico, High-Ticket (800+), más de un aprobador; el brief completo
  suma "Multicanal / evento" y "Lo pide el cliente".
- **Alertas:** Más de un aprobador · Cuello de Botella · Insumos faltantes ("Nada aún").
  El agente suma las suyas (presupuesto, fecha) sin borrar estas.

## Catálogo (del brief completo, `CAT`)

| Código | Servicio | Kraljic |
|---|---|---|
| DIV-ASE-001 | Consultoría estratégica en comunicaciones multimedia | Estratégico |
| DIV-ASE-002 | Estrategia de comunicación corporativa y transmedia | Estratégico |
| DIV-ASE-003 | Auditoría digital y diagnóstico de marca | Estratégico |
| DIV-ASE-004 | Cursos y talleres creativos | Cuello de Botella |
| DIV-DIS-001 | Identidad visual corporativa y manual de marca | Estratégico |
| DIV-DIS-002 | Diseño gráfico (piezas sueltas) | Rutinario |
| DIV-DIS-003 | Ilustración digital y key visuals | Cuello de Botella |
| DIV-DIS-004 | Packaging y empaques | Estratégico |
| DIV-DIS-005 | Rediseño / refresh de identidad | Apalancado |
| DIV-DIS-006 | Dirección de Arte (**no está en los formularios**) | Estratégico |
| DIV-EDI-001 | Editorial: libros y catálogos | Cuello de Botella |
| DIV-EDI-002 | Editorial: revistas y publicaciones digitales | Cuello de Botella |
| DIV-EDI-003 | Brochures y pitch decks | Rutinario |
| DIV-EDI-004 | Web corporativa y landing pages (UI/UX) | Estratégico |
| DIV-AUD-001 | Video corporativo (guion + rodaje + edición) | Estratégico |
| DIV-AUD-002 | Guion y storytelling audiovisual | Cuello de Botella |
| DIV-AUD-003 | Animación y motion graphics 2D/3D | Cuello de Botella |
| DIV-AUD-004 | Pack mensual de contenido vertical | Apalancado |
| DIV-AUD-005 | Fotografía publicitaria y comercial | Apalancado |
| DIV-SND-001 | Podcast / vodcast: producción y edición | Cuello de Botella |
| DIV-SND-002 | Diseño sonoro, mezcla y masterización | Cuello de Botella |
| DIV-SND-003 | Locución y voiceover | Cuello de Botella |
| DIV-PUB-001 | Planificación de campañas multimedia | Estratégico |
| DIV-PUB-002 | Ejecución y monitoreo de campañas | Apalancado |
| DIV-PUB-003 | Meta Ads (Facebook & Instagram) | Apalancado |
| DIV-PUB-004 | Campañas con influencers | Cuello de Botella |
| DIV-PUB-005 | Social media content | Apalancado |
| DIV-PUB-006 | Social media management | Apalancado |
| DIV-PUB-007 | Email marketing | Apalancado |
| DIV-EVE-001 | Lanzamiento de productos y experiencias de marca | Estratégico |
| DIV-EVE-002 | Organización y dirección de eventos corporativos | Estratégico |
| DIV-EVE-003 | Cobertura audiovisual (aftermovie) | Apalancado |
| DIV-EVE-004 | Streaming en vivo para eventos | Cuello de Botella |
| DIV-EVE-005 | Estands, material P.O.P. y ambientación | Cuello de Botella |

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

En el brief completo la ocasión ya llega con nombre de hito: Rebranding / renovación ·
Lanzamiento de producto o servicio · Apertura de tienda / sede · Campaña de temporada · Evento ·
Contenido recurrente · Otro.
