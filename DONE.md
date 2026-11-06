# Entrega — Florería Pétalos

Landing estática completa en index.html, styles.css y script.js. Sin build ni dependencias de ejecución. Abrí index.html o serví esta carpeta con python3 -m http.server 8080.

Incluye navegación, hero con pétalos CSS, tres propuestas de ramos con fotografía, cómo pedir, galería, CTA WhatsApp demo +54 11 5555-0303 y footer Demo conceptual. Lenguaje rioplatense, paleta solicitada, diseño responsive y reduced-motion. Navegación y contacto funcionan sin JS.

Cuatro imágenes creadas con Codex imagegen integrado, guardadas en assets/images/: hero-ramo.png (1600×900), wrap.png, vidriera.png y detalle.png (1200×900). Prompts completos en assets/images/PROMPTS.md. Son imágenes conceptuales, identificadas como IA en el footer.

SEO demo: meta noindex/nofollow, _headers con X-Robots-Tag, robots.txt con Allow: / (sin Disallow: /), favicon SVG. El archivo _headers requiere hosting compatible para aplicar el encabezado; el meta funciona en el HTML.

QA con Chromium/Playwright a 390 y 1280 px: sin desborde horizontal, todas las imágenes decodificadas, destinos internos válidos, cero errores JS, partículas ocultas con reduced-motion. Capturas revisadas visualmente en qa/390.png y qa/1280.png. Herramientas de QA locales en .qa; no son necesarias para servir el sitio. Se comprobó el destino del enlace WhatsApp; no se envió ningún mensaje ni se verificó la existencia del número ficticio.

No se publicó ni se usó git. Referencias y dirección visual en spec.md.
