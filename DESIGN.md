---
version: alpha
name: "Fat&Go"
description: "Cadena de comida rápida retro, rotunda y deliberadamente cutre, resuelta con una composición limpia."
colors:
  primary: "#1D1A16"
  secondary: "#D1261B"
  accent: "#F5B82E"
  background: "#F4E6C5"
  surface: "#FFF7DF"
typography:
  display:
    fontFamily: "Arial Black, Arial, Helvetica, sans-serif"
    fontSize: 7.5rem
    fontWeight: 900
    lineHeight: 0.8
    letterSpacing: "-0.075em"
  label:
    fontFamily: "Courier New, Courier, monospace"
    fontSize: 0.75rem
    fontWeight: 900
    lineHeight: 1.4
    letterSpacing: "0.08em"
rounded:
  none: 0px
  pill: 999px
spacing:
  sm: 8px
  md: 16px
  lg: 32px
components:
  page:
    backgroundColor: "{colors.background}"
    textColor: "{colors.primary}"
    typography: "{typography.display}"
    rounded: "{rounded.none}"
    padding: 16px
  ticket:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.secondary}"
    typography: "{typography.display}"
    rounded: "{rounded.none}"
    padding: 32px
  highlight:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.primary}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: 8px
---

## Overview

Fat&Go imita una cadena de comida rápida de los años 90/2000 venida a menos. El acabado debe ser intencionado: marca cutre, diseño sólido. Cada bloque necesita una función; evita decoración de relleno.

## Colors

- **Tinta:** texto, bordes y sombras duras.
- **Rojo:** marca y énfasis principal.
- **Amarillo:** avisos y acentos puntuales.
- **Crema:** fondo general con textura ligera.
- **Papel:** tarjetas y superficies de lectura.

Mantén las combinaciones actuales de alto contraste. No añadas degradados, transparencias ni colores nuevos sin una necesidad clara.

## Typography

- **Titulares:** Arial Black o su cadena de respaldo; grandes, compactos y en mayúsculas.
- **Etiquetas:** Courier New para tickets, expedientes y mensajes operativos.

Usa como máximo estas dos voces tipográficas: sans pesada y monoespaciada.

## Layout

Composición editorial, directa y responsive. Un foco principal por sección, separación generosa y rejillas que pasan de tres a dos y una columna. El contenido debe funcionar desde 320 px sin desbordamiento horizontal.

## Elevation & Depth

Usa bordes negros gruesos y sombras sólidas desplazadas. No uses desenfoques, cristal ni sombras suaves.

## Shapes

Predominan rectángulos, círculos y píldoras. Las rotaciones leves aportan carácter; no deben perjudicar la lectura ni provocar recortes.

## Components

Los tickets contienen mensajes principales; las etiquetas negras o amarillas aportan contexto breve; las fichas ejecutivas usan papel, borde grueso y sombra dura. No conviertas cada texto en una tarjeta.

## Do's and Don'ts

- **Sí:** humor corporativo absurdo, jerarquía fuerte, espacios limpios y movimiento discreto.
- **Sí:** respetar `prefers-reduced-motion` y contraste WCAG AA.
- **Sí:** validar cada cambio visual en un navegador real, en escritorio y móvil, antes de publicarlo.
- **No:** iconos decorativos, métricas inventadas, degradados, cristal, bloques redundantes o animaciones sin función.
- **No:** añadir secciones o mensajes solo para llenar espacio.