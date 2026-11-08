# 🚀 Instrucciones de Despliegue en Vercel

## Repositorio Creado
✅ **Repositorio GitHub**: https://github.com/saltbalente/maestrosbrujosusa

## Pasos para Desplegar en Vercel

### Método 1: Desde GitHub (Recomendado)
1. Ve a [vercel.com](https://vercel.com) e inicia sesión
2. Haz clic en "New Project"
3. Conecta tu cuenta de GitHub si no lo has hecho
4. Busca el repositorio "Maestrosbrujosusa"
5. Haz clic en "Import"
6. Vercel detectará automáticamente que es un sitio estático
7. Haz clic en "Deploy"

### Método 2: Vercel CLI
```bash
# Instalar Vercel CLI globalmente
npm i -g vercel

# Desde la carpeta del proyecto
cd /ruta/al/proyecto
vercel

# Seguir las instrucciones:
# - Set up and deploy? Y
# - Which scope? (tu cuenta)
# - Link to existing project? N
# - What's your project's name? maestrosbrujosusa
# - In which directory is your code located? ./
```

### Método 3: Arrastrar y Soltar
1. Ve a [vercel.com](https://vercel.com)
2. Arrastra toda la carpeta del proyecto al área de despliegue
3. Vercel desplegará automáticamente

## Configuración Automática
El proyecto incluye `vercel.json` que configura automáticamente:
- ✅ Optimización de imágenes
- ✅ Cache headers para mejor rendimiento
- ✅ Headers de seguridad
- ✅ Compresión automática

## Dominio Personalizado (Opcional)
Una vez desplegado:
1. Ve al dashboard del proyecto en Vercel
2. Sección "Domains"
3. Agrega tu dominio personalizado
4. Configura los DNS según las instrucciones

## Variables de Entorno
Si necesitas configurar variables:
1. Dashboard de Vercel → Settings → Environment Variables
2. Agregar:
   - `WHATSAPP_NUMBER`: 12253607317
   - `GOOGLE_ANALYTICS_ID`: T8H6RZ69

## Actualizaciones Futuras
Para actualizar el sitio:
```bash
git add .
git commit -m "Descripción de cambios"
git push origin main
```
Vercel desplegará automáticamente los cambios.

## URLs Esperadas
- **Repositorio**: https://github.com/saltbalente/Maestrosbrujosusa
- **Sitio en Vercel**: https://maestrosbrujosusa.vercel.app (se generará automáticamente)

## Características del Sitio
- 📱 Totalmente responsivo
- ⚡ Optimizado para velocidad
- 🔍 SEO optimizado
- 💬 Integración WhatsApp
- 🎨 Efectos visuales modernos
- 📊 Google Analytics integrado

¡El proyecto está listo para producción! 🎉