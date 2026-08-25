# Surco — Sitio sobre coleccionismo de vinilos

Proyecto para el Taller 2 (Consigna trabajo práctico HTML). Sitio estático de 3 páginas hecho con HTML, CSS y Bootstrap 5.

## Estructura

```
vinilos-site/
├── index.html        Página de inicio
├── coleccion.html     Página de contenido (guía en profundidad)
├── contacto.html       Página de contacto (formulario solo de diseño)
├── css/
│   └── styles.css      Estilos personalizados
└── images/
    ├── vinyl-record.svg
    └── turntable.svg
```

## Cómo verlo

Abrí `index.html` en el navegador (doble clic alcanza, no necesita servidor).

## Requisitos técnicos cubiertos

- 3 páginas interconectadas con navegación común (`index.html`, `coleccion.html`, `contacto.html`).
- 2 imágenes propias (`images/vinyl-record.svg`, `images/turntable.svg`).
- Listas ordenadas y desordenadas en `coleccion.html`.
- Enlace externo a Discogs y enlaces internos entre las 3 páginas.
- CSS personalizado con más de tres clases propias (`.label-chip`, `.groove-divider`, `.sleeve-card`, `.vinyl-record`, etc.), tipografía (Fraunces / Inter / Space Mono), colores de fondo y transición/efecto visual (disco que gira al pasar el mouse, hover en tarjetas y botones).
- Bootstrap 5 para el grid, la navbar responsiva y el formulario.
- Diseño responsivo (probado en mobile y escritorio con las clases de grilla de Bootstrap).

## Subir a GitHub (control de versiones)

Desde esta carpeta:

```bash
git init
git add index.html css images README.md
git commit -m "Creación de estructura HTML"

git add coleccion.html contacto.html
git commit -m "Agregado de CSS y páginas de contenido"

git add css/styles.css
git commit -m "Estilizado final con Bootstrap"

git branch -M main
git remote add origin <URL-de-tu-repositorio>
git push -u origin main
## Autor
Proyecto realizado por Heredia Said
```

Ajustá el orden y el contenido de los commits a como realmente fuiste trabajando.
