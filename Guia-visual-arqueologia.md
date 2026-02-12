# 🎨 GUÍA DE IDENTIDAD VISUAL
## Arqueología del Silencio

---

## PALETA DE COLORES

### Colores Primarios
- **Azul Noche** (Fondo oscuro, headers principales)
  - HEX: `#1A2332`
  - RGB: 26, 35, 50
  - Uso: Fondos hero, footer, títulos principales

- **Terracota** (Identidad, acentos cálidos)
  - HEX: `#C96846`
  - RGB: 201, 104, 70
  - Uso: Enlaces, bordes, botones secundarios, acentos

- **Dorado** (Lujo, misticismo, CTAs)
  - HEX: `#D4AF37`
  - RGB: 212, 175, 55
  - Uso: Hover states, títulos destacados, botones primarios

### Colores Secundarios
- **Fondo Claro** (Base limpia)
  - HEX: `#FAF8F5`
  - RGB: 250, 248, 245
  - Uso: Background general del sitio

- **Texto Oscuro** (Legibilidad)
  - HEX: `#2C2C2C`
  - RGB: 44, 44, 44
  - Uso: Cuerpo de texto, párrafos

- **Gris Suave** (Elementos sutiles)
  - HEX: `#8B8B8B`
  - RGB: 139, 139, 139
  - Uso: Meta información, fechas, breadcrumbs

---

## TIPOGRAFÍA

### Fuente Display (Títulos grandes, Hero)
**Cormorant Garamond** (Serif elegante)
- Pesos: 400 (Regular), 600 (SemiBold), 700 (Bold)
- Fallback: Georgia, serif
- Uso: H1, títulos de portada, quotes destacados

### Fuente de Títulos (H2-H6)
**Lora** (Serif moderna)
- Pesos: 400 (Regular), 700 (Bold)
- Fallback: Georgia, serif
- Uso: H2, H3, H4, subtítulos de artículos

### Fuente de Cuerpo (Párrafos, navegación)
**Inter** (Sans-serif legible)
- Pesos: 400 (Regular), 500 (Medium), 600 (SemiBold)
- Fallback: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif
- Uso: Cuerpo de texto, menú, botones, UI general

### Fuente Monoespaciada (Código)
**JetBrains Mono** (Opcional, si hay snippets)
- Peso: 400
- Fallback: Consolas, Monaco, monospace

---

## JERARQUÍA VISUAL

### Tamaños de Fuente

### Espaciado


---

## APLICACIONES ESPECÍFICAS

### Banner Superior (Header/Nav)
- Fondo: `#FFFFFF` o `#FAF8F5`
- Texto menú: `#2C2C2C` (Inter Medium)
- Hover menú: `#C96846` (Terracota)
- Fuente: Inter 500 (Medium), 0.95rem

### Portada (Hero Section)
- Fondo: `#1A2332` (Azul Noche) con gradiente sutil
- Título: `#D4AF37` (Dorado) - Cormoant Garamond Bold
- Subtítulo: `#FAF8F5` - Inter Regular
- Borde: `2px solid #D4AF37`

### Cards de Posts
- Fondo: `#FFFFFF`
- Borde izquierdo: `4px solid #C96846`
- Título: `#1A2332` - Lora Bold
- Excerpt: `#2C2C2C` - Inter Regular
- Hover: border → `#D4AF37`, transform: translateX(8px)

### Botones
- **Primario (CTA)**: Fondo `#D4AF37`, texto `#1A2332`, hover: `#C96846`
- **Secundario**: Borde `2px solid #C96846`, texto `#C96846`, hover: fondo `#C96846`, texto blanco

### Footer
- Fondo: `#1A2332`
- Texto: `#FAF8F5`
- Enlaces: `#D4AF37`

---

## PRINCIPIOS DE DISEÑO

1. **Elegancia minimalista**: Espacios en blanco generosos
2. **Misticismo contenido**: Dorado como acento, no protagonista
3. **Legibilidad prioritaria**: Contraste WCAG AA mínimo
4. **Transiciones suaves**: 0.3s ease en hover states
5. **Mobile-first**: Todo responsive desde 320px

---

## NOTAS TÉCNICAS

- **Tema Hugo**: PaperMod (customizado)
- **CSS personalizado**: `assets/css/extended/custom.css`
- **Fuentes cargadas vía**: Google Fonts (agregar al head)
- **Iconos**: Lucide Icons o Font Awesome (minimal)

---

*Versión 1.0 - Febrero 2026*
*Actualizar este documento con cada cambio aprobado*
