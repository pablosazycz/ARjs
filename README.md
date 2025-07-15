# AR.js Demo Project

Demo de realidad aumentada usando AR.js que funciona en GitHub Pages.

## 🚀 Demos Disponibles

### Para GitHub Pages (HTTPS):
- **Versión optimizada:** [github-pages.html](./github-pages.html)
- **Versión completa:** [index.html](./index.html)
- **Instrucciones:** [instrucciones.html](./instrucciones.html)

### Para desarrollo local:
- Usar cualquier servidor HTTP local en puerto 8080

## 📱 Uso en Móviles

### Chrome Android:
- ✅ Funciona perfectamente en HTTPS (GitHub Pages)
- ❌ Problemas en HTTP local

### Firefox Android:
- ✅ Funciona en HTTPS y HTTP

### Safari iOS:
- ✅ Funciona en ambos protocolos

## 🎯 Marcador AR

Necesitas el **marcador Hiro** para que funcione:
- [Descargar marcador](https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png)
- Imprímelo o muéstralo en otra pantalla
- Apunta la cámara hacia el marcador

## 🔧 Solución de Problemas

### La cámara se abre y se cierra:
1. **Usar la versión optimizada** (`github-pages.html`)
2. **Permitir permisos de cámara** completamente
3. **Verificar HTTPS** - GitHub Pages usa HTTPS automáticamente
4. **Probar en Firefox** si Chrome da problemas

### Errores comunes:
- `getUserMedia not supported`: Navegador muy antiguo
- `Permission denied`: Permisos de cámara denegados
- `No camera found`: Dispositivo sin cámara trasera

### Debug:
- Abre las **herramientas de desarrollador** (F12)
- Revisa la **consola** para mensajes de error
- Verifica que estés en **HTTPS**

## 🛠️ Desarrollo Local

```bash
# Servidor Python
python -m http.server 8080

# Servidor Node.js
npx http-server -p 8080

# Acceso desde móvil
http://TU_IP_LOCAL:8080
```

## 📋 Características

### Versión Completa (index.html):
- ✨ Animaciones complejas
- 🎨 Múltiples objetos 3D
- 📊 UI detallada
- 🔊 Efectos de vibración

### Versión Optimizada (github-pages.html):
- ⚡ Carga más rápida
- 🎯 Detección más estable
- 📱 Mejor rendimiento en móviles
- 🔍 Info de debug en tiempo real

## 🌐 Deployment en GitHub Pages

1. Sube los archivos a tu repositorio
2. Ve a Settings → Pages
3. Selecciona la rama main
4. Tu demo estará en: `https://tuusuario.github.io/tu-repositorio/`

## 📚 Tecnologías

- **A-Frame 1.3.0**: Framework de WebXR
- **AR.js 3.4.0**: Realidad aumentada en el navegador
- **WebRTC**: Acceso a la cámara
- **WebGL**: Renderizado 3D

## 🤝 Contribuir

1. Fork el proyecto
2. Crea una rama para tu feature
3. Haz commit de tus cambios
4. Push a la rama
5. Crea un Pull Request

---

**¡Disfruta experimentando con AR.js!** 🎯✨
