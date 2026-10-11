# Estructura en Trello (plan gratuito)

Límites del plan: máx. 10 tableros por espacio de trabajo, sin campos personalizados,
archivos de 10 MB → los archivos pesados van como link a Drive.

## Tablero "Solicitudes"

https://trello.com/b/fmQkk065/solicitudes

Columnas, en orden:
1. Nueva
2. Esperando datos
3. Lista para decidir
4. Propuesta enviada
5. Aceptada
6. Reserva
7. Rechazada

## Tablero "Proyectos"

https://trello.com/b/3Qqh0VgV/proyectos

Una tarjeta por proyecto (nunca un tablero por proyecto). Columnas, en orden:
1. Brief + anticipo
2. Contrabrief
3. Producción
4. Ronda 1
5. Ronda 2
6. Finales y cobro
7. Entregado

## Etiquetas (en ambos tableros)

| Grupo | Etiqueta | Color |
|---|---|---|
| Kraljic | Estratégico | morado |
| Kraljic | Apalancado | azul |
| Kraljic | Rutinario | verde |
| Kraljic | Cuello de Botella | naranja |
| Origen | Asistida | celeste |
| Origen | No asistida | amarillo |
| Alertas | Presupuesto bajo el tier | rojo |
| Alertas | Fecha inviable | rosa |

Las etiquetas se crean a mano en Trello (la conexión no permite crearlas ni renombrarlas).
El agente las busca **por nombre**; si no encuentra una, lo avisa en el resumen del día.

## Tarjeta de solicitud

**Título:** `<Empresa> · <Servicio> · <Ocasión>`

**Descripción (ficha):**

```
👤 Quién
Empresa: …
SPOC: Nombre · correo · WhatsApp

🎯 Qué pide
Servicio: … (DIV-XXX-00)
Kraljic: … → Ruta sugerida: propio / aliado / white-label

📅 Ocasión: …

⏱️ Fecha vs. capacidad
Pide: dd/mm/aaaa · Horas estimadas: … · Libres hasta esa fecha: … → ✅ / ⚠️ / ❌

💰 Presupuesto vs. tier
Rango del cliente: … · Tier sugerido: … → ✅ / ⚠️

📦 Insumos
Tiene: … · Faltan: …

🚨 Alertas
• …

👉 Siguiente paso recomendado
… (motivo en una línea)

📝 Brief precargado: <link>
📧 Correo original: <link>
📊 Fila en la hoja: <n.º de fila>
```

**Vencimiento de la tarjeta:** la fecha límite que pidió el cliente.
