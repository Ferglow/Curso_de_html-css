# Marvel Character Cards

Un proyecto web que muestra tarjetas interactivas de personajes famosos de Marvel con efectos de hover y enlaces a redes sociales.

## 📋 Descripción

Este proyecto presenta una galería de tarjetas elegantes que muestran personajes icónicos de Marvel (Loki, Thor e Iron Man). Cada tarjeta incluye una imagen del personaje, su nombre y enlaces a redes sociales con animaciones suaves.

## ✨ Características

- **Diseño Responsivo**: Se adapta a diferentes tamaños de pantalla
- **Efectos de Hover**: Animaciones fluidas al pasar el cursor sobre las tarjetas
- **Iconos de Redes Sociales**: Enlaces a Facebook, Twitter e Instagram
- **Gradientes Modernos**: Fondo con gradiente atractivo
- **Animaciones CSS**: Transiciones suaves y efectos visuales

## 🛠️ Tecnologías Utilizadas

- HTML5
- CSS3 (Flexbox, Animaciones, Gradientes)
- JavaScript (Ionicons)
- Ionicons 5.5.2

## 📁 Estructura del Proyecto

```
proyecto-marvel/
│
├── index.html          # Archivo principal HTML
├── css/
│   └── style.css       # Estilos CSS (si se usa archivo externo)
├── img/
│   ├── im1.jpg         # Imagen de Loki
│   ├── im2.jpg         # Imagen de Thor
│   └── im3.jpg         # Imagen de Iron Man
└── README.md           # Este archivo
```

## 🚀 Instalación y Uso

1. **Clonar o descargar** el repositorio
2. **Abrir** el archivo `index.html` en tu navegador web
3. **¡Listo!** Ya puedes ver las tarjetas interactivas

### Opción con servidor local:
```bash
# Si tienes Python instalado
python -m http.server 8000

# Si tienes Node.js y live-server
npx live-server
```

## 🎨 Personalización

### Cambiar Personajes
Para agregar o cambiar personajes:

1. Agrega las imágenes en la carpeta `img/`
2. Duplica una sección `.card` en el HTML
3. Actualiza el `src` de la imagen y el nombre del personaje

### Modificar Colores
Los colores principales se pueden cambiar en el CSS:

```css
/* Gradiente de fondo */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Color de las tarjetas */
background: rgba(255, 255, 255, 0.1);
```

### Agregar Más Redes Sociales
Para agregar más iconos de redes sociales:

1. Consulta la documentación de [Ionicons](https://ionic.io/ionicons)
2. Agrega un nuevo `<li>` con el icono deseado
3. Ajusta la variable CSS `--i` para la animación

## 📱 Compatibilidad

- ✅ Chrome
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Dispositivos móviles

## 🎯 Características Técnicas

- **CSS Variables**: Uso de custom properties para animaciones
- **Flexbox**: Layout flexible y responsivo
- **Transform**: Efectos 3D y rotaciones
- **Backdrop Filter**: Efectos de desenfoque moderno
- **Box Shadow**: Sombras elegantes

## 📝 Notas de Desarrollo

- Las imágenes deben tener una resolución mínima de 300x300px para mejor calidad
- Los iconos se cargan desde CDN de Ionicons
- El proyecto usa efectos de glassmorphism para un diseño moderno

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si quieres mejorar el proyecto:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 👨‍💻 Autor

Creado con ❤️ para mostrar el poder de CSS y HTML moderno.

---

**¿Te gustó el proyecto? ¡Dale una ⭐ en GitHub!**