# Reproductor de Música Web

Un reproductor de música web simple y elegante con interfaz visual personalizada.

## 📋 Descripción

Este proyecto es un reproductor de música web minimalista que combina controles de audio HTML5 nativos con una interfaz visual atractiva. Perfecto para mostrar una canción específica con su carátula correspondiente de manera elegante.

## 🎵 Características

- **Reproductor HTML5**: Controles de audio nativos del navegador
- **Carátula Visual**: Imagen de la canción/artista
- **Diseño Minimalista**: Interfaz limpia y enfocada
- **Responsive**: Se adapta a diferentes tamaños de pantalla
- **Formato MP3**: Soporte completo para archivos de audio MP3
- **Controles Nativos**: Play/Pause, volumen, barra de progreso

## 🎧 Contenido Actual

- **Canción**: TinyTim.mp3
- **Carátula**: tiny.jpg
- **Artista**: [Información del artista]

## 🛠️ Tecnologías Utilizadas

- HTML5 Audio API
- CSS3 para estilos personalizados
- Estructura semántica HTML5
- Responsive Web Design

## 📁 Estructura del Proyecto

```
reproductor-musica/
│
├── index.html              # Página principal
├── css/
│   └── styles.css         # Estilos del reproductor
├── img/
│   └── tiny.jpg           # Carátula de la canción
├── TinyTim.mp3            # Archivo de audio
└── README.md              # Este archivo
```

## 🚀 Instalación y Uso

### Uso Local
1. **Descargar** todos los archivos del proyecto
2. **Asegurar** que el archivo `TinyTim.mp3` esté en la raíz
3. **Verificar** que la imagen `tiny.jpg` esté en la carpeta `img/`
4. **Abrir** `index.html` en tu navegador web

### Servidor de Desarrollo
```bash
# Con Python
python -m http.server 8000

# Con Node.js
npx live-server

# Con PHP
php -S localhost:8000
```

**Nota**: Algunos navegadores requieren un servidor para reproducir archivos de audio locales por seguridad.

## 🎨 Personalización

### Cambiar Canción
1. **Reemplazar** el archivo `TinyTim.mp3` con tu archivo de audio
2. **Actualizar** la referencia en el HTML:

```html
<audio controls>
    <source src="tu-cancion.mp3" type="audio/mpeg">
    Tu navegador no soporta el elemento audio.
</audio>
```

### Cambiar Carátula
1. **Reemplazar** `tiny.jpg` con tu imagen
2. **Actualizar** la referencia:

```html
<div class="imgBx">
    <img src="img/tu-imagen.jpg" alt="Carátula de la canción">
</div>
```

### Personalizar Estilos
Edita `css/styles.css` para modificar:
- Tamaño del reproductor
- Colores y efectos
- Animaciones
- Layout responsive

## 📱 Formatos de Audio Soportados

### Principales
- **MP3**: Máxima compatibilidad
- **WAV**: Alta calidad, archivos grandes
- **OGG**: Buena compresión, soporte limitado
- **AAC**: Buena calidad y compresión

### Ejemplo Multi-formato
```html
<audio controls>
    <source src="cancion.mp3" type="audio/mpeg">
    <source src="cancion.ogg" type="audio/ogg">
    <source src="cancion.wav" type="audio/wav">
    Tu navegador no soporta audio HTML5.
</audio>
```

## 🎛️ Controles Avanzados

### Controles Personalizados
```html
<audio id="miAudio" preload="auto">
    <source src="TinyTim.mp3" type="audio/mpeg">
</audio>

<div class="controles-personalizados">
    <button onclick="reproducir()">▶️</button>
    <button onclick="pausar()">⏸️</button>
    <input type="range" id="volumen" min="0" max="1" step="0.1" value="0.5">
</div>
```

### JavaScript para Controles
```javascript
const audio = document.getElementById('miAudio');

function reproducir() {
    audio.play();
}

function pausar() {
    audio.pause();
}

function cambiarVolumen() {
    const volumen = document.getElementById('volumen');
    audio.volume = volumen.value;
}
```

## 🎨 Mejoras Visuales Sugeridas

### Animaciones CSS
- Rotación de la carátula durante reproducción
- Efectos de pulso sincronizados
- Transiciones suaves en controles

### Visualización de Audio
- Barras de ecualizador
- Ondas de sonido animadas
- Partículas reactivas al audio

### Información Adicional
- Título de la canción
- Nombre del artista
- Duración total
- Tiempo transcurrido

## 📊 Funcionalidades Adicionales

### Lista de Reproducción
```html
<div class="playlist">
    <div class="cancion" data-src="cancion1.mp3">Canción 1</div>
    <div class="cancion" data-src="cancion2.mp3">Canción 2</div>
    <div class="cancion" data-src="cancion3.mp3">Canción 3</div>
</div>
```

### Metadata del Audio
```javascript
audio.addEventListener('loadedmetadata', function() {
    console.log('Duración:', audio.duration);
    console.log('Puede reproducir:', audio.canPlayType('audio/mpeg'));
});
```

### Eventos del Reproductor
```javascript
audio.addEventListener('play', () => console.log('Reproduciendo'));
audio.addEventListener('pause', () => console.log('Pausado'));
audio.addEventListener('ended', () => console.log('Terminado'));
audio.addEventListener('timeupdate', actualizarProgreso);
```

## 📱 Compatibilidad

### Navegadores Desktop
- ✅ Chrome 4+
- ✅ Firefox 3.5+
- ✅ Safari 3.1+
- ✅ Edge 12+
- ⚠️ Internet Explorer 9+

### Navegadores Móviles
- ✅ iOS Safari 3.2+
- ✅ Android Browser 2.3+
- ✅ Chrome Mobile
- ✅ Firefox Mobile

## 🔧 Optimizaciones

### Performance
- **Preload**: Usar `preload="metadata"` para carga rápida
- **Formato**: Optimizar archivos de audio
- **Lazy Loading**: Para múltiples canciones

### Accesibilidad
- **Alt text**: Para imágenes de carátula
- **Keyboard navigation**: Controles accesibles
- **Screen readers**: Labels apropiados

## 🎵 Casos de Uso

- **Portfolio Musical**: Mostrar composiciones propias
- **Podcasts**: Reproductor para episodios
- **Demos**: Presentar muestras de audio
- **Educativo**: Lecciones de música o idiomas
- **Background Music**: Música ambiental para sitios web

## 🔐 Consideraciones Legales

- **Derechos de Autor**: Asegurar permisos para usar música
- **Licencias**: Respetar términos de uso
- **DMCA**: Compliance con regulaciones de contenido
- **Monetización**: Considerar regalías si aplica

## 🚀 Deployment

### Hosting Recomendado
- **GitHub Pages**: Para proyectos open source
- **Netlify**: Deploy automático y CDN
- **Vercel**: Excelente performance
- **Firebase Hosting**: Escalable y rápido

### Optimización para Producción
```bash
# Comprimir archivos de audio
ffmpeg -i input.mp3 -b:a 192k output.mp3

# Minificar CSS
npx csso styles.css --output styles.min.css
```

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas!

1. Fork del repositorio
2. Crear rama feature (`git checkout -b feature/nueva-caracteristica`)
3. Commit cambios (`git commit -m 'Agregar nueva característica'`)
4. Push a la rama (`git push origin feature/nueva-caracteristica`)
5. Crear Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver [LICENSE](LICENSE) para más detalles.

**Nota**: La música incluida puede tener sus propios derechos de autor.

---

**🎵 ¡Que la música nunca pare! 🎧**