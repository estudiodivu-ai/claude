# Formularios de Divú

| Archivo | Qué es | Estado |
|---|---|---|
| `brief-expres-diseno.html` | Brief exprés de diseño (identidad «Claqueta»), para incrustar en WordPress con un bloque "HTML personalizado". Envía a un receptor de Apps Script (`DIVU_ENDPOINT`). | `DIVU_ENDPOINT` vacío → modo demo (descarga un .json). |
| `brief-moodboard-av.html` (en Drive) | Brief de audiovisual. | Sin revisar. |

## Cómo lee el agente el brief exprés de diseño

El formulario ya calcula el código DIV y la categoría Kraljic de cada pieza:

| Pieza | Código | Kraljic |
|---|---|---|
| Post o carrusel para redes | DIV-DIS-002 | Rutinario |
| Flyer, afiche o banner | DIV-DIS-002 | Rutinario |
| Logo o identidad nueva | DIV-DIS-001 | Estratégico |
| Refrescar mi marca | DIV-DIS-005 | Apalancado |
| Empaque o etiqueta | DIV-DIS-004 | Estratégico |
| Ilustración o personaje | DIV-DIS-003 | Cuello de Botella |
| Presentación o brochure | DIV-EDI-003 | Rutinario |
| Otra cosa | DIV-DIS-002 | Rutinario → **el agente lo revisa con el campo "contexto"** |

Ocasión del formulario → hito de negocio:

| Respuesta | Hito |
|---|---|
| un lanzamiento | Lanzamiento |
| renovar mi imagen | Rebranding |
| una promoción o temporada | Campaña de temporada (Black Friday, Q4…) |
| un evento | Evento |
| mis redes de todos los días | Contenido (posible retainer) |
| abrir mi negocio | Apertura |
| otra cosa | Otra (revisar "contexto") |

Presupuesto del formulario → tier:

| Respuesta | Lectura del agente |
|---|---|
| Menos de $300 | Por debajo del ticket base ($334) → alerta "Presupuesto bajo el tier" |
| $300 – $800 | Ticket base; no llega a Esencial |
| $800 – $1,150 | Esencial |
| Más de $1,150 | Integral o Premium (el formulario no los distingue) |
| Ni idea, oriéntame | Sin alerta; recomendar sesión de briefing |

## Diferencias con lo que necesita el agente

1. **Falta "¿Cómo nos conociste?"** → sin ese campo no se puede calcular Asistida / No asistida.
2. **No pregunta quién aprueba** → no se puede detectar "más de un aprobador".
3. **Presupuesto:** falta separar $1,150-1,500 y más de $1,500 (Premium).
4. **Insumos no es obligatorio** → si viene vacío, el agente lo marca como faltante.
5. **No envía correo** → no hay "Nueva Solicitud" en Gmail ni confirmación automática al cliente.
   Depende del receptor de Apps Script.
6. **El cierre promete** "te escribimos en máximo 3 días hábiles para confirmar alcance y
   cotización": es un compromiso de plazo.
