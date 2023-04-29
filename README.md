# SVG Icons

Scripts para generar un mapa de SVG para reutilizar iconos en web. En un mismo fichero tendremos varios iconos svg en etiquetas `<symbol>` con `id` correspondiente.

Para utilizarlos, sólo tendremos que hacer lo siguiente:

```html
<svg>
  <use href="logos.svg#twitch" />
</svg>
```

## Requisitos

- [svgo](https://github.com/svg/svgo)
- sed

## Uso

```bash
# Optimiza una imagen
optimize original.svg optimized.svg

# Crea un mapa de SVG con todos los iconos de la carpeta
create folder

# Script listo para nuestro caso
generate
```
