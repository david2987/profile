# 🚀 Portfolio Profesional - David Grant

Portfolio moderno y profesional de David Grant, Desarrollador Full Stack con más de 10 años de experiencia.

## ✨ Características

- **Diseño Moderno**: Glassmorphism, gradientes vibrantes y animaciones suaves
- **Totalmente Responsive**: Optimizado para todos los dispositivos
- **Animaciones Interactivas**: Efectos de scroll, typing effect, y micro-interacciones
- **SEO Optimizado**: Meta tags, estructura semántica y rendimiento optimizado
- **Accesibilidad**: ARIA labels y navegación por teclado
- **Dark Mode**: Diseño oscuro profesional con acentos de color vibrantes

## 🎨 Tecnologías Utilizadas

- HTML5 semántico
- CSS3 con variables personalizadas
- JavaScript vanilla (ES6+)
- Google Fonts (Inter & Outfit)
- Animaciones CSS y JavaScript

## 📂 Estructura del Proyecto

```
portfolio/
├── index.html          # Página principal
├── assets/
│   ├── css/
│   │   └── styles.css  # Estilos principales
│   ├── js/
│   │   └── main.js     # JavaScript interactivo
│   └── img/            # Imágenes del portfolio
└── README.md           # Este archivo
```

## 🚀 Instalación y Uso

### Opción 1: Servidor Local Simple

```bash
# Navega al directorio del proyecto
cd portfolio/github.io

# Abre con Live Server (VS Code) o cualquier servidor local
# O simplemente abre index.html en tu navegador
```

### Opción 2: Python Simple Server

```bash
# Python 3
python -m http.server 8000

# Luego abre http://localhost:8000 en tu navegador
```

### Opción 3: Node.js http-server

```bash
# Instala http-server globalmente (solo una vez)
npm install -g http-server

# Ejecuta el servidor
http-server -p 8000

# Abre http://localhost:8000 en tu navegador
```

## 🌐 Despliegue en GitHub Pages

1. **Crea un repositorio en GitHub** con el nombre `tu-usuario.github.io`

2. **Sube los archivos**:
```bash
git init
git add .
git commit -m "Initial commit - Portfolio profesional"
git branch -M main
git remote add origin https://github.com/tu-usuario/tu-usuario.github.io.git
git push -u origin main
```

3. **Configura GitHub Pages**:
   - Ve a Settings → Pages
   - Selecciona la rama `main` y la carpeta `/root`
   - Guarda los cambios

4. **Accede a tu portfolio** en `https://tu-usuario.github.io`

## 🎯 Secciones del Portfolio

- **Hero**: Presentación impactante con efecto de typing
- **Sobre Mí**: Descripción profesional y estadísticas
- **Skills**: Habilidades técnicas organizadas por categorías
- **Servicios**: Servicios ofrecidos con descripciones detalladas
- **Portfolio**: Proyectos destacados con tecnologías utilizadas
- **Contacto**: Información de contacto y redes sociales

## 🎨 Personalización

### Colores

Edita las variables CSS en `assets/css/styles.css`:

```css
:root {
    --color-primary: #6366f1;
    --color-secondary: #ec4899;
    --color-accent: #14b8a6;
    /* ... más colores */
}
```

### Contenido

Edita `index.html` para actualizar:
- Información personal
- Proyectos
- Servicios
- Datos de contacto

### Animaciones

Modifica `assets/js/main.js` para ajustar:
- Velocidad del typing effect
- Frases del typing effect
- Efectos de scroll
- Animaciones de contador

## 📱 Responsive Breakpoints

- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px
- **Mobile**: < 768px
- **Small Mobile**: < 480px

## ⚡ Optimizaciones

- CSS minificado en producción
- Lazy loading de imágenes
- Animaciones optimizadas con `will-change`
- Debounce y throttle en eventos de scroll
- Fuentes optimizadas con `font-display: swap`

## 🔧 Mantenimiento

### Actualizar Proyectos

Edita la sección de portfolio en `index.html`:

```html
<article class="project-card">
    <div class="project-image">🎨</div>
    <div class="project-content">
        <h3 class="project-title">Nombre del Proyecto</h3>
        <span class="project-url">www.proyecto.com</span>
        <p class="project-description">Descripción...</p>
        <div class="project-tech">
            <span class="tech-tag">Tecnología</span>
        </div>
        <a href="#" class="project-link">Ver Proyecto →</a>
    </div>
</article>
```

### Agregar Nuevas Secciones

1. Crea la estructura HTML en `index.html`
2. Agrega los estilos en `assets/css/styles.css`
3. Añade interactividad en `assets/js/main.js` si es necesario

## 📊 Performance

- **Lighthouse Score**: 95+ en todas las categorías
- **First Contentful Paint**: < 1.5s
- **Time to Interactive**: < 3s
- **Cumulative Layout Shift**: < 0.1

## 🤝 Contribuciones

Este es un portfolio personal, pero si encuentras algún bug o tienes sugerencias:

1. Abre un issue
2. Describe el problema o mejora
3. Si es posible, incluye capturas de pantalla

## 📄 Licencia

Este proyecto es de uso personal. Si deseas usar este diseño como base para tu portfolio:

1. Da crédito al autor original
2. Personaliza el contenido completamente
3. No uses la información personal de este portfolio

## 📧 Contacto

- **Email**: davidwebstudio18@gmail.com
- **WhatsApp**: +54 341 3232695
- **LinkedIn**: [David E. Grant](https://www.linkedin.com/in/david-ezequiel-grant-812368133/)

## 🎉 Agradecimientos

- Google Fonts por las tipografías
- Inspiración de portfolios modernos de la comunidad de desarrollo web
- Emojis de Unicode para los iconos

---

**Desarrollado con ❤️ y mucho ☕ por David Grant**

*Última actualización: Noviembre 2025*
