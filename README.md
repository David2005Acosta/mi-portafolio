# Portafolio de David Acosta

Página personal con mis datos, habilidades y proyectos. Es un sitio estático
hecho con HTML y CSS, sin frameworks ni proceso de build.

**Demo:** _pendiente de desplegar en Vercel_

## Estructura

```
mi-portafolio/
├── index.html      # Contenido de la página
├── styles.css      # Estilos
├── assets/
│   ├── avatar.svg  # Iniciales (se puede cambiar por una foto)
│   └── favicon.svg # Icono de la pestaña
└── README.md
```

## Verlo en local

Abre `index.html` en el navegador o levanta un servidor local:

```bash
python -m http.server 5500
```

Y visita <http://localhost:5500>.

## Cambiar el contenido

- **Foto:** reemplaza `assets/avatar.svg` por una foto cuadrada y actualiza el
  `src` de la imagen en `index.html`.
- **Proyectos:** cada proyecto es un `<li>` dentro de `.projects`. Copia uno y
  cambia el título, la descripción, las tecnologías y el enlace.
- **LinkedIn:** se puede añadir junto al correo y GitHub en la sección de
  contacto.
- **Colores:** están definidos al inicio de `styles.css`, en `:root`.

## Despliegue

El proyecto está pensado para Vercel: se importa el repositorio desde GitHub y
Vercel lo publica como sitio estático. Cada `push` a `main` actualiza la misma
URL automáticamente.

## Licencia

Contenido personal © David Acosta.