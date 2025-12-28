# PROYECTO SHOWCASE CSS

**Alumno:** Pedro
**Asignatura:** Diseño de Interfaces Web (DIW)
**Entrega:** Práctica Evaluable 1/2

---

## 📋 ÍNDICE DE RÚBRICA (Guía de Corrección)

### 1. ESTRUCTURA HTML & SEMÁNTICA

- **HTML5 Estratégico**:
  - `<header>` -> `.header-nav` (`index.html`)
  - `<main>` -> (`index.html`)
  - `<section>` -> `.hero-section`, `.projects-section`, `.about-section`, `.skills-visual-section` (`index.html`)
  - `<footer>` -> `.main-footer` (`index.html`)

### 2. CSS MODERNO: PSEUDOCLASES (4+ Distintas)

- **`:hover`** (Interacción):
  - `.nav-link` -> Subrayado animado (`css/header.css`)
  - `.project-card` -> Escala y elevación (`css/projects.css`)
- **`:active`** (Efecto Clic):
  - `.hero-btn`, `.cta-nav` -> Reducción de escala al pulsar (`css/base.css`)
- **`:focus`** (Accesibilidad):
  - `a`, `button` -> Outline discontinuo al navegar con teclado (`css/base.css`)
- **`:nth-child()`** (Posicionamiento):
  - `.project-card` -> Grid caótico, rotación individual de tarjetas (`css/projects.css`)
- **`:last-child`** (Selección):
  - `.line` -> Cursor parpadeante en última línea de código (`css/hero.css`)

### 3. ANIMACIONES CSS

- **`@keyframes`**:
  - `blink` -> Cursor de terminal parpadeante (`css/hero.css`)
  - `mover-cinta` -> Carrusel infinito de texto (`css/hero.css`)
  - `spin-slow` -> Rotación constante de decoraciones de fondo (`css/stack.css`)
- **`transition`**:
  - `.project-card` -> Suavizado de hover (`css/projects.css`)
  - `.inspector-panel` -> Movimiento fluido (`css/about.css`)

### 4. IMÁGENES Y EFECTOS VISUALES

- **`mix-blend-mode` (OBLIGATORIO)**:
  - `.overlay` -> Efecto de mezcla "multiply" en imágenes de tarjetas (`css/projects.css`)
- **`background-image`**:
  - `.hero-visual` -> Gradiente radial (`css/hero.css`)
  - `.skills-visual-section` -> Patrón de cuadrícula (`css/stack.css`)
- **`background-size`**:
  - `.hero-visual` (`css/hero.css`)
- **`background-position`**:
  - `.skills-visual-section` (`css/stack.css`)
- **`opacity`**:
  - `blink` -> Animación de opacidad en cursor (`css/hero.css`)

### 5. TIPOGRAFÍAS E ICONOS

- **Google Fonts**:
  - `Syne` (Títulos) y `Space Grotesk` (Cuerpo) importadas en `<head>` (`index.html`)
- **Font Awesome (OBLIGATORIO)**:
  - Iconos `<i>` en botones (`.hero-btn`) y tarjetas de stack (`.stack-icon`) (`index.html`)

### 6. DISEÑO RESPONSIVE

- **Media Queries**:
  - `@media (max-width: 1000px)` -> Aplicado en todos los módulos CSS para adaptación móvil.
- **Unidades Relativas**:
  - `clamp()` -> Títulos fluidos (`.display-title` en `css/hero.css`)
  - `vh / svh` -> Altura de secciones (`css/base.css`)
  - `%` -> Anchuras fluidas (`css/about.css`)
