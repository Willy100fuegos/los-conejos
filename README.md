# Los Conejos

Dashboard Mystery Shopper

Demo: https://willy100fuegos.github.io/los-conejos/

Descripción
-----------
"Los Conejos" es un dashboard estático orientado a visualizar y gestionar información de Mystery Shopper (comprador encubierto). Está construido con HTML/CSS/JS y pensado para desplegarse fácilmente en GitHub Pages.

Características principales
--------------------------
- Interfaz de tablero (dashboard) para visualizar métricas y resultados.
- Visualizaciones simples (gráficas / tablas).
- Estructura estática fácil de desplegar y modificar.
- Ideal como prototipo o plantilla para proyectos de Mystery Shopper.

Tecnologías
-----------
- HTML
- CSS
- JavaScript
- (Opcional) Librerías de visualización como Chart.js o D3.js si se amplía

Vista previa / Demo
-------------------
Accede a la versión desplegada en GitHub Pages:
- https://willy100fuegos.github.io/los-conejos/

Cómo usar / Ejecutar localmente
------------------------------
1. Clona el repositorio:
```bash
git clone https://github.com/Willy100fuegos/los-conejos.git
cd los-conejos
```

2. Abrir directamente
- Abre `index.html` en tu navegador (suficiente para contenido estático).

3. Servidor local (recomendado para evitar restricciones de CORS con fetch):
```bash
# Python 3
python -m http.server 8000
# Luego visita http://localhost:8000
```

Estructura sugerida del repositorio
-----------------------------------
- index.html — Punto de entrada del dashboard
- /assets — Imágenes, iconos y fuentes
- /css — Hojas de estilo
- /js — Lógica del frontend y visualizaciones
- /data — (Opcional) JSON o CSV de ejemplo

Desarrollo y personalización
----------------------------
- Añade o reemplaza componentes en `index.html`.
- Agrega gráficos conectando datos reales (fetch a un JSON o API).
- Integra librerías como Chart.js para gráficas más completas:
```html
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
```

Buenas prácticas
---------------
- Mantén los datos sensibles fuera del repositorio público.
- Si necesitas una API, considera crear un backend separado y usar variables de entorno.
- Añade pruebas visuales o end-to-end si el proyecto crece.

Contribuir
----------
1. Haz fork del repositorio.
2. Crea una rama con tu mejora: `git checkout -b feature/mi-mejora`
3. Haz commits claros y descriptivos.
4. Abre un Pull Request describiendo los cambios y su propósito.

Licencia
--------
Actualmente este repositorio no incluye un archivo de licencia. Si deseas compartirlo públicamente con condiciones, añade un archivo `LICENSE` (por ejemplo MIT) o indícalo en este README.

Contacto
--------
Author: Willy100fuegos  
Repositorio: https://github.com/Willy100fuegos/los-conejos
