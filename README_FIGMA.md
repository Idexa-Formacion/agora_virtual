# 📦 PAQUETE FIGMA - COORDINADORA SAGRADA FAMÍLIA

## 🎯 Contenido del Paquete

Este paquete contiene todos los recursos necesarios para recrear el diseño completo de la web en Figma:

### ✅ Archivos Incluidos:

1. **DESIGN_SYSTEM.md** - Especificaciones completas de diseño
2. **propuesta_web_coordinadora_final.html** - Página HOME completa
3. **mockup_transparencia.html** - Página de Transparencia
4. **mockup_actualitat.html** - Página de Actualidad/Blog
5. **mockup_login.html** - Página de Login Área Privada

---

## 🚀 PROCESO DE IMPORTACIÓN A FIGMA

### MÉTODO 1: Captura de Pantalla (Más Rápido)

#### Paso 1: Preparar los navegadores
1. Abre cada archivo HTML en Chrome o Firefox
2. Ajusta el tamaño de la ventana a **1440px de ancho** (usa DevTools: F12 → Toggle Device Toolbar)

#### Paso 2: Capturar las páginas
Opción A - **Extensión GoFullPage** (Recomendado):
1. Instala la extensión "GoFullPage" en Chrome
2. Abre cada HTML
3. Click en la extensión → Captura completa
4. Descarga como PNG en alta calidad

Opción B - **Captura con Figma**:
1. En Figma: File → Import
2. Arrastra los archivos HTML (Figma puede intentar renderizarlos)
3. O captura manualmente con herramientas del sistema

#### Paso 3: Importar a Figma
1. Crea un nuevo archivo en Figma
2. Crea frames de 1440x[altura variable]
3. Arrastra las imágenes capturadas a cada frame
4. Nombra cada página correctamente:
   - `01_HOME`
   - `02_TRANSPARENCIA`
   - `03_ACTUALITAT`
   - `04_LOGIN`

---

### MÉTODO 2: Recreación Manual (Más Profesional)

#### Paso 1: Setup Inicial en Figma

1. **Crear archivo nuevo**
   - Desktop: 1440px width
   - Mobile: 375px width

2. **Configurar Color Styles**
   ```
   Primary: #984c4c
   Primary Light: #b36060
   Secondary: #D4A574
   Accent: #E8956B
   Dark: #1A1A1A
   Light: #FAFAF8
   Gray: #6B7280
   Gray Light: #F3F4F6
   ```
   
   En Figma: Click derecho en color → Create Style

3. **Configurar Text Styles**
   - Importar fuentes: Playfair Display y DM Sans
   - Crear estilos según DESIGN_SYSTEM.md:
     - H1/Hero: 64px / Playfair Display / 900
     - H2/Section: 48px / Playfair Display / 700
     - Body: 16px / DM Sans / 400
     - etc.

#### Paso 2: Crear Componentes Base

1. **Header Component**
   - Frame: 1440 x 90px
   - Auto-layout horizontal
   - Crear variantes: Default, Sticky

2. **Button Components**
   - Primary Button: Secondary color background
   - Secondary Button: Transparent con border
   - Crear variantes: Default, Hover, Disabled

3. **Card Components**
   - Entity Card
   - Blog Card
   - Document Card
   - Crear con auto-layout

#### Paso 3: Construir Páginas

Para cada página HTML:
1. Abre el HTML en el navegador
2. Usa las especificaciones del DESIGN_SYSTEM.md
3. Recrea sección por sección
4. Usa los componentes creados
5. Aplica auto-layout para responsive

---

## 📋 ESTRUCTURA DE PÁGINAS EN FIGMA

Organiza tu archivo Figma así:

```
📁 COORDINADORA SAGRADA FAMÍLIA
│
├── 📄 Cover (página de presentación)
│
├── 🎨 Design System
│   ├── Colors
│   ├── Typography
│   ├── Spacing
│   └── Components
│
├── 🖥️ Desktop (1440px)
│   ├── 01_HOME
│   ├── 02_QUI_SOM
│   ├── 03_PROPOSIT
│   ├── 04_TRANSPARENCIA
│   ├── 05_ACTUALITAT
│   ├── 06_DIRECTORI_ENTITATS
│   ├── 07_CONTACTE
│   └── 08_AREA_PRIVADA
│       ├── Login
│       ├── Dashboard
│       ├── Repositorio
│       ├── Tablón Anuncios
│       └── Calendario
│
└── 📱 Mobile (375px)
    └── (versiones mobile de cada página)
```

