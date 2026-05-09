# ProShop - E-Commerce Profesional

Una tienda online moderna, profesional y completamente funcional construida con React, TailwindCSS y Vite, inspirada en Amazon, Mercado Libre y Nike.

## 🎯 Características Principales

### 🛍️ Carrito de Compras
- Agregar y eliminar productos
- Modificar cantidades
- Cálculo automático de totales, impuestos y envíos
- Persistencia en LocalStorage

### ❤️ Sistema de Favoritos
- Marcar productos como favoritos
- Página dedicada de favoritos
- Agregar favoritos al carrito desde la página

### 🔍 Búsqueda y Filtros Avanzados
- Buscador en tiempo real
- Filtros por categoría
- Filtro por rango de precio
- Ordenamiento (precio, calificación, destacados)

### 💳 Checkout y Pagos Simulados
- Proceso de compra de dos pasos
- Validación de información de envío
- Información de pago (simulado)
- Confirmación de compra con modal

### 📊 Dashboard Administrativo
- Gráficas de ventas diarias
- Análisis de ventas por categoría
- Productos más vendidos
- Estadísticas KPI
- Historial de órdenes recientes
- Acceso restringido con login

### 📦 Órdenes y Compras
- Historial de órdenes
- Exportación a PDF de comprobantes
- Detalles de cada orden
- Estado de envío

### 🎨 Interfaz de Usuario Premium
- Dark Mode completamente funcional
- Diseño responsive (móvil, tablet, desktop)
- Animaciones suaves y transiciones
- Sidebar moderna
- Header profesional con búsqueda
- Footer con información de contacto

### 🏪 Catálogo de Productos
- 12 productos de ejemplo de diferentes categorías
- Tarjetas de producto con imágenes
- Calificaciones y reseñas
- Información de stock
- Detalles técnicos de productos
- Modal de visualización de detalles

### 💾 Persistencia de Datos
- LocalStorage para carrito
- LocalStorage para favoritos
- LocalStorage para órdenes
- LocalStorage para preferencias de tema
- LocalStorage para datos de usuario



## 🎨 Paleta de Colores

- **Primario**: Azul (#3B82F6)
- **Secundario**: Gris (#1F2937)
- **Éxito**: Verde (#10B981)
- **Error**: Rojo (#EF4444)
- **Advertencia**: Amarillo (#F59E0B)
- **Acentos**: Púrpura (#8B5CF6)

## 📦 Dependencias

### Principales
- **React**: Framework de UI
- **React DOM**: Renderizado en el DOM
- **React Router DOM**: Navegación (preparado para routing)
- **TailwindCSS**: Diseño utilities-first
- **Vite**: Build tool y dev server
- **Recharts**: Gráficas y visualizaciones
- **jsPDF**: Exportación a PDF
- **html2canvas**: Captura de pantalla para PDF
- **Lucide React**: Iconos
- **Framer Motion**: Animaciones (preparado)
- **Zustand**: Gestión de estado (alternativa)

## 🔧 Funcionalidades Técnicas

### Context API
- Gestión de estado global
- Acciones de carrito
- Gestión de favoritos
- Sistema de órdenes
- Tema (dark/light mode)
- Información de usuario

### LocalStorage
- Persistencia automática del carrito
- Persistencia de favoritos
- Persistencia de órdenes
- Persistencia del tema seleccionado
- Persistencia de datos de usuario

### Animaciones
- Fade in al cargar componentes
- Slide up para modales
- Hover effects en tarjetas
- Transiciones suaves
- Pulse soft animation

### Componentes Reutilizables
- **Button**: Con variantes (primary, secondary, danger, success, outline, ghost)
- **Card**: Con opción de hover effect
- **Modal**: Con diferentes tamaños
- **Loader**: Con diferentes tamaños y modo fullscreen
- **Notification**: Con tipos (success, error, info, warning)
- **ProductCard**: Tarjeta interactiva con favoritos y carrito

## 📱 Responsive Design

- **Mobile-first**: Diseñado primero para móviles
- **Breakpoints**:
  - sm: 640px
  - md: 768px
  - lg: 1024px
  - xl: 1280px
  - 2xl: 1536px

## 🔒 Características de Seguridad (Simuladas)

- Login de administrador (sin backend)
- Validación de formularios básica
- Protección de rutas (solo admin ve dashboard)
- CSRF simulado en pagos

## 📊 Datos de Ejemplo

El proyecto incluye 12 productos de ejemplo en las siguientes categorías:

- **Electrónica**: Laptops, iPhones, auriculares, monitores, etc.
- **Calzado**: Zapatillas deportivas y de running
- **Accesorios**: Mochilas, relojes inteligentes, etc.
- **Muebles**: Sofás y otros muebles

