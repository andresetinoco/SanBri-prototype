# Correos de bienvenida de San Bri

Se envían una sola vez, al crear la cuenta. Al registrarse la persona elige "Busco un inmueble" o "Soy corredor inmobiliario o aliado" y recibe el correo que le corresponde.

| Plantilla | Para | Asunto |
|---|---|---|
| `bienvenida-cliente.html` | Clientes | {{nombre}}, tu cuenta en San Bri está activa: ya puedes ver los precios |
| `bienvenida-aliado.html` | Corredores y aliados (B2B) | 🤝 {{nombre}}, acceso B2B activado: precios desbloqueados para cierres compartidos (opción A) |

- Remitente: `San Bri <ebricennosanbri@gmail.com>`. Para enviar desde Resend con ese remitente hay que verificar un dominio propio; una dirección @gmail.com no se puede verificar en Resend. Recomendado: enviar desde `hola@san-bri.com` con `Reply-To: ebricennosanbri@gmail.com`, o enviar por la API de Gmail con esa cuenta.
- Variable: `{{nombre}}` = nombre de pila de la persona.
- Enlaces: catálogo `https://www.san-bri.com/comprar` (dominio por confirmar), WhatsApp `https://wa.me/584141356110` con mensaje prellenado. El canal de aliados usa el mismo número hasta que San Bri dé uno aparte.
- HTML con tablas y estilos en línea para que se vea bien en Gmail, Outlook y Apple Mail. Los emojis se mantienen (👉 y 🤝 se ven bien en los clientes de correo actuales).
- Pie legal: Corredores Reob C.A. · RIF J-31658884-0.
