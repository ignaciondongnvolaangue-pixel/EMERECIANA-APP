# EMERECIANA App 📱

App de estudio para Higiene y Epidemiología - 4º semestre

## Características
- ✅ Checklist de actividades con persistencia
- 📅 Vista por días con scroll horizontal
- 💾 Funciona offline
- 📲 Instalable en móvil como app nativa

## Cómo instalar en tu móvil

### En Android:
1. Abre Chrome y ve a la página donde está alojada la app
2. Toca los tres puntos del menú
3. Selecciona "Instalar aplicación" o "Añadir a pantalla de inicio"
4. ¡Listo! Aparecerá como una app más

### En iPhone:
1. Abre Safari y ve a la página
2. Toca el icono de compartir (cuadrado con flecha)
3. Desliza hacia abajo y selecciona "Añadir a pantalla de inicio"
4. Confirma el nombre y ya está

## Archivos incluidos
- `index.html` - La aplicación completa
- `manifest.json` - Configuración para PWA
- `sw.js` - Service Worker para offline
- `icon-192.png` - Icono para la app
- `icon-512.png` - Icono de alta resolución

## Para desarrolladores
Si quieres modificar la app:
1. Edita `index.html` para cambiar contenido o estilos
2. Los datos están en el array `dias` dentro del script
3. El progreso se guarda automáticamente en localStorage