---

## 🎨 ASSETS NECESARIOS

### Imágenes Sugeridas (Unsplash):
- **Hero**: Sagrada Família - `https://unsplash.com/s/photos/sagrada-familia`
- **Eventos**: Castellers Barcelona - `https://unsplash.com/s/photos/castellers`
- **Barrio**: Eixample Barcelona - `https://unsplash.com/s/photos/barcelona-eixample`

### Iconos SVG:
Los SVGs de los iconos están embebidos en los HTML. Puedes:
1. Copiar el código SVG
2. Pegarlo en Figma (File → Place Image → pega el código)
3. Figma lo convertirá en vector editable

---

## ⚡ TIPS RÁPIDOS FIGMA

### Plugins Útiles:
1. **Unsplash** - Para imágenes de placeholder
2. **Content Reel** - Para texto placeholder en catalán
3. **Stark** - Para verificar accesibilidad de colores
4. **Iconify** - Para iconos adicionales si necesitas

### Atajos de Teclado:
- `Cmd/Ctrl + G` - Agrupar elementos
- `Cmd/Ctrl + E` - Flatten selection
- `Shift + A` - Auto-layout
- `Cmd/Ctrl + /` - Buscar acciones

### Auto-Layout Tips:
- Usa auto-layout en TODOS los componentes
- Padding: 32px para cards, 48px para secciones
- Gap: 24px para elementos relacionados

---

## 📊 ENTREGABLES FINALES DESDE FIGMA

Una vez tengas todo en Figma, exporta:

### Para Presentación Cliente:
1. **PDF Completo**
   - File → Export → PDF
   - Include all pages
   - Incluir anotaciones si es necesario

2. **Imágenes PNG** (alta resolución)
   - Seleccionar cada frame
   - Export → PNG → 2x scale

### Para Desarrollo:
1. **Specs para desarrolladores**
   - Usar Figma Inspect panel
   - Exportar CSS donde sea necesario

2. **Assets individuales**
   - Logos: SVG
   - Iconos: SVG
   - Imágenes: PNG @2x

---

## ✅ CHECKLIST FINAL

Antes de considerar el Figma completo:

- [ ] Todos los color styles creados
- [ ] Todos los text styles configurados
- [ ] Header component con variantes
- [ ] Button components completos
- [ ] Card components creados
- [ ] Todas las páginas desktop creadas
- [ ] Versiones mobile de páginas principales
- [ ] Prototipo básico enlazando páginas
- [ ] Anotaciones para especificaciones técnicas
- [ ] Página de portada/cover atractiva
- [ ] Export de PDF para presentación

---

## 🆘 SOPORTE

Si tienes dudas sobre:
- **Especificaciones de diseño**: Ver DESIGN_SYSTEM.md
- **Componentes específicos**: Inspeccionar los HTML en DevTools
- **Colores/tipografías**: Todo está documentado en DESIGN_SYSTEM.md

---

## 📞 PRÓXIMOS PASOS

1. ✅ Importar/recrear mockups en Figma
2. ✅ Crear componentes reutilizables
3. ✅ Diseñar versiones mobile
4. ✅ Crear prototipo navegable
5. ✅ Exportar PDF para firma
6. ✅ Presentar al cliente

---

**Tiempo estimado de trabajo en Figma:**
- Setup inicial: 1-2 horas
- Componentes base: 2-3 horas
- Páginas desktop: 4-6 horas
- Versiones mobile: 2-3 horas
- Prototipo y polish: 1-2 horas

**TOTAL: 10-16 horas** (dependiendo de experiencia con Figma)

---

## 🎯 ¿NECESITAS AYUDA?

Si prefieres que te genere:
- ✅ Más páginas específicas (Dashboard, Calendario, etc.)
- ✅ Componentes SVG adicionales
- ✅ Variantes de diseño
- ✅ Guías de desarrollo más detalladas

**¡Solo pídelo!**

---

**Versión:** 1.0  
**Proyecto:** Coordinadora Sagrada Família  
**Fecha:** Marzo 2025
