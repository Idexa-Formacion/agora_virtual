# DESIGN SYSTEM - COORDINADORA SAGRADA FAMÍLIA
## Guía completa de especificaciones para Figma

---

## 🎨 COLOR TOKENS

### Colores Primarios
```
--primary: #984c4c
--primary-light: #b36060
--primary-dark: #7a3d3d
```

### Colores Secundarios
```
--secondary: #D4A574
--accent: #E8956B
```

### Colores Neutros
```
--dark: #1A1A1A
--light: #FAFAF8
--gray: #6B7280
--gray-light: #F3F4F6
--white: #FFFFFF
```

### Aplicación de Colores
- **Botones primarios:** #D4A574 (secondary)
- **Texto principal:** #1A1A1A (dark)
- **Texto secundario:** #6B7280 (gray)
- **Backgrounds:** #FAFAF8 (light)
- **Cards:** #FFFFFF (white)
- **Links hover:** #984c4c (primary)

---

## 📝 TIPOGRAFÍA

### Fuentes
**Display/Títulos:** Playfair Display
- Weights: 400, 600, 700, 900
- Google Fonts: https://fonts.google.com/specimen/Playfair+Display

**Cuerpo de texto:** DM Sans
- Weights: 300, 400, 500, 600
- Google Fonts: https://fonts.google.com/specimen/DM+Sans

### Escalas Tipográficas

#### Desktop (1440px)
```
H1 - Hero: 64px / 900 / Playfair Display / line-height: 1.1
H2 - Section Title: 48px / 700 / Playfair Display / line-height: 1.2
H3 - Card Title: 28px / 600 / Playfair Display / line-height: 1.3
H4 - Subsection: 24px / 600 / Playfair Display / line-height: 1.4

Body Large: 20px / 300 / DM Sans / line-height: 1.7
Body Regular: 16px / 400 / DM Sans / line-height: 1.7
Body Small: 15px / 400 / DM Sans / line-height: 1.6
Caption: 14px / 500 / DM Sans / line-height: 1.5

Button Text: 16px / 600 / DM Sans / line-height: 1
Nav Link: 15px / 500 / DM Sans / line-height: 1
```

#### Mobile (768px y menos)
```
H1 - Hero: 40px / 900 / Playfair Display
H2 - Section Title: 32px / 700 / Playfair Display
H3 - Card Title: 20px / 600 / Playfair Display
Body Regular: 16px / 400 / DM Sans
```

---

## 📐 SPACING & LAYOUT

### Contenedor Principal
- Max-width: 1400px
- Padding lateral: 48px (desktop) / 24px (mobile)

### Grid System
- Columns: 12
- Gutter: 32px
- Margin: 48px

### Spacing Scale
```
xs: 8px
sm: 16px
md: 24px
lg: 32px
xl: 48px
2xl: 64px
3xl: 80px
4xl: 96px
```

### Secciones
- Padding vertical: 80px (desktop) / 48px (mobile)
- Margin entre secciones: 0 (usa background alternado)

---

## 🔲 COMPONENTES

### Header
- Height: 90px
- Background: #FFFFFF
- Box-shadow: 0 2px 20px rgba(0,0,0,0.06)
- Position: Sticky top
- Z-index: 1000

### Navigation
- Gap entre items: 40px
- Font-size: 15px
- Font-weight: 500
- Hover underline: 2px solid #984c4c
- Transition: 0.3s ease

### Buttons

#### Primary Button (CTA)
```
Background: #D4A574
Color: #1A1A1A
Padding: 16px 40px
Border-radius: 50px
Font-size: 16px
Font-weight: 600
Box-shadow: 0 10px 30px rgba(212,165,116,0.3)
Hover: translateY(-2px) + shadow increase
```

#### Secondary Button
```
Background: transparent
Border: 2px solid #984c4c
Color: #984c4c
Padding: 14px 38px
Border-radius: 50px
Hover: background #984c4c + color white
```

### Cards

#### Entity Card
```
Background: #FFFFFF
Padding: 32px
Border-radius: 15px
Box-shadow: 0 5px 20px rgba(0,0,0,0.05)
Border: 2px solid transparent
Hover: translateY(-5px) + border-color #D4A574
Transition: 0.3s ease
```

#### Timeline Card (Eventos)
```
Background: #FFFFFF
Border-radius: 20px
Image height: 280px
Content padding: 32px
Box-shadow: 0 10px 40px rgba(0,0,0,0.08)
Hover: scale(1.02)
```

### Featured Event Card
```
Grid: 1fr 1fr (50/50)
Border-radius: 20px
Box-shadow: 0 20px 60px rgba(0,0,0,0.1)
Image side: gradient overlay rgba(152,76,76,0.85)
Content padding: 48px
```

