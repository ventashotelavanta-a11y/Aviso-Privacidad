# Avanta Hotel - Política de Privacidad

Página de Política de Privacidad con diseño profesional para Avanta Hotel & Villas.

## 📁 Estructura de archivos para GitHub

```
tu-repositorio/
├── politica-privacidad-github.html  (renombrar a index.html)
├── images/
│   ├── logo_avanta_principal.png
│   └── habitaciones_avanta.jpg
└── README.md
```

## 🚀 Instrucciones para subir a GitHub Pages

### Paso 1: Crear repositorio en GitHub
1. Ve a GitHub.com y crea un nuevo repositorio
2. Nómbralo como quieras (ej: `avanta-privacidad`)
3. Marca como **público**

### Paso 2: Estructura de carpetas
Crea esta estructura en tu repositorio:

```bash
# Crea la carpeta images
mkdir images

# Mueve los archivos
mv logo_avanta_principal.png images/
mv habitaciones_avanta.jpg images/
mv politica-privacidad-github.html index.html
```

### Paso 3: Subir archivos a GitHub
```bash
git init
git add .
git commit -m "Política de privacidad Avanta"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
git push -u origin main
```

### Paso 4: Activar GitHub Pages
1. Ve a tu repositorio en GitHub
2. Click en **Settings**
3. Click en **Pages** (menú lateral izquierdo)
4. En "Source", selecciona **main** branch
5. Click **Save**

¡Listo! Tu página estará disponible en:
```
https://TU-USUARIO.github.io/TU-REPO/
```

## 🎨 Características del diseño

- ✅ Diseño 100% fiel a Stitch
- ✅ Responsive (móvil y desktop)
- ✅ Tailwind CSS desde CDN
- ✅ Material Symbols Icons
- ✅ Fuente Plus Jakarta Sans
- ✅ Colores brand de Avanta
- ✅ Header sticky con navegación
- ✅ Footer con enlaces a redes sociales
- ✅ Checkbox funcional con JavaScript
- ✅ Botón "Enviar y Continuar" interactivo

## 🔗 Links incluidos

- WhatsApp: Contacto directo con Ricardo Peña
- Google Maps: Ubicación del hotel
- Instagram: @avanta_hotelqro
- Facebook: /avantahotelqro
- Website: avantahotel.com.mx

## 📝 Personalización

Para personalizar la página, edita:

1. **Dirección del hotel** (línea 74)
2. **Email de privacidad** (línea 131)
3. **Links del footer** (líneas 167-191)

## 💡 Notas técnicas

- **Tailwind CSS**: Cargado desde CDN, no requiere compilación
- **Material Icons**: Íconos de Google Fonts
- **JavaScript**: Validación del checkbox incluida
- **Responsive**: Breakpoints optimizados para móvil

---

**Desarrollado para Avanta Hotel & Villas**  
Diseño original por Stitch (Google)
