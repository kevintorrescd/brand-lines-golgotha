# Brand Lines Golgotha

Repositorio de skills de diseño para reutilizar lineamientos visuales en distintos tipos de entregables.

## Estructura

Cada skill vive dentro de `skills/<nombre-de-skill>/` y mantiene su propio:

- `SKILL.md`
- `agents/openai.yaml`
- `references/`
- `assets/`

## Skills disponibles

| Skill | Uso |
| --- | --- |
| `presentation-pptx` | Crear o adaptar presentaciones PPTX/PowerPoint con la guía visual educativa de Golgotha. |

## Convención para nuevas skills

Usar esta estructura:

```text
skills/
  nombre-de-skill/
    SKILL.md
    agents/
      openai.yaml
    references/
    assets/
```

Mantener cada skill autocontenida: sus referencias, plantillas, paletas e imágenes deben vivir dentro de su propia carpeta.
