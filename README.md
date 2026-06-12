# Demo — Invitación Digital XV Años (Valentina)

Demo de venta para el negocio de invitaciones digitales (Viva Comonfort · Invitaciones).
Quinceañera ficticia. Evento: sábado 21/11/2026, Comonfort/Empalme Escobedo.

## Ver localmente

```bash
cd ~/invitaciones/demo-xv && python3 -m http.server 8731
# abrir http://localhost:8731/
```

## Personalización por invitado (feature premium)

Cada invitado puede recibir un link único:

```
http://localhost:8731/?invitado=Familia+Ramírez&pases=4
```

- Muestra "Invitación especial para: Familia Ramírez · 4 pases reservados"
- El botón RSVP pre-llena el WhatsApp con nombre y número de personas

## Qué incluye

- Portada con ornamentos SVG hechos a mano (sin assets externos)
- Cuenta regresiva en vivo al 21/11/2026 6:00 pm
- Itinerario, ubicaciones con botón Google Maps, dress code, galería, lluvia de sobres
- RSVP por WhatsApp (número actual: +1 657 377 6892, USA — mover a número mexicano dedicado cuando el negocio valide)
- Música: vals generado con Web Audio API — **cero riesgo de derechos de autor**
- Footer con CTA del negocio ("Pide la tuya desde $399") — loop viral: cada invitado lo ve

## Fotos

`img/` — fotos de Unsplash (licencia Unsplash: uso comercial permitido, sin atribución requerida).
En invitaciones reales se reemplazan por las fotos del cliente.

## Antes de publicar

1. Hospedar (GitHub Pages / Railway) y poner URL absoluta en `og:image` para el preview de WhatsApp
2. Cambiar el número de WhatsApp del footer/RSVP al número del negocio (NO el del carwash — separar números por política de Meta)
3. Decidir vigencia de la página (ej. "tu invitación vive 6 meses")
