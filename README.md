# STARMEDICA Web

Proyecto web estático para STARMEDICA S.A.S, clínica especializada en cardiología no invasiva. Diseño moderno, accesible y responsive, construido con Tailwind CSS. Este proyecto también presenta cómo **MVL Marketing** potencia organizaciones de salud con soluciones integrales de marketing, automatización y desarrollo.

## Detalles de Diseño
- **Tipografía:** Encabezados con `Outfit`, texto con `DM Sans` para alta legibilidad.
- **Paleta:** Azul (`#252DFF`) y rojo corporativo para énfasis; grises neutros para fondos.
- **Componentes:** Cards con sombras suaves, botones con efecto glow, secciones con animaciones (`reveal-up`, `reveal-scale`).
- **Modales:** Capa `modal-overlay` con transición de opacidad y `modal-content` con escala suave; estado inicial con `opacity: 0` y `visibility: hidden`, se activan con la clase `show`.
- **Accesibilidad:** Contrastes adecuados, iconografía `Lucide` y navegación clara.

## Tecnología
- **Stack:** HTML + Tailwind CSS (compilado a `dist/output.css`), JS ligero para modales y sliders.
- **Build:** `npx tailwindcss -i ./src/input.css -o ./dist/output.css --minify`.
- **Estructura:**
  - `src/input.css`: estilos fuente y utilidades.
  - `dist/output.css`: CSS compilado para producción.
  - `img/`: recursos gráficos optimizados.

## Branding
Somos expertos creando herramientas de tecnología para empresas de salud y clínicas. Proyecto desarrollado por [MVL](https://mvlmkt.com/) Marketing.

- **Marca:** La palabra "MVL." utiliza la tipografía Cyberjunkies.
- **Fuente Cyberjunkies:** incluida en `font/Cyberjunkies/`.
  - `Cyberjunkies.ttf`, `Cyberjunkies.otf`
  - `Cyberjunkies Italic.ttf`, `Cyberjunkies Italic.otf`
  - `cyberjunkies.css` (declaraciones `@font-face`)
  - `license.txt`

### Uso de la fuente Cyberjunkies
1. Incluir el CSS de la fuente donde se requiera:
   ```html
   <link rel="stylesheet" href="font/Cyberjunkies/cyberjunkies.css">
   ```
2. Aplicar la clase utilitaria para la marca:
   ```html
   <span class="font-cyberjunkies">MVL.</span>
   ```

## MVL Marketing: Solución para Empresas de Salud
**MVL Marketing** es un partner tecnológico para clínicas y empresas como STARMEDICA. Unificamos estrategia y ejecución en tres pilares:

- **Marketing:** posicionamiento digital, contenido médico, campañas multicanal y medición de resultados.
- **Automatización:** flujos de contacto y seguimiento (email/SMS/WhatsApp), recordatorios de cita, chatbots, integraciones con CRM/HIS.
- **Desarrollo:** sitios web, portales de pacientes, dashboards, APIs e integraciones seguras.

Beneficios clave:
- **Experiencia paciente optimizada:** agendamiento ágil, comunicaciones oportunas y rutas claras de servicio.
- **Eficiencia operativa:** menos tareas manuales, más trazabilidad y datos útiles para la gestión.
- **Escalabilidad:** infraestructura y procesos listos para crecer.

Conoce más y solicita una demo en [MVL](https://mvlmkt.com/) Marketing.

## Enlaces y Contacto
- Sitio: `starmedica.co`
- Desarrollado por: [MVL](https://mvlmkt.com/) Marketing

## Despliegue
Subida vía SSH/SCP al hosting (`starmedica.co/`). Estructura de carpetas replicada: HTML en raíz, `img/`, `src/`, `dist/`, `other/`, y `font/`.