---

## 🖼️ IMÁGENES & OVERLAYS

### Hero Section
```
Background: linear-gradient(135deg, rgba(152,76,76,0.92), rgba(179,96,96,0.88))
Image: Sagrada Família Barcelona
Min-height: 600px
```

### Image Overlays
```
Dark gradient: linear-gradient(to top, rgba(0,0,0,0.7), transparent)
Brand gradient: linear-gradient(135deg, rgba(152,76,76,0.85), rgba(212,165,116,0.75))
```

---

## 🎭 EFECTOS & ANIMACIONES

### Shadows
```
Card: 0 5px 20px rgba(0,0,0,0.05)
Card hover: 0 15px 40px rgba(0,0,0,0.1)
Button: 0 10px 30px rgba(212,165,116,0.3)
Featured section: 0 20px 60px rgba(0,0,0,0.1)
```

### Border Radius
```
Small: 10px
Medium: 15px
Large: 20px
Pill: 50px (buttons, badges)
Circle: 50% (logo)
```

### Transitions
```
Default: all 0.3s ease
Hover effects: 0.3s ease
Transform: 0.3s ease
```

---

## 📱 BREAKPOINTS

```
Desktop: 1440px (diseño base)
Laptop: 1024px
Tablet: 768px
Mobile: 375px - 425px
```

### Responsive Adjustments
- Header: stack vertical en mobile
- Featured event: grid 1 columna
- Entity cards: 1 columna en mobile
- Font sizes: reducir 30-40%
- Padding: reducir 50%

---

## 🔧 COMPONENTES SVG

### Logo Container
```
Width: 60px
Height: 60px
Background: #984c4c
Border-radius: 50%
Font-size: 24px
Font-weight: 700
Color: #FFFFFF
```

### Icons (Propòsit Section)
- Size: 80x80px
- Colors: #984c4c (primary) + #D4A574 (secondary)
- Style: Line + fill combination
- Stroke-width: 2-2.5px

---

## 📄 PÁGINAS & SECCIONES

### 1. HOME
- Hero section
- Featured event card
- Qui som preview
- Propòsit preview
- CTA section

### 2. QUI SOM
- Hero mini
- Texto descriptivo central
- Timeline o historia (opcional)

### 3. PROPÒSIT
- 3 cards con SVG icons
- Grid 3 columnas
- Missió, Visió, Valors

### 4. TRANSPARÈNCIA
- Lista de documentos descargables
- Filtros por categoría/fecha
- Icons de PDF

### 5. ACTUALITAT
- Grid de posts/noticias
- Filtro por categorías
- Imagen destacada + excerpt
- Autor y fecha

### 6. DIRECTORI ENTITATS
- Grid de entity cards
- Buscador (opcional)
- Filtro alfabético (opcional)

### 7. ÀREA PRIVADA
- Login page
- Dashboard
- Repositorio interno
- Tablón de anuncios
- Calendario
- Formularios

### 8. CONTACTE
- Formulario
- Datos de contacto
- Mapa (opcional)

---

## 📋 EXPORT SETTINGS (FIGMA)

### Frames
- Desktop: 1440 x variable height
- Mobile: 375 x variable height

### Assets Export
- SVG: icons, logos
- PNG @2x: images, screenshots
- PDF: full page mockups

### Plugins Recomendados
- **Stark**: Accessibility checker
- **Unsplash**: Stock images
- **Content Reel**: Lorem ipsum
- **Iconify**: Icon library
- **Auto Layout**: Spacing helpers

---

## 🎯 IMPLEMENTATION NOTES

### WordPress + Elementor
- Usar widgets de Elementor para cada sección
- Custom CSS para animaciones
- ACF para campos personalizados (entidades)
- CPT para noticias/actualidad

### Fonts Loading
```html
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700;900&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
```

### CSS Variables
```css
:root {
  --primary: #984c4c;
  --primary-light: #b36060;
  --secondary: #D4A574;
  --accent: #E8956B;
  --dark: #1A1A1A;
  --light: #FAFAF8;
  --gray: #6B7280;
  --gray-light: #F3F4F6;
}
```

---

## ✅ CHECKLIST FIGMA

- [ ] Crear página "Cover" con overview
- [ ] Crear páginas para cada sección
- [ ] Definir color styles
- [ ] Definir text styles
- [ ] Crear componentes reutilizables
- [ ] Crear variants para estados (hover, active)
- [ ] Documentar auto-layout settings
- [ ] Exportar assets necesarios
- [ ] Crear versión mobile de cada página
- [ ] Añadir anotaciones y notas
- [ ] Crear prototipo navegable

---

**Versión:** 1.0
**Fecha:** Marzo 2025
**Proyecto:** Coordinadora Sagrada Família Web
