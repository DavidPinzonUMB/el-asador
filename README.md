# Empresa de Cárnicos

Sitio web de **Empresa de Cárnicos S.A.S**, carnicería gourmet especializada en cortes madurados y seleccionados. Presenta la propuesta de valor, el catálogo de cortes, información de contacto y una galería corporativa.

🌐 **Sitio publicado:** <https://davidpinzonumb.github.io/EmpresaDeCarnicos/>  
📦 **Repositorio:** <https://github.com/DavidPinzonUMB/EmpresaDeCarnicos>

---

## Páginas del sitio

| Página | Archivo | Descripción |
|---|---|---|
| Inicio | [`index.html`](index.html) | Bienvenida, propuesta de valor y estándares de calidad. |
| Cortes | [`productos.html`](productos.html) | Catálogo completo de cortes premium con precios. |
| Galería | [`galeria.html`](galeria.html) | Galería corporativa con maduración, despiece y empaque. |
| Contacto | [`contacto.html`](contacto.html) | Datos de contacto y formulario para pedidos. |

## Estructura del proyecto

```
EmpresaDeCarnicos/
├── index.html         # Página principal
├── productos.html     # Catálogo de cortes
├── contacto.html      # Contacto
├── galeria.html       # Galería corporativa
├── css/
│   └── styles.css     # Hoja de estilos común
├── img/               # Imágenes
└── README.md
```

## Tecnologías

- **HTML5 semántico** (`<html lang="es-CO">`, `<meta charset="utf-8">`).
- **CSS3** sin frameworks: variables CSS, Grid y Flexbox.
- Tipografías Google Fonts: **Playfair Display** (títulos) e **Inter** (cuerpo).
- Diseño responsive (escritorio, tableta y móvil).

## Cómo ver el sitio

### En línea
Abrir <https://davidpinzonumb.github.io/EmpresaDeCarnicos/> en el navegador.

### Localmente

```bash
git clone https://github.com/DavidPinzonUMB/EmpresaDeCarnicos.git
cd EmpresaDeCarnicos
start index.html        # Windows
# open index.html       # macOS
# xdg-open index.html   # Linux
```

No requiere servidor ni dependencias.

## Proceso de desarrollo

El sitio se construyó con un flujo profesional de **ramas + pull requests**, una sección por rama:

| Sección | Rama |
|---|---|
| Catálogo de cortes | `feature/catalogo` |
| Página de contacto | `feature/contacto` |
| Galería corporativa | `feature/galeria` |

Cada rama se desarrolló por separado, se subió al remoto y se integró a `main` mediante un pull request, manteniendo `main` siempre publicable.

```bash
git checkout -b feature/nueva-seccion
git add .
git commit -m "feat: descripción del cambio"
git push origin feature/nueva-seccion
# Abrir Pull Request en GitHub y, tras revisión, hacer merge a main
```

## Publicación

El sitio se publica con **GitHub Pages** desde la rama `main` (carpeta raíz). Cada `push` a `main` actualiza el sitio en línea.

Para activarlo:
1. **Settings → Pages** del repositorio.
2. En **Source** elegir `main` y `/ (root)`.
3. Guardar y esperar a que GitHub genere la URL pública.
