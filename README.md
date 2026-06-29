# Nerea Pérez — Personal CV Website

## 🚀 Publicar en GitHub Pages

1. Crea un repositorio en GitHub llamado `nerea-perez-cv` (o el nombre que quieras)
2. Sube todos los archivos de esta carpeta al repositorio
3. Ve a **Settings → Pages → Source** y selecciona la rama `main` y carpeta `/ (root)`
4. Tu web estará disponible en `https://tuusuario.github.io/nerea-perez-cv`

> **Tip**: Si nombras el repositorio `tuusuario.github.io` (ej. `nereaperez.github.io`), la URL será directamente `https://nereaperez.github.io`

---

## 📸 Añadir tu foto de perfil

1. Guarda tu foto con el nombre **`profile.jpg`** en la carpeta `assets/img/`
2. Abre `index.html` y busca el comentario:
   ```html
   <!-- AÑADE TU FOTO AQUÍ -->
   ```
3. Reemplaza esta línea:
   ```html
   <div class="photo-placeholder">NP</div>
   ```
   Por:
   ```html
   <img src="assets/img/profile.jpg" alt="Nerea Pérez">
   ```

---

## 🗂️ Estructura de archivos

```
nerea-cv/
├── index.html          ← La web completa (CSS + JS incluidos)
├── README.md           ← Este archivo
└── assets/
    └── img/            ← Coloca tus imágenes aquí
        ├── profile.jpg          (tu foto de perfil)
        └── ... (cualquier otra imagen opcional)
```

---

## 🌐 Dominio personalizado (opcional)

Si tienes un dominio propio (ej. `nereaperez.com`):
1. Crea un archivo `CNAME` en la raíz con solo el dominio: `nereaperez.com`
2. En tu proveedor de DNS, apunta el dominio a `185.199.108.153`
3. En GitHub Pages → Settings, añade el dominio personalizado

---

*Diseño personalizado · No uses plantillas — este es tuyo.*
