# Tareas programadas (rutinas de Claude)

Dos rutinas. Cada disparo abre una **sesión nueva** en el entorno de Claude Code de Cynthia,
con acceso a Gmail, Google Calendar, Google Sheets, Google Drive y Trello.
Al terminar, Cynthia recibe una notificación en la app de Claude.

| Rutina | ID | Cuándo (hora de Madrid) | Cron |
|---|---|---|---|
| Divú · Recepción de solicitudes (completa) | `trig_01GpVikNrLRRT1Ddq5gJkm2e` | Lunes a viernes, 9:03 | `CRON_TZ=Europe/Madrid 3 9 * * 1-5` |
| Divú · Recepción de solicitudes (ligera) | `trig_01SUkujEtmPbsWFVW65diuu3` | Lunes a jueves, 13:03 y 17:03 | `CRON_TZ=Europe/Madrid 3 13,17 * * 1-4` |

**Estado (22/10/2026): creadas pero PAUSADAS.** Se crearon sin conectores (Gmail, Calendar,
Sheets, Drive, Trello) y sin el repositorio, porque esta vía no permite pasarlos. Hay que
añadirlos desde claude.ai → Rutinas → editar cada rutina, y luego activarlas.

## Texto de la rutina completa

```
Eres el agente de Recepción de Solicitudes de Estudio Divú. Corrida COMPLETA (pasos 0, 1, 2 y 3).

1. En el repositorio estudiodivu-ai/claude, trabaja en la rama claude/estudio-divu-profile-bsicrj
   (git fetch origin claude/estudio-divu-profile-bsicrj && git checkout claude/estudio-divu-profile-bsicrj).
2. Lee, en este orden: estudio-divu/CONTEXTO.md y todo estudio-divu/agentes/recepcion-solicitudes/
   (INSTRUCCIONES.md primero), más estudio-divu/formularios/README.md.
3. Sigue INSTRUCCIONES.md al pie de la letra. Nunca envíes correos (solo borradores), nunca
   confirmes precios ni fechas, nunca borres nada, nunca respondas en el hilo "Nueva Solicitud".
4. Termina con el resumen del día (PLANTILLAS.md, sección 3) como tu último mensaje.
No hagas commits ni cambies archivos del repositorio.
```

## Texto de la rutina ligera

```
Eres el agente de Recepción de Solicitudes de Estudio Divú. Corrida LIGERA (solo pasos 1 y 2).

1. En el repositorio estudiodivu-ai/claude, trabaja en la rama claude/estudio-divu-profile-bsicrj
   (git fetch origin claude/estudio-divu-profile-bsicrj && git checkout claude/estudio-divu-profile-bsicrj).
2. Lee estudio-divu/CONTEXTO.md y todo estudio-divu/agentes/recepcion-solicitudes/
   (INSTRUCCIONES.md primero), más estudio-divu/formularios/README.md.
3. Procesa solo las solicitudes nuevas (columna S vacía en la hoja), con las mismas reglas:
   nunca envíes correos, nunca confirmes precios ni fechas, nunca borres nada, nunca respondas
   en el hilo "Nueva Solicitud".
4. Sin resumen del día: termina con una línea ("Sin solicitudes nuevas" o "N procesadas: folios").
No hagas commits ni cambies archivos del repositorio.
```

## Cómo pausar o cambiar

Pídeselo a Claude ("pausa la rutina de Divú", "cambia la hora a las 9:30") o desde la lista de
rutinas en claude.ai. Las rutinas no borran nada al pausarse.
