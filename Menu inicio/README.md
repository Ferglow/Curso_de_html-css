# Portafolio Personal - Fernando Andres (Ferglow)

Sitio web personal y portafolio profesional de Fernando Andres, desarrollador conocido como "Ferglow".

## 📋 Descripción

Este es el sitio web personal y portafolio profesional de Fernando Andres. El proyecto está diseñado para mostrar habilidades, proyectos y experiencia profesional de manera elegante y moderna, con una navegación intuitiva y diseño responsivo.

## 🌟 Características del Portafolio

- **Header Profesional**: Logo personalizado con enlace a GitHub
- **Navegación Clara**: Secciones organizadas (Inicio, Código, Contacto)
- **Diseño Responsivo**: Adaptable a todos los dispositivos
- **Identidad Visual**: Logo y favicon personalizados
- **Enlaces Externos**: Conexión directa al perfil de GitHub

## 🏗️ Estructura Actual

### Header
- **Logo**: Imagen personalizada con el nombre "Ferglow"
- **Navegación**: Enlaces a las principales secciones
- **GitHub Link**: Acceso directo al perfil profesional

### Secciones Planificadas
1. **Inicio**: Presentación personal y resumen profesional
2. **Código**: Portafolio de proyectos y habilidades técnicas
3. **Contacto**: Información de contacto y formulario

## 🛠️ Tecnologías Utilizadas

- HTML5 Semántico
- CSS3 (archivo `styles.css`)
- Diseño Responsive
- Favicon personalizado
- Enlaces externos (GitHub)

## 📁 Estructura del Proyecto

```
portafolio-ferglow/
│
├── index.html                    # Página principal
├── styles.css                    # Estilos CSS principales
├── img/
│   └── discussion_2572753.png   # Logo y favicon
└── README.md                     # Este archivo
```

## 🚀 Instalación y Uso

### Desarrollo Local
1. **Clonar** o descargar el repositorio
2. **Abrir** `index.html` en tu navegador
3. **Editar** el contenido según necesidades

### Servidor de Desarrollo
```bash
# Con Python
python -m http.server 8000

# Con Node.js (live-server)
npx live-server

# Con PHP
php -S localhost:8000
```

### Hosting Recomendado
- **GitHub Pages**: Gratuito y fácil de configurar
- **Netlify**: Deploy automático desde Git
- **Vercel**: Excelente para proyectos frontend

## 🎨 Personalización

### Cambiar Información Personal
```html
<title>Tu Nombre</title>
<h2 class="nombreLogo">TuAlias</h2>
```

### Modificar Enlaces de Navegación
```html
<nav>
    <a href="#inicio" class="nav-link">Inicio</a>
    <a href="#proyectos" class="nav-link">Proyectos</a>
    <a href="#sobre-mi" class="nav-link">Sobre Mí</a>
    <a href="#contacto" class="nav-link">Contacto</a>
</nav>
```

### Actualizar Enlaces Sociales
```html
<a href="https://github.com/tu-usuario" target="_blank" class="logo">
<a href="https://linkedin.com/in/tu-perfil" target="_blank">
<a href="https://twitter.com/tu-usuario" target="_blank">
```

## 📝 Secciones Sugeridas para Completar

### 1. Sección Hero/Inicio
```html
<section id="inicio" class="hero">
    <div class="hero-content">
        <h1>Hola, soy Fernando Andres</h1>
        <p>Desarrollador Full Stack especializado en...</p>
        <button class="cta-button">Ver mi trabajo</button>
    </div>
</section>
```

### 2. Sección Sobre Mí
```html
<section id="sobre-mi" class="about">
    <h2>Sobre Mí</h2>
    <p>Descripción profesional y personal...</p>
    <div class="skills">
        <!-- Lista de habilidades -->
    </div>
</section>
```

### 3. Sección Proyectos
```html
<section id="codigo" class="projects">
    <h2>Mis Proyectos</h2>
    <div class="project-grid">
        <!-- Tarjetas de proyectos -->
    </div>
</section>
```

### 4. Sección Contacto
```html
<section id="contacto" class="contact">
    <h2>Contacto</h2>
    <form class="contact-form">
        <!-- Formulario de contacto -->
    </form>
</section>
```

## 🎯 Tecnologías a Mostrar

### Frontend
- HTML5, CSS3, JavaScript
- React, Vue.js, Angular
- Sass/SCSS, Tailwind CSS
- Responsive Design

### Backend
- Node.js, Express
- Python, Django/Flask
- PHP, Laravel
- Bases de datos (MySQL, MongoDB)

### Herramientas
- Git/GitHub
- VS Code
- Figma/Adobe XD
- Docker

## 📱 Responsividad

### Breakpoints Recomendados
```css
/* Mobile First */
@media (min-width: 768px) { /* Tablet */ }
@media (min-width: 1024px) { /* Desktop */ }
@media (min-width: 1200px) { /* Large Desktop */ }
```

## 🔧 Funcionalidades Adicionales

### Animaciones CSS
- Transiciones suaves en hover
- Animaciones de entrada (AOS)
- Loading animations

### JavaScript Interactivo
- Smooth scrolling
- Formulario de contacto funcional
- Modo oscuro/claro
- Carousel de proyectos

### SEO y Performance
- Meta tags optimizados
- Open Graph para redes sociales
- Lazy loading de imágenes
- Minificación de CSS/JS

## 📊 Analytics y Tracking

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>

<!-- Meta tags para SEO -->
<meta name="description" content="Portafolio de Fernando Andres - Desarrollador Full Stack">
<meta name="keywords" content="desarrollador, programador, web, frontend, backend">
```

## 🚀 Deployment

### GitHub Pages
1. Push código a repositorio GitHub
2. Ir a Settings > Pages
3. Seleccionar source branch
4. Acceder via: `https://username.github.io/repo-name`

### Netlify
```bash
# Deploy manual
npm run build
drag & drop dist folder

# Deploy automático
conectar repositorio GitHub
```

## 🤝 Contribuciones

Si quieres colaborar con mejoras:

1. Fork del repositorio
2. Crear rama feature (`git checkout -b feature/mejora`)
3. Commit cambios (`git commit -m 'Agregar mejora'`)
4. Push a la rama (`git push origin feature/mejora`)
5. Crear Pull Request

## 📄 Checklist de Completación

- [ ] Completar sección Hero/Inicio
- [ ] Agregar sección Sobre Mí
- [ ] Crear galería de proyectos
- [ ] Implementar formulario de contacto
- [ ] Agregar animaciones CSS
- [ ] Optimizar para SEO
- [ ] Hacer responsive completo
- [ ] Configurar analytics
- [ ] Deploy a producción
- [ ] Configurar dominio personalizado

## 📞 Contacto

- **GitHub**: [Ferglow](https://github.com/Ferglow)
- **Email**: [Agregar email]
- **LinkedIn**: [Agregar perfil]
- **Portfolio**: [URL cuando esté desplegado]

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver [LICENSE](LICENSE) para más detalles.

---

**🚀 ¡Construyendo el futuro, un commit a la vez!**