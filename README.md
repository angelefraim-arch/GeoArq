# GeoArq — Portafolio profesional

Sitio de una sola página (landing) para el portafolio del Arq. Ángel Martínez, enfocado en servicios de topografía: levantamientos topográficos, curvas de nivel, deslindes, lotificación, replanteo y georreferenciación.

## 🗂 Estructura del proyecto

```
geoarq/
├── index.html          # Página principal
├── assets/
│   ├── css/
│   │   └── style.css   # Estilos del sitio
│   └── img/
│       ├── pagina-01.jpg   # Imágenes del portafolio (páginas 1–11)
│       ├── pagina-02.jpg
│       └── ...
└── README.md
```

> Nota: el archivo original era un único `.html` con las 11 imágenes del portafolio incrustadas en base64. Se extrajeron a `assets/img/` como archivos `.jpg` independientes y el CSS se movió a `assets/css/style.css`, para que el proyecto sea más ligero, fácil de mantener y versionar en Git.

## 🚀 Cómo verlo localmente

Como es HTML/CSS puro (sin build ni dependencias), solo necesitas abrir el archivo en el navegador:

```bash
# Opción 1: abrir directamente
open index.html        # macOS
# o doble clic en index.html

# Opción 2: servirlo con un servidor local (recomendado para rutas relativas)
python3 -m http.server 8000
# luego visita http://localhost:8000
```

## 🌐 Publicarlo con GitHub Pages

1. Sube este repositorio a GitHub.
2. Ve a **Settings → Pages**.
3. En "Branch", selecciona `main` (o `master`) y la carpeta `/ (root)`.
4. Guarda; en un par de minutos tu sitio estará disponible en:
   `https://<tu-usuario>.github.io/<nombre-del-repo>/`

## ✏️ Personalización

- **Contenido / textos:** edita directamente `index.html`.
- **Colores y tipografías:** variables CSS al inicio de `assets/css/style.css` (`--ink`, `--paper`, `--brass`, etc.).
- **Imágenes del portafolio:** reemplaza los archivos en `assets/img/` manteniendo el mismo nombre, o actualiza el atributo `src` en `index.html` si cambias el nombre del archivo.

## 📞 Contacto

- WhatsApp: 477 893 5301
- Correo: arq.angelmartinez0@gmail.com
- Ubicación: León de los Aldama, Guanajuato, México

---

Hecho con HTML y CSS puro. Sin frameworks, sin dependencias, sin build step.
