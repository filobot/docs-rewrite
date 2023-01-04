Aquí encontrará información no exhaustiva sobre cómo funciona Cloudflare en nuestros dominios y servicios.

# ¿Qué es Cloudflare?

Cloudflare es una de las mayores redes que operan en Internet. La gente utiliza los servicios de Cloudflare con el fin de aumentar la seguridad y el rendimiento de sus sitios y servicios web.

## ¿Cómo nos ayuda Cloudflare?

Cloudflare nos ayuda a mantener nuestro sitio web a salvo de atacantes con intenciones maliciosas y acelera nuestro sitio web en todo el mundo.

# Acerca de una prohibición de Cloudflare

Una tarea muy importante para Cloudflare es protegernos de los ataques DDoS que podrían llevar nuestro servicio fuera de línea y, para ello, automatizamos los sistemas para que las prohibiciones puedan ser enviadas a atacantes o dispositivos victimizados por el atacante.

> Nos tomamos muy en serio todas las prohibiciones que otorgamos y no dudaremos en priorizar protegernos en este tipo de situaciones.
  {.is-info}

Hay dos tipos de prohibiciones que utilizamos:
- **Prohibiciones temporales**: Respondidos con el código 403 seguido por el mensaje "Acceso Denegado".
- **Prohibiciones permanentes**: Respondidos con el código 403 seguido por el mensaje "Acceso Denegado".

\* También se especificará el tipo de baneo recibido.

> En algunas situaciones, un [captcha](https://www.hcaptcha.com) puede ser requerido antes de acceder a nuestro sitio web, como una alternativa a las prohibiciones de Cloudflare.
  {.is-info}

Objetos que pueden ser prohibidos:
- Tu dirección IP.
- Tu Proveedor de Servicios de Internet[^1].
- Tu rango de dirección IP[^2].
- El agente de usuario de tu navegador.
- Tu país.
- El tipo de navegador [🕵️](https://www.torproject.org/) que utilices.

\* No todos los objetos se mencionan aquí.

> Cuando se emite una prohibición, se le prohíbe acceder a cualquier servicio o página de nuestro sitio web mientras la prohibición está en vigor.
  {.is-danger}

### Prohibiciones temporales

Estas son prohibiciones que normalmente expiran después de **1 hora** de ser emitidas.

> Estas sanciones no se pueden apelar.
  {.is-danger}

### Prohibiciones permanentes

Estas prohibiciones nunca expiran una vez que se emiten.

> Si crees que tu prohibición es injusta o incorrecta, apela **[haciendo clic aquí](https://forms.gle/Pdig38H5gn6XfyW76)**.
  {.is-info}

> Haciendo una apelación no te asegura de que vayas a ser desbaneado, sólo asegura que revisaremos a fondo tu caso.
  {.is-warning}

# ¿Qué acciones están prohibidas?

> No todas las acciones se muestran aquí por razones de seguridad.
  {.is-warning}

## Excesos de errores 429[^3]

Nuestro servicio tiene dos tipos de límites de tarifa:
- **Individual o específico** (API): Son diferentes para cada punto final y restrictivos a corto plazo. Exceder estos limites de tarifa no da como resultado una prohibición de Cloudflare.
- **Global o común** (Genérica): Son iguales para cada punto final y restrictivos a largo plazo. Exceder estos limites de tarifa da lugar a una prohibición de Cloudflare.

Respeta los limites de tarifa independientemente de lo que son. La API no es accesible públicamente, así que no esperamos que la utilices, pero, si lo haces, verifica los encabezados de `X-RateLimit` para asegurarte de respetar los límites de tarifa.

> Si recibes repetidamente **errores 429**, hay una buena probabilidad de que se emita una prohibición de cloudflare. Si sucede con frecuencia, recibirás una prohibición permanente de Cloudflare.
  {.is-danger}

[^1]: Nos referimos a la empresa que le proporciona el servicio de conexión a Internet.
[^2]: Puedes averiguar su rango de direcciones IP haciendo clic **[aquí](https://www.calculator.net/ip-subnet-calculator.html)**.
[^3]: Los errores 429 indican a los navegadores y aplicaciones, que hacen solicitudes de cualquier tipo a nuestro sitio web, que su límite de velocidad está siendo excedido.
