# Tarea programada (rutina de Claude)

Una rutina. Cada disparo abre una **sesión nueva** en el entorno de Claude Code de Cynthia.
Al terminar, Cynthia recibe una notificación en la app de Claude con el resumen.

| Rutina | ID | Cuándo (hora de Madrid) | Cron |
|---|---|---|---|
| Divú · Planificación (revisión del domingo) | `trig_013n4VSkTZz1mKW2pZpHqHoF` | Domingo, 18:03 | `CRON_TZ=Europe/Madrid 3 18 * * 0` |

**Estado (26/10/2026): creada y activa; primera corrida el domingo 1 nov a las 18:03.** Se creó con
todos los conectores de la cuenta; solo usa Google Sheets, Trello, Google Calendar y Google Drive.
Repositorio añadido por Cynthia el 29 oct.

## Texto de la rutina

```
Eres el agente de Planificación · S&OP de Estudio Divú (revisión del domingo).

1. En el repositorio estudiodivu-ai/claude, trabaja en la rama claude/estudio-divu-profile-bsicrj
   (git fetch origin claude/estudio-divu-profile-bsicrj && git checkout claude/estudio-divu-profile-bsicrj).
2. Lee, en este orden: estudio-divu/CONTEXTO.md y todo estudio-divu/agentes/planificacion/
   (INSTRUCCIONES.md primero, luego FUENTES.md).
3. Sigue INSTRUCCIONES.md al pie de la letra. Solo lees: no envíes correos, no crees eventos,
   no muevas tarjetas, no edites hojas ni documentos, no borres nada.
4. Termina con el resumen en el formato de INSTRUCCIONES.md como tu último mensaje, en español.
   Sin nombres, correos ni datos de pago de clientes: solo IDs de pedido.
No hagas commits ni cambies archivos del repositorio.
```

## Cómo pausar o cambiar

Pídeselo a Claude ("pausa la revisión del domingo", "cámbiala a las 19:00") o desde la lista de
tareas programadas en claude.ai.
