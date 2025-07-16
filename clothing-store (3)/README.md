# Fashion Store Premium

Una tienda de ropa premium con diseño minimalista, construida con Next.js 14 y Tailwind CSS.

## 🚀 Características

- **Diseño Minimalista Premium** - Inspirado en marcas de lujo como COS, Everlane
- **Navegación por Swipe** - Experiencia móvil fluida
- **Carrito y Wishlist Flotantes** - UX moderna y accesible
- **Información Detallada de Productos** - Materiales, cuidado, sostenibilidad
- **Responsive Design** - Optimizado para todos los dispositivos
- **Performance Optimizada** - Next.js 14 con App Router

## 🛠️ Tecnologías

- **Next.js 14** - Framework React con App Router
- **TypeScript** - Tipado estático
- **Tailwind CSS** - Styling utility-first
- **Lucide React** - Iconos modernos
- **Radix UI** - Componentes accesibles

## 📦 Instalación

\`\`\`bash
# Clonar el repositorio
git clone <repository-url>

# Instalar dependencias
npm install

# Ejecutar en desarrollo
npm run dev

# Construir para producción
npm run build

# Ejecutar en producción
npm start
\`\`\`

## 🌐 Deployment en Render

1. Conecta tu repositorio de GitHub a Render
2. Selecciona "Web Service"
3. Configura:
   - **Build Command**: `npm install && npm run build`
   - **Start Command**: `npm start`
   - **Environment**: Node
   - **Plan**: Free

## 📱 Funcionalidades

### Navegación
- Swipe horizontal para cambiar productos
- Navegación por teclado (flechas)
- Indicadores visuales de posición

### Productos
- 8 productos premium con información detallada
- Materiales, cuidado y sostenibilidad
- Reviews y ratings
- Información de diseñador y colección

### Carrito y Wishlist
- Gestión completa de productos
- Cálculo automático de totales
- Persistencia de estado

### Diseño
- Tipografía elegante y minimalista
- Colores neutros premium
- Animaciones suaves
- Glassmorphism effects

## 🎨 Personalización

### Colores
Modifica los colores en `tailwind.config.js` y `app/globals.css`

### Productos
Actualiza la información en `lib/products.ts`

### Componentes
Los componentes están en `/components` y son totalmente personalizables

## 📄 Licencia

MIT License - ver LICENSE file para detalles.
