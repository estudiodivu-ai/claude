# Plantillas

Tono Divú: cercano, creativo, con humor sutil, pero claro. Idioma según el país del cliente
(ver `../../CONTEXTO.md`). Todos los correos a clientes quedan como **borrador**.

## 0. Confirmación automática

La envía el receptor de Apps Script al instante ("Recibimos tu solicitud · Estudio Divú · {folio}").
El agente no la toca.

## 1. Acuse de recibo (+ datos faltantes, si aplica)

**Asunto:** Recibimos tu solicitud ✨ · Estudio Divú

> Hola, {nombre}:
>
> ¡Gracias por escribirnos! Ya tenemos tu solicitud de **{servicio}** para **{empresa}**
> y está en nuestra mesa (la de verdad, la que tiene café).
>
> En los próximos días hábiles revisamos todo con calma y te contamos cómo seguimos.
>
> {SOLO SI FALTAN DATOS:}
> Para armar algo a tu medida, nos faltan un par de piezas del rompecabezas:
> - {dato faltante 1}
> - {dato faltante 2}
>
> Puedes responder a este mismo correo.
> {FIN}
>
> Un abrazo,
> Cynthia
> Dirección de Arte Publicitaria · Estudio Divú
> estudiodivu.art · estudiodivu@gmail.com

**Prohibido en este correo:** precios, montos, tiers, fechas de entrega o de inicio,
"aceptamos", "confirmado".

## 2. Respuesta a mensajes por WhatsApp o Instagram

> ¡Hola! Gracias por escribirnos 🙌 Para darte una respuesta a tu medida (y no perdernos
> nada en el camino), te pedimos que nos cuentes tu proyecto en este formulario:
> diseño (logo, posts, empaques…): https://estudiodivu.art/brief-diseno/
> cualquier otro proyecto: https://estudiodivu.art/solicitar-proyecto/
> Te respondemos en 1 día hábil, de lunes a jueves (hora de España).

## 3. Resumen del día (en Claude, no por correo)

El resumen es **el mensaje final de la sesión de Claude** de la corrida de las 9:03.
Cynthia lo lee en la app de Claude (le llega una notificación). **No se crea borrador en Gmail.**

```
☕ Divú · Solicitudes del {fecha}

🆕 {n} solicitudes nuevas
  • {Folio} · {Empresa} · {Servicio} · {Kraljic} · {tier} · recomiendo: {siguiente paso}
    🚨 {alertas, si hay} · Tarjeta: {link}

⏳ Esperando datos: {n} (la más antigua: {empresa}, desde {fecha})
✅ Pasadas a Proyectos: {lista o "ninguna"}
📝 Borradores esperando tu OK en Gmail: {n}
👀 Necesito tu ojo: {dudas o errores, o "nada, todo en orden"}
🔧 Acciones del agente en Trello hoy: {n}   ← solo el primer mes
```
