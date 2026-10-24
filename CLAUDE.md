Actúa como mi asistente de desarrollo web y despliegue. Trabajamos en el proyecto "reformas_barcelona", una web estática de una empresa de reformas en Barcelona.

PASO 1: LEER EL PROYECTO (sin modificar nada todavía)
Lee estos archivos de la carpeta del proyecto:
- CLAUDE.md: instrucciones generales del proyecto.
- DESIGN.md: sistema de diseño (colores, tipografías, componentes, tono).
- index.html: página principal actual.
- code.html y screen.png: exportación original del diseño (referencia visual).
Resúmeme en 5-8 líneas lo que has entendido del proyecto, y dime si hay contradicciones entre CLAUDE.md, DESIGN.md e index.html.

PASO 2: HACER PERSISTENTES LAS INSTRUCCIONES
Crea o actualiza un archivo de reglas del proyecto, en el formato de reglas que use Antigravity para el workspace (por ejemplo dentro de .agent/rules/), y un AGENTS.md en la raíz, con el contenido esencial de CLAUDE.md y DESIGN.md, para que se apliquen en todas las sesiones futuras sin que yo tenga que repetirlas. Deben incluir:
1. Idioma: toda la web y las respuestas en español de España.
2. Negocio: empresa de reformas en Barcelona; objetivo principal de la web = que el visitante pida presupuesto (formulario, teléfono o WhatsApp).
3. Diseño: respetar siempre DESIGN.md (paleta, tipografía, espaciado, estilo de botones). No cambiar el estilo visual sin que yo lo pida.
4. Tecnología: HTML/CSS/JS estáticos, sin frameworks ni dependencias innecesarias. index.html es la página principal; no tocar code.html ni screen.png (solo referencia).
5. Calidad: diseño responsive (móvil primero), buena accesibilidad (alt en imágenes, contraste, etiquetas en formularios), carga rápida (imágenes optimizadas, lazy loading).
6. SEO local: title y meta description con "reformas en Barcelona", un solo H1, datos estructurados LocalBusiness (JSON-LD), sitemap.xml y robots.txt.
7. Seguridad y legal: no incluir claves ni datos privados en el código; mantener enlaces a Aviso legal, Política de privacidad y Política de cookies, y un aviso de cookies si hay analítica.
8. Forma de trabajar: antes de cambios grandes, dime el plan en pocas líneas; después de cada cambio, resume qué has tocado; no borres archivos sin preguntarme.
Cuando termines, enséñame el contenido de los archivos de reglas creados y dime dónde han quedado.

PASO 3: REVISIÓN PREVIA A PUBLICAR
Revisa index.html y dime una lista corta de problemas antes de subirlo: enlaces rotos, imágenes sin alt o muy pesadas, textos de relleno (lorem ipsum, teléfonos o emails de ejemplo), falta de meta etiquetas, formulario que no envía nada, problemas en móvil. Corrígelos solo después de que yo confirme.

PASO 4: PUBLICAR LA WEB
Explícame en pocas líneas las opciones gratuitas o baratas para hospedar una web estática (por ejemplo Firebase Hosting, Netlify, Vercel, GitHub Pages o Cloudflare Pages), recomiéndame una para mi caso y pregúntame cuál prefiero, y si ya tengo dominio.
Después guíame paso a paso, un paso cada vez, esperando a que yo confirme:
1. Preparar la carpeta (renombrar o estructurar archivos si hace falta).
2. Inicializar git y subirlo a un repositorio de GitHub (si la opción elegida lo necesita).
3. Conectar con el servicio de hosting y publicar.
4. Conectar mi dominio y activar HTTPS.
5. Configurar un formulario de contacto que funcione de verdad (por ejemplo con un servicio de formularios o una función sencilla) y comprobar que me llega el correo.
6. Comprobación final de la web publicada: abrir la URL, probar móvil, formulario, enlaces y velocidad.
Si necesitas ejecutar comandos en la terminal, muéstrame primero qué hace cada comando y pídeme permiso. Si necesitas datos míos (dominio, correo, teléfono, cuentas), pídemelos tú.

Empieza por el PASO 1.