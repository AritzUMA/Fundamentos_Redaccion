# 🎬 Edición de Vídeo

Web de recursos docentes para las clases de edición de vídeo con **DaVinci Resolve 19** y **Adobe Premiere Pro**.

## 🌐 Ver la web

**[aritzuma.github.io/edicion-video](https://aritzuma.github.io/edicion-video)**

## 📁 Estructura

```
edicion-video/
├── index.qmd          # Página de inicio
├── styles.css         # Estilos personalizados
├── _quarto.yml        # Configuración de Quarto
├── davinci/
│   ├── intro.qmd      # Introducción a DaVinci Resolve
│   └── practica1.qmd  # Práctica 1 — Anuncio BMW
├── premiere/
│   └── intro.qmd      # Introducción a Premiere Pro
└── recursos.qmd       # Recursos y herramientas
```

## 🛠️ Desarrollo local

```r
# Renderizar localmente
quarto::quarto_render()

# O desde terminal
quarto render
quarto preview
```

## 🚀 Publicar en GitHub Pages

```bash
quarto publish gh-pages
```

## 📋 Contenido actual

- ✅ Práctica 1 — Anuncio BMW (DaVinci Resolve)
- ✅ Introducción a DaVinci Resolve
- 🔄 Introducción a Premiere Pro (en desarrollo)
