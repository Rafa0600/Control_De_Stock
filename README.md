# Mikra - Control de Stock (PWA)

App instalable para control de stock de Mikra.

## Cómo subir a GitHub Pages (paso a paso)

### 1. Crear repositorio
- Ir a [github.com/new](https://github.com/new)
- Nombre: `mikra-stock` (o el que quieras)
- Marcar **Public**
- Click en **Create repository**

### 2. Subir archivos
- En el repo vacío, click en **"uploading an existing file"**
- Arrastrá TODOS estos archivos:
  - `index.html`
  - `manifest.json`
  - `sw.js`
  - `icon-192.png`
  - `icon-512.png`
- Click en **Commit changes**

### 3. Activar GitHub Pages
- Ir a **Settings** → **Pages** (en el menú izquierdo)
- Source: **Deploy from a branch**
- Branch: **main** → carpeta **/ (root)**
- Click **Save**
- Esperá 1-2 minutos

### 4. Tu URL será:
```
https://TU-USUARIO.github.io/mikra-stock/
```

### 5. Instalar en el celular
- **Android (Chrome):** Entrá a la URL → aparece banner "Agregar a inicio" o menú ⋮ → "Instalar app"
- **iPhone (Safari):** Entrá a la URL → botón compartir → "Agregar a inicio"

## Actualizar versión
Cuando subas un HTML nuevo, cambiá `CACHE_NAME = 'mikra-stock-v2'` en `sw.js` para forzar la actualización del caché.
