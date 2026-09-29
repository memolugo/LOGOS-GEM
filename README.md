# LOGOS-GEM

Repositorio con los logos e imagenes de identidad de la **Agencia de Transformacion Digital (ATD)** y del **Gobierno del Estado de Morelos** para poder referenciarlos por URL publica en archivos HTML (en vez de rutas locales tipo `file:///` o `../assets/...` que no se ven al compartir el archivo).

Incluye tanto los assets que mas se reutilizan hoy como variantes adicionales (orientaciones, colores, plecas, membretes, avatares, personificador) pensadas para necesidades futuras: informes, paginas web, invitaciones, nombramientos, oficios/cartas, credenciales y piezas de redes sociales.

## Uso

Cada imagen tiene una URL "raw" estable con este formato:

```
https://raw.githubusercontent.com/memolugo/LOGOS-GEM/master/<carpeta>/<archivo>
```

Ejemplo en HTML:

```html
<img src="https://raw.githubusercontent.com/memolugo/LOGOS-GEM/master/logos/isotipo-atd-solo.png" alt="ATD">
```

## Estructura

### `logos/` — isotipos y logotipos completos

| Archivo | Descripcion |
|---|---|
| `isotipo-atd-solo.png` | Isotipo ATD solo (el mas usado en nombramientos y cartas) |
| `isotipo-atd-color.png` | Isotipo ATD version a color |
| `logo-morelos-atd-reverso.png` | Logo combinado Morelos + ATD, version reverso/blanco |
| `convivencia-morelos-atd-reverso.png` | Logo Morelos + ATD version reverso, usado en invitaciones |
| `cenefa-inferior.png` | Cenefa/franja inferior de identidad |
| `atd-logo-01.png` a `atd-logo-12.png` | Set completo de variantes del logo ATD (colores/fondos distintos) usado en plantillas de informe y web del skill ATD |
| `logo-horizontal-01.png` a `logo-horizontal-06.png` | Set de logo Gobierno Digital en orientacion horizontal, variantes de color |
| `logo-vertical-01.png` a `logo-vertical-06.png` | Set de logo Gobierno Digital en orientacion vertical, variantes de color |

### `plecas/` — franjas/bandas de identidad para redes y documentos

| Archivo | Descripcion |
|---|---|
| `pleca-2025-01.png` a `pleca-2025-06.png` | Set de plecas vigente (marzo 2025) |
| `pleca-2024-01.png` a `pleca-2024-06.png` | Set de plecas anterior (enero 2025), por si algun documento previo lo requiere |

### `membretes/` — hojas membretadas para oficios y cartas

| Archivo | Descripcion |
|---|---|
| `membrete-carta.png` | Hoja membretada tamano carta |
| `membrete-oficio.png` | Hoja membretada tamano oficio |

### `avatares/` — marcos/plantillas de foto de perfil

| Archivo | Descripcion |
|---|---|
| `avatar-marco-2025.png` | Marco editable de foto de perfil, version vigente |
| `avatar-marco-2024.png` | Marco de foto de perfil, version anterior |

### `personificador/` — plantilla de credencial/personificador

| Archivo | Descripcion |
|---|---|
| `personificador-plantilla.png` | Plantilla de personificador (credencial) de Agentes ATD |

## Notas

- Todos los archivos son PNG listos para usarse en `<img src>` o como `background-image` en HTML/CSS.
- Los archivos fuente editables (`.ai`, `.psd`, `.docx`, `.pptx`) se quedan en el proyecto local de diseno; este repo solo contiene los exportados listos para web.
- Cuando se agregue un logo o variante nueva, mantener la convencion de nombres en minusculas con guiones y actualizar esta tabla.
