# 🚀 Despliegue en Netlify

Este proyecto está configurado para desplegarse fácilmente en Netlify.

## 📋 Archivos de Configuración

Los siguientes archivos han sido creados para el despliegue:

- `netlify.toml` - Configuración principal de Netlify
- `public/_redirects` - Manejo de rutas SPA
- `public/_headers` - Headers de seguridad y cache

## 🔧 Configuración Automática

Netlify detectará automáticamente la configuración desde `netlify.toml`:

- **Build Command**: `npm run build`
- **Publish Directory**: `dist`
- **Node Version**: 18

## 📝 Pasos para Desplegar

### Opción 1: Despliegue Automático (Git)

1. Sube tu código a GitHub, GitLab o Bitbucket
2. Ve a [Netlify](https://netlify.com)
3. Conecta tu repositorio
4. Netlify detectará automáticamente la configuración
5. ¡Listo! Tu sitio estará desplegado

### Opción 2: Despliegue Manual

1. Ejecuta `npm run build` localmente
2. Sube la carpeta `dist` a Netlify como sitio estático
3. Configura manualmente:
   - **Build Command**: `npm run build`
   - **Publish Directory**: `dist`

## 🌐 Características Configuradas

- ✅ **SPA Support**: Todas las rutas se redirigen correctamente
- ✅ **Security Headers**: Protección XSS, frame options, etc.
- ✅ **Asset Caching**: Cache agresivo para archivos estáticos
- ✅ **SEO Friendly**: Headers apropiados para motores de búsqueda

## 🔍 Verificación

Después del despliegue, verifica que:

- La aplicación carga correctamente
- Las rutas de React Router funcionan (navegación directa)
- El modo oscuro funciona
- El carrito y favoritos se mantienen
- Las imágenes y assets cargan rápido

## 📞 Soporte

Si tienes problemas con el despliegue, revisa:

- [Documentación de Netlify](https://docs.netlify.com/)
- [Guía de despliegue de Vite](https://vitejs.dev/guide/static-deploy.html)
- Los logs de build en Netlify

¡Tu E-Commerce está listo para el mundo! 🌍