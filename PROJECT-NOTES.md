
## Cuentas y accesos
- **GitHub**: github.com/gjosebwes-sketch
- **Dominio**: watertools.es (Hostinet, expira abril 2027)
- **DNS**: 4 registros A (185.199.108-111.153) + CNAME www → gjosebwes-sketch.github.io
- **Ko-fi**: ko-fi.com/gustavo90204
- **Email**: gustavo@watertools.es
- **LinkedIn**: linkedin.com/in/gustavo-blanco-walter

## DNS configurados en Hostinet
- A: @ → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- CNAME: www → gjosebwes-sketch.github.io
- TXT: google-site-verification (ya existente, NO borrar)
- MX: mail.watertools.es (NO borrar)

## Funcionalidades implementadas en index.html
- Tema claro/oscuro con preferencia guardada en localStorage
- Menú hamburguesa para móvil
- Partículas de agua animadas en hero (canvas)
- Contadores animados (30+ años, 5 herramientas, etc.)
- Sección de herramientas con iframes
- Métodos de análisis de agua (9 tarjetas)
- Descargas (enlace a GitHub Releases)
- Blog técnico (sección con artículos)
- Donación Ko-fi (sección + footer)
- Consultoría (sección + modal con formulario y validación)
- Sobre mí (perfil + redes sociales)
- Navegación activa por scroll
- Animaciones reveal con stagger

## Formulario de consultoría
- Funciona visualmente (validación, spinner, pantalla éxito)
- NO envía datos a ningún sitio todavía
- Para hacerlo real: usar Formspree (formspre.io) — gratis
- Buscar en el código el comentario "AQUÍ CONECTAS TU BACKEND REAL"

## SEO implementado
- Schema.org en index.html (WebSite, Person, ItemList)
- Meta tags optimizados (canonical, robots, og:type, og:locale, twitter:card)
- Artículo blog con Schema.org (Article, FAQPage, BreadcrumbList)
- robots.txt y sitemap.xml creados
- FALTA: verificar en Google Search Console

## Artículos de blog creados
1. `/tools/blog/conversion-4-20-ma-unidades-proceso.html` (4-20 mA y 0-20 mA)

## Artículos pendientes (orden prioridad SEO)
2. 4-20 mA vs Pulso en caudalímetros
3. Recuperación ósmosis inversa
4. Presión osmótica (cómo calcular)
5. Tipos de membranas de ósmosis inversa
6. Dimensionar torre de enfriamiento
7. Qué es un desalador electrostático

## Meta tags específicos por herramienta (PENDIENTE)
Cada archivo en /tools/*.html necesita sus propios:
- `<title>` específico
- `<meta name="description">` específico
- `<link rel="canonical">`
- `<meta property="og:title">`, `og:description`, `og:url`

## Monetización
- Ko-fi: activo (donación voluntaria €5)
- Consultoría: formulario listo (precios por definir: sugerencia 150-500€)
- Freemio (herramientas Pro): NO implementado todavía
- Stripe para facturas: NO implementado todavía

## Tareas pendientes
- [ ] Verificar en Google Search Console
- [ ] Crear artículos 2-7 del blog
- [ ] Añadir meta tags específicos a cada /tools/*.html
- [ ] Conectar Formspree al formulario de consultoría
- [ ] Crear favicon.svg real (actualmente puede ser placeholder)
- [ ] Configurar Google Analytics (opcional)
