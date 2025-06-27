# Lista Animada - Personajes Populares de Los Simpson

Un proyecto web que presenta una lista animada y elegante de los personajes más populares de Los Simpson con efectos visuales modernos.

## 📋 Descripción

Este proyecto muestra un ranking de los personajes más queridos de Los Simpson en formato de lista interactiva. Cada elemento incluye la imagen del personaje, su posición en el ranking, nombre y una breve descripción, todo con animaciones suaves y un diseño moderno.

## ✨ Características

- **Lista Ranking**: Numeración clara del 1 al 5
- **Diseño Moderno**: Interfaz limpia y atractiva
- **Animaciones CSS**: Efectos de hover y transiciones suaves
- **Responsive Design**: Se adapta a diferentes dispositivos
- **Imágenes Optimizadas**: Visualización clara de cada personaje
- **Tipografía Elegante**: Jerarquía visual clara

## 🎭 Personajes Incluidos

1. **Moe Szyslak** - Cantinero del bar de Moe
2. **Marge Simpson** - Esposa de Homero y madre de familia
3. **Homero Simpson** - Padre de familia y protagonista
4. **Lisa Simpson** - Hija intelectual de la familia
5. **Bart Simpson** - Hijo travieso de la familia

## 🛠️ Tecnologías Utilizadas

- HTML5 Semántico
- CSS3 (Flexbox, Animaciones, Transiciones)
- Diseño Responsive
- Favicon personalizado

## 📁 Estructura del Proyecto

```
lista-simpson/
│
├── index.html              # Archivo principal HTML
├── css/
│   └── style.css          # Estilos CSS principales
├── img/
│   ├── ejercicio.png      # Favicon del proyecto
│   ├── s1.jpg             # Imagen de Moe
│   ├── s3.png             # Imagen de Marge
│   ├── s4.png             # Imagen de Homero
│   ├── s5.jpg             # Imagen de Lisa
│   └── s6.png             # Imagen de Bart
└── README.md              # Este archivo
```

## 🚀 Instalación y Uso

### Opción 1: Uso Directo
1. **Descargar** todos los archivos del proyecto
2. **Asegurar** que las imágenes estén en la carpeta `img/`
3. **Abrir** `index.html` en tu navegador web

### Opción 2: Servidor Local
```bash
# Con Python
python -m http.server 8000

# Con Node.js
npx live-server

# Con PHP
php -S localhost:8000
```

## 🎨 Personalización

### Cambiar Personajes
Para modificar o agregar personajes:

```html
<div class="list">
    <div class="imgBx">
        <img src="img/nuevo-personaje.jpg">
    </div>
    <div class="content">
        <h2 class="rank"><small>#</small>6</h2>
        <h4>Nombre del Personaje</h4>
        <p>Descripción breve</p>
    </div>
</div>
```

### Modificar Estilos
El archivo CSS permite personalizar:
- Colores de fondo y texto
- Efectos de hover
- Animaciones de entrada
- Tamaños y espaciados
- Efectos de sombra

### Cambiar el Ranking
Simplemente modifica los números en:
```html
<h2 class="rank"><small>#</small>NUMERO</h2>
```

## 📱 Características Técnicas

- **Semantic HTML**: Uso correcto de elementos semánticos
- **CSS Grid/Flexbox**: Layout moderno y flexible
- **Image Optimization**: Soporte para múltiples formatos (JPG, PNG)
- **Hover Effects**: Interactividad visual
- **Typography**: Jerarquía clara de textos
- **Box Model**: Uso eficiente de padding y margins

## 🎯 Posibles Mejoras

- [ ] Agregar más personajes
- [ ] Implementar animaciones de entrada escalonadas
- [ ] Añadir filtros por categoría
- [ ] Incluir información adicional en modal
- [ ] Agregar sistema de votación
- [ ] Implementar modo oscuro/claro

## 📱 Compatibilidad

- ✅ Chrome 70+
- ✅ Firefox 65+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ iOS Safari
- ✅ Android Chrome

## 🎨 Paleta de Colores Sugerida

Para mantener la temática de Los Simpson:
- **Amarillo Simpson**: `#FFD700`
- **Azul Marge**: `#87CEEB`
- **Rojo Bart**: `#FF6B6B`
- **Verde Lisa**: `#98FB98`

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Para contribuir:

1. Fork del repositorio
2. Crear rama feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit de cambios (`git commit -m 'Agregar nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Crear Pull Request

## 📝 Notas de Desarrollo

- Las imágenes deben mantener proporciones consistentes
- Usar formatos web optimizados (WebP cuando sea posible)
- Considerar lazy loading para mejor rendimiento
- Mantener accesibilidad con alt text apropiado

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver archivo [LICENSE](LICENSE) para más detalles.

## 🏆 Créditos

- **Personajes**: © The Simpsons, propiedad de Fox Broadcasting Company
- **Desarrollo**: Proyecto educativo de desarrollo web
- **Inspiración**: Serie animada Los Simpson

---

**¡Disfruta explorando el mundo de Springfield! 🍩**