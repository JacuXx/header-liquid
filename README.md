# Header Categories - Kalles Theme Custom Header

Un header personalizado avanzado para el tema Kalles de Shopify que combina un diseño moderno con funcionalidades personalizadas para tiendas de comercio electrónico.


## 📱 Diseño Responsive

### 🖥️ Vista Desktop
![Header Desktop - Búsqueda predictiva con icono a la izquierda, botón BEST SELLERS y navegación por categorías](https://github.com/JacuXx/header-liquid/blob/main/img/desktop.png)

**Características destacadas en desktop:**
- 🔍 **Búsqueda predictiva activa**: Barra de búsqueda amplia con placeholder "Buscar productos"
- 📍 **Icono de búsqueda a la izquierda**: Diseño único que mejora la UX
- 🏷️ **Botón "BEST SELLERS"**: Botón personalizado prominente y funcional
- 👤 **Iconos de usuario y carrito**: Posicionados estratégicamente a la derecha
- ✨ **Diseño limpio**: Espaciado profesional y tipografía optimizada

### 📱 Vista Mobile
![Header Mobile - Diseño compacto con hamburger menu, búsqueda predictiva y navegación optimizada](https://github.com/JacuXx/header-liquid/blob/main/img/movil.png)

**Características destacadas en mobile:**
- 📱 **Header compacto responsive**: Optimizado para pantallas pequeñas
- 🔍 **Búsqueda predictiva móvil**: Campo de búsqueda con placeholder "Buscar productos"
- ☰ **Navegación hamburguesa**: Menú lateral accesible con un toque
- 👤 **Iconos de acción**: Usuario y carrito (con contador "0") perfectamente posicionados
- 🎨 **Diseño minimalista**: Interface limpia que mantiene toda la funcionalidad
- ⚡ **Performance optimizada**: Carga rápida y interacciones fluidas

## 🎯 Elementos Visuales Destacados

### Desktop Layout (Como se ve en la imagen)
```
    [🔍 Buscar productos                                ] [BEST SELLERS] [👤] [🛒0]
─────────────────────────────────────────────────────────────────────────────────────
                          [mega]    [mega]    [base]
```

### Mobile Layout (Como se ve en la imagen)
```
[☰]                                                          [👤] [🛒0]
──────────────────────────────────────────────────────────────────────
    [🔍 Buscar productos                                ]
```

**Elementos clave visualizados en las imágenes:**
- ✅ **Búsqueda predictiva**: Campo de búsqueda con placeholder "Buscar productos" perfectamente funcional
- ✅ **Icono de búsqueda izquierda**: Implementado y visible en el campo de búsqueda
- ✅ **Botón "BEST SELLERS"**: Botón personalizado negro prominente en desktop
- ✅ **Navegación inferior**: Categorías "mega", "mega", "base" claramente visibles
- ✅ **Iconos de usuario/carrito**: Con contador de items (0) visible
- ✅ **Responsive perfecto**: Adaptación completa entre desktop y mobile
- ✅ **Hamburger menu**: Navegación lateral en móvil perfectamente implementada

## 🔍 Funcionalidad de Búsqueda Predictiva

### Características de la Búsqueda
- **🎯 Búsqueda en tiempo real**: Los usuarios pueden escribir y obtener sugerencias instantáneas
- **📱 Totalmente responsive**: Funciona perfectamente en desktop y mobile
- **🔍 Icono posicionado a la izquierda**: Mejora la UX con indicación visual clara
- **⚡ Performance optimizada**: Búsqueda rápida sin afectar la velocidad del sitio
- **🎨 Diseño integrado**: Se integra perfectamente con el diseño del header

## ✨ Características Únicas

### 🔍 Búsqueda Avanzada con Predicción
- **🎯 Búsqueda predictiva en tiempo real**: Los usuarios obtienen sugerencias mientras escriben
- **📍 Icono de búsqueda a la izquierda**: Diseño único que mejora la UX y la accesibilidad
- **📱 Búsqueda responsive**: Se adapta perfectamente a todos los dispositivos manteniendo funcionalidad
- **🎨 Estilos personalizados**: Bordes redondeados, colores y efectos hover customizables
- **⚡ Integración completa**: Compatible con la búsqueda nativa de Shopify y sus funciones predictivas
- **🔄 Placeholder inteligente**: Texto "Buscar productos" que guía al usuario
- **💫 Efectos visuales**: Transiciones suaves y feedback visual al interactuar

### 🎨 Diseños Flexibles
- **Design 1 y Design 2**: Dos variantes de layout disponibles
- **Header transparente**: Opción para páginas de inicio
- **Alturas customizables**: Control total sobre las dimensiones
- **Alineación configurable**: Left, Center, Right para el menú principal

### 📱 Optimización Mobile
- **Header mobile personalizado**: Altura y comportamiento específicos
- **Categorías opcionales**: Show/hide en dispositivos móviles
- **Navegación simplificada**: Solo iconos o completa
- **Performance optimizada**: CSS específico para cada breakpoint

### 🎯 Botones Personalizados
- **Botones "mega" y "base"**: Enlaces personalizables con iconos
- **Colores customizables**: Variables CSS para fácil personalización
- **Efectos hover**: Transiciones suaves y modernas
- **Responsive**: Se adaptan automáticamente a móviles

### 🎨 Personalización Completa
- **Colores independientes**: Normal y hover states
- **Transparencia configurable**: Para headers overlay
- **Bordes y separadores**: Opcionales y customizables
- **Efectos de animación**: Slide up y fade in disponibles

## 🚀 Instalación y Configuración

### Paso 1: Instalación de Archivos

1. **Copia los archivos principales** a tu tema Kalles:
   ```
   📁 assets/
   └── header-search.css
   
   📁 sections/
   ├── header-categories-menu.liquid
   └── header-sidebar.liquid
   
   📁 snippets/
   └── t4s_group_btns.liquid
   ```

2. **Verifica la estructura** de tu tema antes de proceder

### Paso 2: Configuración del Theme

1. **Accede al Customizer** de Shopify
2. **Navega a Header** en la configuración del tema
3. **Selecciona "Header Categories"** como tu sección de header
4. **Activa las opciones principales**:
   - ✅ Enable full Width
   - ✅ Show dropdown arrow
   - ✅ Show border bottom

### Paso 3: Configuración de Búsqueda

#### Activar Search Left Icon
```liquid
<!-- En header-categories-menu.liquid, busca: -->
"search_left_icon": {
  "type": "checkbox",
  "id": "search_left_icon",
  "label": "Enable search icon on left",
  "default": true
}
```

#### Configurar estilos CSS
```css
/* Las variables CSS están en header-search.css */
:root {
  --custom-btn-text-color: #222222;
  --custom-btn-text-hover-color: #56cfe1;
  --custom-btn-border-color: rgba(34, 34, 34, 0.2);
  --custom-btn-border-hover-color: #56cfe1;
}
```

### Paso 4: Configuración de Botones Personalizados

1. **En el Customizer**, ve a la sección Header
2. **Agrega bloques** de tipo "mega" y "base"
3. **Configura cada botón**:
   - **URL**: Enlace de destino
   - **Texto**: Etiqueta del botón
   - **Icon**: Código de icono (Line Awesome)
   - **Colors**: Colores personalizados opcionales

### Paso 5: Configuración Mobile

1. **Custom header mobile height**: 60-80px recomendado
2. **Show Categories**: Activar si quieres categorías en móvil
3. **Only click icon**: Para navegación simplificada

## ⚙️ Opciones de Configuración

### Layout Options
```yaml
Layout Types:
  - menu_left: Menú a la izquierda
  - menu_right: Menú a la derecha
  - default: Layout estándar

Header Designs:
  - design_1: Diseño clásico
  - design_2: Diseño moderno

Alignment:
  - left: Alineación izquierda
  - center: Alineación centrada  
  - right: Alineación derecha
```

### Search Configuration
```yaml
Search Options:
  - search_left_icon: Icono búsqueda izquierda
  - search_form_max_width: Ancho máximo del formulario
  - search_mobile_optimization: Optimización móvil
```

### Color Scheme
```yaml
Normal State:
  - text_color: Color del texto
  - background_color: Color de fondo
  - border_color: Color de bordes

Hover State:
  - text_hover_color: Color texto hover
  - background_hover_color: Color fondo hover
  - border_hover_color: Color borde hover

Transparent Mode:
  - transparent_text_color: Color en modo transparente
  - transparent_bg_color: Fondo transparente
  - opacity_transparent: Opacidad transparente
```

## 🎨 Personalización Avanzada

### CSS Variables
```css
/* Personaliza fácilmente los colores */
:root {
  --custom-btn-text-color: #222222;
  --custom-btn-text-hover-color: #56cfe1;
  --custom-btn-border-color: rgba(34, 34, 34, 0.2);
  --custom-btn-border-hover-color: #56cfe1;
  --custom-btn-bg-color: transparent;
  --custom-btn-bg-hover-color: rgba(86, 207, 225, 0.1);
  --custom-btn-border-radius: 4px;
  --custom-btn-border-width: 1px;
}
```

### Responsive Breakpoints
```css
/* Desktop */
@media (min-width: 1025px) {
  .search-width-custom { width: 58%; }
  .logo-width-custom { width: 15%; }
  .iconos-custom { width: 5%; }
}

/* Tablet */
@media (min-width: 768px) and (max-width: 1024px) {
  /* Estilos específicos para tablet */
}

/* Mobile */
@media (max-width: 768px) {
  /* Estilos específicos para móvil */
}
```

## 🔧 Solución de Problemas

### Problemas Comunes

**❌ El icono de búsqueda no aparece a la izquierda**
```css
/* Verifica que esté incluido header-search.css */
.t4s-search-header__submit-left {
  left: 3px;
  width: 38px;
}
```

**❌ Los botones personalizados no se muestran**
```liquid
<!-- Verifica que t4s_group_btns.liquid esté incluido -->
{%- render 't4s_group_btns', se_stts: se_stts -%}
```

**❌ El header no es responsive**
```css
/* Asegúrate de que las media queries estén cargando */
@media (max-width: 768px) {
  .t4s-custom-buttons-wrapper {
    display: none !important;
  }
}
```

### Debug Tips
1. **Inspecciona elementos** para verificar que las clases CSS se apliquen
2. **Revisa la consola** para errores de JavaScript
3. **Verifica archivos** que estén en las carpetas correctas
4. **Prueba en incógnito** para evitar cache issues

## 📚 Recursos Adicionales

### Iconos
- **Line Awesome Icons**: [https://kalles.the4.co/font-lineawesome/](https://kalles.the4.co/font-lineawesome/)
- **Formato**: `las la-icon-name`

### Shopify Liquid
- **Documentación**: [https://shopify.dev/docs/themes/liquid](https://shopify.dev/docs/themes/liquid)
- **Schema Settings**: [https://shopify.dev/docs/themes/settings](https://shopify.dev/docs/themes/settings)

### CSS Grid & Flexbox
- **CSS Grid Guide**: Para layouts avanzados
- **Flexbox Guide**: Para alineación de elementos

## 📞 Soporte

Para soporte técnico o customizaciones adicionales:

1. **Documenta el problema** con screenshots
2. **Incluye el código** que estás usando
3. **Especifica el dispositivo** y navegador
4. **Proporciona la URL** de prueba si es posible

---

## 📝 Changelog

### v1.0.0
- ✅ Header categories inicial
- ✅ Búsqueda con icono izquierda
- ✅ Botones personalizados mega/base
- ✅ Responsive design completo
- ✅ Configuración avanzada

### Próximas Características
- 🔄 Modo dark/light automático
- 🔄 Animaciones adicionales
- 🔄 Más tipos de botones
- 🔄 Integración con apps populares

---

**¿Te gusta este header?** ⭐ Dale una estrella al repositorio y compártelo con otros desarrolladores de Shopify.
