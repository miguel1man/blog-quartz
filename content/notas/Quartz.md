---
title: "Guía Quartz"
tags:
  - Markdown
  - YAML
---

## Enlaces Markdown

```markdown
// Texto a mostrar igual al nombre del archivo
[[nombre-del-archivo]]

// Texto personalizado
[[nombre-del-archivo|Texto a mostrar]]

// Imagen
![texto-alternativo](/notas/imagenes/foto1.jpg)

// Imagen con texto descriptivo
![texto-alternativo](/notas/imagenes/foto2.jpg)_Texto_descriptivo_
```

## YAML front matter

```yaml
---
title: "Título del artículo"
date: 2099-12-31
enableToc: true
draft: true
tags:
  - etiqueta 1
  - etiqueta-2
---
```

## Enlaces a etiquetas de Quartz

```markdown
// Etiqueta específica
[Texto personalizado](/tags/etiqueta1)

// Todas las etiquetas
[Texto personalizado](/tags)
```
