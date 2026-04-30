# Fundamentos de Redacción Audiovisual

Web de recursos docentes para las clases de edición de vídeo con DaVinci Resolve 19 y Adobe Premiere Pro.

## Web publicada

[aritzuma.github.io/Fundamentos_Redaccion](https://aritzuma.github.io/Fundamentos_Redaccion)

## Estructura del repositorio

```
Fundamentos_Redaccion/
├── .github/workflows/publish.yml
├── .gitignore
├── _quarto.yml
├── styles.css
├── index.qmd
├── recursos.qmd
├── README.md
├── davinci/
│   ├── intro.qmd
│   └── practica1.qmd
└── Recuros/            # No subir — archivos grandes ignorados por .gitignore
```

## Material de las prácticas

Los archivos de vídeo y audio se distribuyen por SwissTransfer o a través de la carpeta de la asignatura en los ordenadores del aula. No están incluidos en el repositorio por su tamaño.

## Desarrollo local

```r
quarto::quarto_render()
quarto::quarto_preview()
```

## Publicación

La web se publica automáticamente en GitHub Pages mediante GitHub Actions cada vez que se hace push a la rama main.
