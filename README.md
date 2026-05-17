# 🏔️ Hostal [Nombre] — Landing Page

Sitio web promocional para **Hostal [Nombre]**, ubicado en la zona de páramo de [Municipio], [Departamento], Colombia. Diseñado con una estética oscura y editorial inspirada en la niebla y el paisaje de frailejones.

---

## 📁 Estructura del proyecto

```
hostal-paramo/
├── index.html        # Archivo principal (HTML + CSS + JS en un solo archivo)
├── /img              # Carpeta recomendada para tus imágenes
│   ├── hero.jpg
│   ├── about.jpg
│   ├── gallery-1.jpg
│   └── ...
└── README.md
```

---

## 🗂️ Secciones de la landing

| Sección | Descripción |
|---|---|
| **Nav** | Barra de navegación fija con scroll suave |
| **Hero** | Portada con imagen principal, título y estadísticas |
| **Marquee** | Banda animada con palabras clave del páramo |
| **About** | Historia y características del hostal |
| **Galería** | Grid tipo mosaico con 5 imágenes |
| **Perks** | Lista de beneficios y actividades |
| **Habitaciones** | Cards con imagen, descripción y precio |
| **Banner** | Imagen de impacto a pantalla completa |
| **Contacto** | Info, botón de WhatsApp y formulario |
| **Footer** | Links a redes sociales y créditos |

---

## ✏️ Cómo personalizar

### 1. Textos y nombre
Busca y reemplaza en `index.html`:

```
NOMBRE DEL HOSTAL   →  nombre real del hostal
[NOMBRE]            →  municipio, vereda o departamento
[Departamento]      →  departamento real
20XX                →  año de fundación
```

### 2. Imágenes
Reemplaza cada `url('TU-IMAGEN-*.jpg')` por la ruta de tu foto:

```html

background-image: url('TU-IMAGEN-HERO.jpg')


background-image: url('img/hero.jpg')
```

| Variable | Descripción |
|---|---|
| `TU-IMAGEN-HERO.jpg` | Imagen principal del hero |
| `TU-IMAGEN-ABOUT.jpg` | Foto del entorno / frailejones |
| `TU-IMAGEN-ACCENT.jpg` | Detalle interior del hostal |
| `TU-IMAGEN-PERKS.jpg` | Foto de actividad / experiencia |
| `TU-IMAGEN-BANNER.jpg` | Imagen de fondo del banner grande |
| `TU-IMAGEN-G1` a `G5` | Fotos de la galería |
| `TU-IMAGEN-HAB1` a `HAB3` | Fotos de habitaciones |

### 3. WhatsApp
Busca esta línea y cambia el número (sin `+`, con código de país):

```html
href="https://wa.me/573000000000?text=..."
