# 📞 Call Center - Landing Page

Bienvenido al repositorio de **Call Center Landing Page**, una aplicación web moderna desarrollada con React y Vite, diseñada para presentar servicios especializados de eliminación de deudas de centrales de riesgo crediticio de forma profesional y atractiva.

![React](https://img.shields.io/badge/React-18.2.0-61dafb?logo=react&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-4.1.0-646cff?logo=vite&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.2.7-38b2ac?logo=tailwindcss&logoColor=white) ![React Router](https://img.shields.io/badge/React%20Router-6.8.2-f44250?logo=react-router) ![Animate.css](https://img.shields.io/badge/Animate.css-4.1.1-ff6b9d)

## 📑 Tabla de Contenidos

- [✨ Características Principales](#-características-principales)
- [🛠 Stack Tecnológico](#-stack-tecnológico)
- [🏗 Arquitectura del Proyecto](#-arquitectura-del-proyecto)
- [🚀 Instalación y Configuración](#-instalación-y-configuración)
- [📁 Estructura del Proyecto](#-estructura-del-proyecto)
- [🧩 Componentes Principales](#-componentes-principales)
- [🎨 Sistemas de Animaciones](#-sistemas-de-animaciones)
- [🔨 Desarrollo](#-desarrollo)
- [🚢 Despliegue](#-despliegue)
- [🤝 Contribución](#-contribución)
- [📞 Soporte](#-soporte)
- [📄 Licencia](#-licencia)

---

## ✨ Características Principales

### 📋 Presentación de Servicios

- 🏦 **Eliminación de deudas**: Información detallada sobre procesos de baja de centrales de riesgo crediticio
- 📊 **Análisis personalizado**: Soluciones adaptadas a cada cliente mediante asesoramiento especializado
- ⚖️ **Amparo legal**: Servicio respaldado por la Ley de Protección de Datos Personales (Ley Nº 25.326)
- 🇦🇷 **Cobertura nacional**: Atención en toda la República Argentina

### 💻 Experiencia de Usuario

- 📱 **Diseño responsivo**: Interfaz adaptable a dispositivos móviles, tablets y escritorio
- ✨ **Animaciones fluidas**: Efectos visuales con Animate.css y Intersection Observer para scroll progresivo
- ⚡ **Carga ultrarrápida**: Optimización de bundling con Vite y code-splitting automático
- 🎯 **UI moderna**: Componentes personalizados con TailwindCSS y paleta de colores profesional

### 🔗 Navegación y Estructura

- 🗺️ **Ruteo avanzado**: Sistema de navegación multi-página con React Router v6
- 📄 **Múltiples secciones**: Home, Quiénes somos, Seguridad/Legal, Contacto
- 🧭 **Navegación intuitiva**: Menú desplegable responsivo y footer dinámico

### 📬 Integración de Contacto

- 📧 **Formularios de contacto**: Captura de leads desde múltiples puntos de la aplicación
- 📞 **Información centralizada**: Enlaces a teléfono, WhatsApp y redes sociales
- 🔔 **Llamadas a acción**: CTAs estratégicos con diseño diferenciado

---

## 🛠 Stack Tecnológico

### Frontend Framework

| Tecnología                                  | Versión | Propósito                        |
| ------------------------------------------- | ------- | -------------------------------- |
| [React](https://react.dev)                  | 18.2.0  | Librería de UI con componentes   |
| [Vite](https://vitejs.dev)                  | 4.1.0   | Build tool y dev server moderno  |
| [React Router](https://reactrouter.com)     | 6.8.2   | Ruteo y navegación multi-página  |
| [TailwindCSS](https://tailwindcss.com)      | 3.2.7   | Framework de utilidades CSS      |

### Librerías de Animaciones e Iconografía

| Librería                                        | Versión | Propósito                    |
| ----------------------------------------------- | ------- | ---------------------------- |
| [Animate.css](https://animate.style/)           | 4.1.1   | Animaciones CSS predefinidas  |
| [React Icons](https://react-icons.github.io/)   | 4.7.1   | Librería de iconos SVG        |
| [Intersection Observer API](https://mdn.io)     | 0.12.2  | Detección de scroll progresivo |

### Herramientas de Desarrollo

| Herramienta                           | Versión | Propósito                    |
| ------------------------------------- | ------- | ---------------------------- |
| @vitejs/plugin-react                  | 3.1.0   | Soporte de JSX en Vite       |
| PostCSS                               | 8.4.21  | Transformación de CSS        |
| Autoprefixer                          | 10.4.13 | Prefijos CSS automáticos     |
| gh-pages                              | 5.0.0   | Despliegue en GitHub Pages   |

---

## 🏗 Arquitectura del Proyecto

```ascii
landing_page_call_center/
├── 📄 index.html                 # Punto de entrada HTML
├── 📁 public/                    # Assets públicos estáticos
├── 📁 src/
│   ├── 📄 main.jsx              # Renderización de React DOM
│   ├── 📄 App.jsx               # Componente raíz + ruteo
│   ├── 📄 index.css             # Estilos globales
│   ├── 📁 components/           # Componentes reutilizables
│   │   ├── nav_bar.jsx          # Barra de navegación
│   │   ├── footer.jsx           # Pie de página
│   │   ├── contact_us.jsx       # Botón de contacto rápido
│   │   ├── contact_form.jsx     # Formulario principal
│   │   ├── who_we_are.jsx       # Sección "Quiénes somos"
│   │   ├── why_choose_us.jsx    # Sección "Por qué elegirnos"
│   │   ├── bar.jsx              # Componente de barra auxiliar
│   │   └── function.jsx         # Hook useIntersection customizado
│   └── 📁 Pages/                # Páginas de la aplicación
│       ├── home.jsx             # Página de inicio
│       ├── who_we_us.jsx        # Página de presentación
│       ├── contact.jsx          # Página de contacto
│       └── legal_security.jsx   # Página de términos y seguridad
├── 📄 vite.config.js            # Configuración de Vite
├── 📄 tailwind.config.cjs       # Configuración de Tailwind
├── 📄 postcss.config.cjs        # Configuración de PostCSS
├── 📄 package.json              # Dependencias y scripts
└── 📄 README.md                 # Este archivo

```

**Flujo de Datos:**

```
Usuario accede a landing
        ↓
   Rutas de React Router
        ↓
   Renderiza Page + Componentes
        ↓
   Intersection Observer detecta scroll
        ↓
   Animaciones con Animate.css
        ↓
   Formularios capturan leads
        ↓
   Conversión
```

---

## 🚀 Instalación y Configuración

### Prerrequisitos del Sistema

- **Node.js**: >= 16.x (recomendado 18.x o superior)
- **npm**: >= 8.x (o yarn 3.x)
- **Git**: Para clonar el repositorio
- **Navegador moderno**: Chrome, Firefox, Safari o Edge (últimas 2 versiones)

### Pasos de Instalación

```bash
# 1. Clonar el repositorio
git clone https://github.com/tu-usuario/landing_page_call_center.git
cd landing_page_call_center

# 2. Instalar dependencias
npm install
# O si usas yarn:
yarn install

# 3. Iniciar servidor de desarrollo
npm run dev
# O:
yarn dev
```

### Verificar Instalación

```bash
# El servidor estará disponible en:
# http://localhost:5173/landing_page_call_center/
```

### Build para Producción

```bash
# Compilar para producción (salida en carpeta 'dist')
npm run build

# Previsualizar build localmente (antes de desplegar)
npm run preview
```

---

## 📁 Estructura del Proyecto

### Organización de Componentes

```text
src/components/
├── 📄 nav_bar.jsx           # Navegación principal con menú responsivo
├── 📄 footer.jsx            # Pie de página con enlaces y contacto
├── 📄 contact_us.jsx        # Botón/componente de contacto rápido
├── 📄 contact_form.jsx      # Formulario de captura de leads
├── 📄 who_we_are.jsx        # Sección de presentación de empresa
├── 📄 why_choose_us.jsx     # Sección de ventajas y diferenciadores
├── 📄 bar.jsx               # Componente de barra auxiliar
└── 📄 function.jsx          # Hook customizado para Intersection Observer
```

### Organización de Páginas

```text
src/Pages/
├── 📄 home.jsx              # Página de inicio (principal)
│   └── Contiene: Hero section, beneficios, formularios, CTA
├── 📄 who_we_us.jsx         # Página "Quiénes somos"
│   └── Historia, misión, valores de la empresa
├── 📄 contact.jsx           # Página de contacto
│   └── Formularios y múltiples canales de comunicación
└── 📄 legal_security.jsx    # Página de términos y seguridad
    └── Términos de servicio, privacidad, garantías legales
```

### Estilos

```text
src/
├── 📄 index.css             # Estilos globales y variables CSS
└── tailwind.config.cjs      # Configuración personalizada de Tailwind
```

---

## 🧩 Componentes Principales

### Componente App.jsx

Componente raíz que maneja el ruteo y estructura principal:

```jsx
// Estructura base
<Router>
  <NavBar />
  <Routes>
    <Route path="/landing_page_call_center/" element={<Home/>}/>
    <Route path="/landing_page_call_center/quienes-somos" element={<WhoWeUs/>}/>
    <Route path="/landing_page_call_center/seguridad-legal" element={<LegalSecurity/>}/>
    <Route path="/landing_page_call_center/contacto" element={<Contact/>}/>
  </Routes>
  <Footer />
</Router>
```

**Características:**
- Manejo de rutas con React Router v6
- NavBar y Footer persistentes en todas las páginas
- Base path configurado para GitHub Pages

### Página Home.jsx

Página principal con múltiples secciones:

**Secciones incluidas:**
1. **Hero Section**: Imagen de fondo, headline principal, CTAs
2. **Propuesta de valor**: Descripción de servicios y cobertura
3. **Proceso en 3 pasos**: Análisis → Propuesta → Solución (con iconos)
4. **Sección "Por qué elegirnos"**: Ventajas competitivas
5. **Formulario de contacto**: Captura de leads
6. **Sección "Quiénes somos"**: Presentación de empresa
7. **CTA secundaria**: Términos y condiciones

**Animaciones implementadas:**
- Fade-in al cargar página (animate.css)
- Fade-in en scroll con Intersection Observer
- Efectos hover en botones y elementos interactivos

### Hook useIntersection (function.jsx)

Hook customizado para detectar cuando elementos son visibles en pantalla:

```jsx
// Uso
const [elementRef, isIntersecting] = useIntersection({
  threshold: 0.5,  // Trigger cuando 50% del elemento es visible
});

return (
  <div ref={elementRef} className={isIntersecting ? "animate__fadeIn" : ""}>
    Contenido con animación
  </div>
);
```

**Beneficios:**
- Reutilizable en múltiples componentes
- Mejora rendimiento: solo anima cuando es necesario
- Proporciona experiencia visual fluida

### Componentes de Secciones

| Componente | Propósito | Ubicación |
| --- | --- | --- |
| `contact_us.jsx` | Botón de contacto flotante/rápido | Home, todas las páginas |
| `contact_form.jsx` | Formulario principal de captura | Home |
| `who_we_are.jsx` | Presentación de empresa | Home |
| `why_choose_us.jsx` | Ventajas diferenciadores | Home |
| `nav_bar.jsx` | Navegación principal | Header global |
| `footer.jsx` | Enlaces y contacto | Footer global |

---

## 🎨 Sistemas de Animaciones

### Animate.css

Librería de animaciones CSS predefinidas integrada en el proyecto:

```jsx
// Ejemplo: Fade in en elemento principal
<div className="animate__animated animate__fadeIn">
  Contenido con fade-in
</div>

// Otros efectos disponibles
animate__slideInUp       // Desliza hacia arriba
animate__zoomIn          // Zoom de entrada
animate__bounceIn        // Rebote de entrada
animate__fadeInLeft      // Fade desde izquierda
```

**Ubicaciones principales:**
- Hero section en home.jsx
- Secciones al cargar página
- Componentes con Intersection Observer

### Intersection Observer API

Detección de scroll progresivo para activar animaciones bajo demanda:

```jsx
// Patrón implementado
const [elementRef, isIntersecting] = useIntersection({ threshold: 0.5 });

// Aplica animación solo cuando elemento es visible
<div ref={elementRef} 
     className={`opacity-0 ${isIntersecting ? "animate__animated animate__fadeIn" : ""}`}>
  Se anima al entrar en pantalla
</div>
```

**Ventajas:**
- ⚡ Mejor rendimiento (solo anima elementos visibles)
- 🎯 Experiencia visual progresiva
- 📊 Mejora métricas de Core Web Vitals

### Efectos Hover

```css
/* Botones principales */
.btn-primary {
  @apply duration-500 hover:bg-white hover:text-red-800;
}

/* Enlaces y elementos interactivos */
a {
  @apply transition-all duration-300;
}
```

---

## 🔨 Desarrollo

### Scripts Disponibles

| Comando | Acción | Uso | Notas |
| --- | --- | --- | --- |
| `npm run dev` | Inicia servidor de desarrollo | Desarrollo local | Hot reload automático |
| `npm run build` | Crea build de producción | Compilación final | Salida en carpeta `dist/` |
| `npm run preview` | Previsualiza build producción | Testing pre-deploy | Simula servidor estático |
| `npm run deploy` | Despliega a GitHub Pages | Despliegue automático | Requiere configuración |

### Estructura de Commits

```bash
# Formato recomendado para commits
git commit -m "tipo(ámbito): descripción breve

Descripción detallada de cambios realizados si es necesario.

- Cambio específico 1
- Cambio específico 2
- Cierra #123"

# Ejemplos válidos
git commit -m "feat(home): agregar sección de testimonios"
git commit -m "fix(contact): validación de email en formulario"
git commit -m "style(nav): actualizar paleta de colores primarios"
git commit -m "perf(animations): optimizar Intersection Observer"
git commit -m "docs(readme): actualizar documentación de setup"
```

### Convenciones de Código React

```jsx
// ✅ Componentes funcionales con hooks
export default function NombreComponente({ prop1, prop2 }) {
  const [state, setState] = useState(null);
  
  useEffect(() => {
    // Efectos secundarios
  }, [dependencies]);

  return (
    <div className="flex gap-4">
      {/* JSX */}
    </div>
  );
}

// Props con destructuring
// Componentes modulares y reutilizables
// Nombres descriptivos en español/inglés consistentes
// Hooks customizados para lógica compartida
```

### Herramientas de Desarrollo Recomendadas

- **VS Code**: Editor principal
- **ES7+ React/Redux/React-Native snippets**: Para completaciones rápidas
- **Tailwind CSS IntelliSense**: Autocompletado de clases
- **Vite Plugin**: Soporte de Vite en VS Code
- **React Developer Tools**: Debugging de componentes

### Flujo de Trabajo de Desarrollo

```bash
# 1. Crear rama de feature
git checkout -b feature/nueva-funcionalidad

# 2. Hacer cambios y verificar localmente
npm run dev
# Probar en http://localhost:5173/landing_page_call_center/

# 3. Compilar para producción (verificar build)
npm run build
npm run preview

# 4. Commit y push
git add .
git commit -m "feat(componente): descripción"
git push origin feature/nueva-funcionalidad

# 5. Crear Pull Request en GitHub
```

---

## 🚢 Despliegue

### Despliegue en GitHub Pages (Recomendado)

GitHub Pages está preconfigurado en el proyecto. Solo necesitas:

#### Configuración Inicial

1. **Crear repositorio en GitHub**
   - Nombre: `landing_page_call_center`
   - Visibilidad: Public (necesario para Pages)

2. **Configurar en package.json**
   ```json
   {
     "repository": {
       "type": "git",
       "url": "https://github.com/tu-usuario/landing_page_call_center.git"
     }
   }
   ```

3. **Activar GitHub Pages**
   - Ir a Settings → Pages
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`

#### Desplegar

```bash
# Compilar y desplegar automáticamente
npm run deploy
```

**URL resultante:**
```
https://tu-usuario.github.io/landing_page_call_center/
```

> ℹ️ El base path `/landing_page_call_center/` está configurado en `vite.config.js`

### Alternativa: Vercel (Despliegue más moderno)

```bash
# 1. Instalar Vercel CLI
npm i -g vercel

# 2. Desplegar
vercel --prod
```

**Ventajas sobre GitHub Pages:**
- ⚡ Mejor rendimiento global (CDN)
- 🔄 Deploy automático en push a main
- 📊 Analytics y logging integrados
- 🔧 Variables de entorno nativas
- 🚀 Serverless functions (si es necesario después)

### Alternativa: Netlify

```bash
# 1. Configurar en netlify.toml
[build]
  command = "npm run build"
  publish = "dist"

# 2. Conectar repo a Netlify
# Ir a https://netlify.com → Connect new site from Git
```

### Variables de Entorno para Producción

Crea archivo `.env.production`:

```env
# Si necesitas endpoints de contacto
VITE_CONTACT_EMAIL=contacto@empresa.com
VITE_WHATSAPP_NUMBER=+54911234567
VITE_PHONE_NUMBER=+541145678901

# Analytics (opcional)
VITE_GA_ID=G-XXXXXXXXXX
```

Uso en componentes:

```jsx
const contactEmail = import.meta.env.VITE_CONTACT_EMAIL;
```

### Checklist Pre-Deploy

- [ ] `npm run build` genera carpeta `dist/` sin errores
- [ ] `npm run preview` funciona correctamente
- [ ] Todas las rutas funcionan (router setup)
- [ ] Formularios envían datos correctamente
- [ ] Imágenes y assets cargan correctamente
- [ ] Animaciones funcionan en navegador de producción
- [ ] Testing en móvil/tablet/desktop
- [ ] Verificar Google Lighthouse (Performance, SEO)
- [ ] HTTPS habilitado en dominio
- [ ] Meta tags y OG tags correctos

---

## 🤝 Contribución

### Cómo Contribuir

1. **Fork del repositorio**
   ```bash
   # En GitHub: Click en "Fork"
   git clone https://github.com/tu-usuario/landing_page_call_center.git
   cd landing_page_call_center
   ```

2. **Crear rama de feature**
   ```bash
   git checkout -b feature/mi-nueva-funcionalidad
   ```

3. **Realizar cambios**
   - Mantener convenciones de código
   - Agregar comentarios en lógica compleja
   - Probar en múltiples dispositivos

4. **Commit y Push**
   ```bash
   git add .
   git commit -m "feat(scope): descripción clara"
   git push origin feature/mi-nueva-funcionalidad
   ```

5. **Crear Pull Request**
   - Descripción clara del cambio
   - Screenshots si es UI
   - Referencia a issues si aplica

### Estándares de Código

#### Componentes React
```jsx
// ✅ Correcto
export default function MiComponente({ titulo, variant = "primary" }) {
  return (
    <div className={`component ${variant}`}>
      <h2>{titulo}</h2>
    </div>
  );
}

// ❌ Evitar
function MiComponente(props) {
  return <h2>{props.titulo}</h2>;
}
```

#### Clases de Tailwind
```jsx
// ✅ Correcto: clases organizadas lógicamente
<button className="bg-red-800 hover:bg-white text-white hover:text-red-800 px-4 py-2 duration-500 tracking-wider">
  CTA
</button>

// ❌ Evitar: clases desorganizadas
<button style={{background: 'red', color: 'white'}}>
  CTA
</button>
```

#### Nombres de Variables
```jsx
// ✅ Correcto: descriptivos
const [isVisible, setIsVisible] = useState(false);
const userEmail = data.user.email;

// ❌ Evitar: ambiguos
const [x, setX] = useState(false);
const email1 = data.u.e;
```

### Tipos de Contribución Bienvenidas

- 🐛 **Bug fixes**: Arreglar problemas identificados
- ✨ **Nuevas características**: Funcionalidades que mejoren UX
- 📚 **Documentación**: Mejoras a README o comentarios
- 🎨 **Design/UI**: Mejoras visuales y de usabilidad
- ⚡ **Performance**: Optimizaciones de velocidad
- ♿ **Accesibilidad**: ARIA labels, keyboard navigation, etc.

### Reportar Bugs

Usar plantilla al crear issue:

```markdown
## Descripción del Bug
Descripción clara del problema.

## Pasos para Reproducir
1. Ir a...
2. Hacer clic en...
3. Ver que...

## Comportamiento Esperado
Qué debería ocurrir.

## Comportamiento Actual
Qué ocurre realmente.

## Ambiente
- OS: [Windows/Mac/Linux]
- Navegador: [Chrome/Firefox/Safari]
- Versión: [número]

## Screenshots
[Si aplica]
```

---

## 📞 Soporte

### Recursos de Ayuda

#### Documentación Técnica
- **React**: [react.dev/learn](https://react.dev/learn)
- **Vite**: [vitejs.dev/guide](https://vitejs.dev/guide/)
- **Tailwind**: [tailwindcss.com/docs](https://tailwindcss.com/docs)
- **React Router**: [reactrouter.com](https://reactrouter.com)
- **Animate.css**: [animate.style](https://animate.style)

#### Comunidades
- **Stack Overflow**: Tag `reactjs` o `vite`
- **GitHub Discussions**: Preguntas en el repositorio
- **Discord React**: [Comunidad React](https://discord.gg/react)

### Contacto Directo

Para preguntas sobre el proyecto:

- 📧 **Email**: contacto@empresa.com
- 📱 **WhatsApp**: [+54 9 11 1234-5678](https://wa.me/5491112345678)
- 🐙 **GitHub Issues**: [Reportar problema](https://github.com/tu-usuario/landing_page_call_center/issues)

### FAQ

**P: ¿Cómo cambio el base path de la aplicación?**
R: En `vite.config.js`, modifica el valor de `base`. Ejemplo:
```js
export default defineConfig({
  base: "/nuevo-path/"
})
```

**P: ¿Cómo agrego nuevas rutas?**
R: En `App.jsx`, agrega nuevas rutas dentro de `<Routes>`:
```jsx
<Route path="/nueva-ruta" element={<MiComponente/>}/>
```

**P: ¿Cómo cambio los colores principales?**
R: En `tailwind.config.cjs`, expande el objeto `theme`:
```js
theme: {
  colors: {
    primary: '#...',
    secondary: '#...'
  }
}
```

**P: ¿Cómo integro un formulario de contacto con email?**
R: Usa servicios como:
- [Formspree](https://formspree.io)
- [EmailJS](https://www.emailjs.com)
- [Netlify Forms](https://www.netlify.com/products/forms)

---

## 📄 Licencia

Este proyecto se distribuye bajo la **Licencia MIT**.

```text
MIT License

Copyright (c) 2025 Call Center Landing Page

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Permisos ✅

- Uso comercial
- Modificación
- Distribución
- Uso privado

### Condiciones ❗

- Incluir aviso de copyright
- Incluir copia de licencia

---

<div align="center">

## 🚀 ¡Comienza Ahora!

```bash
npm install && npm run dev
```

Visita [http://localhost:5173/landing_page_call_center/](http://localhost:5173/landing_page_call_center/)

---

**¿Te resultó útil este proyecto?** ⭐ ¡Dale una estrella en GitHub!

**¿Tienes una pregunta?** 💬 [Abre un issue](https://github.com/tu-usuario/landing_page_call_center/issues/new)

**¿Quieres contribuir?** 🤝 [Lee nuestra guía de contribución](#-contribución)

---

> _Documentación elaborada con atención al detalle | React × Vite × TailwindCSS_  
> _Última actualización: Noviembre 2025 | Versión: 1.0.0_

</div>
