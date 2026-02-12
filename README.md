# Sitio Web Gutigu.com - Instrucciones de Instalación

## 📁 Archivos incluidos

1. **index.html** - Página principal del sitio
2. **privacy-policy.html** - Política de privacidad (requerida para Google Play)
3. **terms.html** - Términos de uso
4. **guardian_digital_play_store.docx** - Guía completa para publicar en Google Play Store

## 🚀 Cómo subir al servidor

### Opción 1: Usando FTP/SFTP

1. Descarga todos los archivos HTML
2. Conecta a tu servidor usando un cliente FTP (FileZilla, WinSCP, etc.)
3. Navega a la carpeta raíz de tu dominio (generalmente `/public_html` o `/www`)
4. Sube los 3 archivos HTML a la raíz del sitio

### Opción 2: Usando cPanel

1. Accede al panel de control de tu hosting
2. Ve a "Administrador de archivos"
3. Navega a `public_html`
4. Haz clic en "Subir archivos"
5. Selecciona los 3 archivos HTML y súbelos

### Opción 3: Usando GitHub Pages (hosting gratuito)

1. Crea un repositorio en GitHub
2. Sube los archivos HTML
3. Ve a Settings → Pages
4. Activa GitHub Pages desde la rama main
5. Configura tu dominio personalizado gutigu.com

## 🔗 URLs importantes

Una vez subidos, tus archivos estarán disponibles en:

- **Página principal**: https://gutigu.com
- **Política de privacidad**: https://gutigu.com/privacy-policy.html
- **Términos de uso**: https://gutigu.com/terms.html

## 📱 Para Google Play Store

Cuando completes el formulario de Google Play, usa:

**URL de Política de Privacidad**: `https://gutigu.com/privacy-policy.html`

**Sitio web de la aplicación**: `https://gutigu.com`

**Email de contacto**: `contacto@gutigu.com`

## ✅ Verificación

Después de subir los archivos, verifica que todo funcione:

1. Abre https://gutigu.com en tu navegador
2. Verifica que la página se carga correctamente
3. Prueba los enlaces del menú (Apps, Nosotros, Contacto)
4. Verifica que la política de privacidad se carga en https://gutigu.com/privacy-policy.html
5. Verifica los términos en https://gutigu.com/terms.html

## 🎨 Personalización futura

Para agregar más apps en el futuro:

1. Abre `index.html` en un editor de texto
2. Busca la sección `<div class="apps-grid">`
3. Duplica el bloque `<div class="app-card">` de Guardian Digital
4. Modifica el contenido con la información de tu nueva app
5. Sube el archivo actualizado

## 📧 Email de contacto

Configura el email `contacto@gutigu.com` en tu proveedor de hosting para que los usuarios puedan contactarte.

## 🔒 SSL/HTTPS

Asegúrate de que tu hosting tenga un certificado SSL activo para que tu sitio sea HTTPS (requerido por Google Play).

## 📞 Soporte

Si tienes problemas técnicos, contacta al soporte de tu proveedor de hosting.

---

**¡Éxito con tu lanzamiento de Guardian Digital! 🚀**
