# 🌑 Eclipse Solar Total · 12 agosto 2026

Herramientas interactivas para seguir y preparar el eclipse solar total del **12 de agosto de 2026**, visible desde España y parte de Europa.

🔗 **[Ver mapa de sombras](https://tuusuario.github.io/tu-repo/eclipse-solar-2026sombras.html)**  
🔗 **[Abrir brújula AR](https://tuusuario.github.io/tu-repo/brujula_profesional.html)**

---

## Herramientas incluidas

### 🗺️ Mapa de sombras — `eclipse-solar-2026sombras.html`

Mapa interactivo (Leaflet) que muestra la trayectoria del eclipse solar total del 12 de agosto de 2026. Permite:

- Visualizar la banda de totalidad y las zonas de eclipse parcial
- Consultar el porcentaje de cobertura solar según la ubicación
- Explorar los horarios locales de cada fase del eclipse

### 🧭 Brújula AR — `brujula_profesional.html`

Brújula de realidad aumentada orientada al eclipse. Funciona desde el navegador del móvil y permite:

- Apuntar el dispositivo hacia el Sol en tiempo real usando la brújula y el giroscopio
- Ver el azimut y altitud solar en cada momento del eclipse
- Simular las fases del eclipse con un slider de tiempo
- Indicación visual de la fase actual (parcial / totalidad)

> ⚠️ Requiere un navegador moderno con acceso a sensores de orientación (recomendado: Chrome o Safari en móvil). Solicita permiso para usar el giroscopio en iOS.

---

## Uso

No requiere instalación ni servidor. Basta con abrir los archivos `.html` directamente en el navegador, o acceder a través de los enlaces de GitHub Pages.

---

## Tecnologías

- HTML5 + CSS3 + JavaScript puro (sin dependencias en la brújula)
- [Leaflet.js](https://leafletjs.com/) para el mapa interactivo
- API de orientación del dispositivo (`DeviceOrientationEvent`) para la brújula AR

---

## Licencia

Proyecto de uso libre. Puedes compartirlo, adaptarlo o incrustarlo en tu web.
