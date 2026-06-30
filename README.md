# Mi Presupuesto — App de control de gastos

App web progresiva (PWA) para controlar gastos diarios y presupuesto anual.
Funciona en Android como app instalada, con datos guardados en el teléfono.

## Archivos necesarios

| Archivo | Descripción |
|---|---|
| `index.html` | La app completa (auto-contenida) |
| `manifest.json` | Configuración PWA |
| `sw.js` | Service worker (offline) |
| `icon-192.png` | Ícono app Android |
| `icon-512.png` | Ícono splash screen |

## Paso a paso — GitHub Pages

### 1. Crear el repositorio
1. Ve a [github.com](https://github.com) → **New repository**
2. Nombre: `mi-presupuesto` (o el que quieras)
3. Marca **Public** (necesario para GitHub Pages gratis)
4. Clic en **Create repository**

### 2. Subir los archivos
1. En tu nuevo repo → clic en **Add file → Upload files**
2. Arrastra los 5 archivos: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`
3. Clic en **Commit changes**

### 3. Activar GitHub Pages
1. En el repo → **Settings** → **Pages** (menú izquierdo)
2. En "Source" selecciona **Deploy from a branch**
3. Branch: **main** · Folder: **/ (root)**
4. Clic en **Save**
5. Espera ~1 minuto → aparece tu URL: `https://TU_USUARIO.github.io/mi-presupuesto/`

### 4. Instalar en Android
1. Abre Chrome en tu Android
2. Ve a tu URL de GitHub Pages
3. Chrome muestra un banner **"Agregar Mi Presupuesto a pantalla de inicio"** → toca **Instalar**
4. ¡Listo! Aparece el ícono azul "$" en tu pantalla de inicio

## Características
- ✅ Funciona offline (service worker)
- ✅ Datos guardados en el teléfono (localStorage)
- ✅ Gastos diarios con categorías y medios de pago
- ✅ Presupuesto mensual/semanal/anual editable
- ✅ Importa Excel (.xlsx) con tus gastos
- ✅ Conciliación bancaria (Amex, CommBank, NAB, Santander)
- ✅ Seguimiento anual con balance de caja
- ✅ Moneda AUD / CLP

## Actualizar la app
Cuando quieras actualizar con cambios:
1. Sube el nuevo `index.html` al repo (drag & drop → commit)
2. GitHub Pages se actualiza automáticamente en ~1 min
3. En Android, cierra y vuelve a abrir la app
