# Guia visual para presentaciones educativas

Esta guia define el sistema visual para crear presentaciones consistentes con las muestras y capturas compartidas. El texto de los documentos no es relevante; la guia se basa en color, estructura, jerarquia, espaciado, cards, tablas, etiquetas y tratamientos de evaluacion.

## 1. Direccion visual

El estilo debe sentirse limpio, academico, moderno y muy legible. La presentacion no debe verse decorativa: debe verse como material docente bien construido, con estructura clara y lectura rapida.

Palabras clave:

- Claro
- Docente
- Minimalista
- Ordenado
- Evaluativo
- Practico
- Profesional

Evitar:

- Marfil, beige o tonos crema.
- Dorado, azul o teal como colores del sistema.
- Gradientes decorativos.
- Sombras pesadas.
- Fondos oscuros.
- Paletas con demasiados colores.
- Ilustraciones o iconos multicolor sin necesidad.

## 2. Paleta cromatica oficial

Esta es la paleta base. No agregar colores nuevos salvo que haya una razon funcional muy clara.

| Uso | Hex | Regla |
| --- | --- | --- |
| Fondo de diapositiva | `#F8FAFC` | Fondo principal de la mayoria de slides |
| Titulo principal | `#000000` | Portadas y titulos de gran impacto |
| Titulos | `#111111` | Titulos de seccion, cards, tablas y preguntas |
| Texto / cuadros de texto | `#4B5563` | Parrafos, descripciones y texto secundario |
| Verde principal | `#059669` | Acentos, lineas, iconos, respuesta correcta |
| Verde 47% aprox. | `#7FD5B5` | Fondos de subtitulos/pills cuando se necesita mas presencia |
| Verde muy suave | `#ECFDF5` | Fondo de cards positivas o bloques correctos |
| Borde de cards | `#E5E7EB` | Bordes de cards, opciones y divisores |
| Fondo de cards | `#FFFFFF` | Cards, tablas y bloques de respuesta |
| Error / negacion | `#FF4444` | Negaciones, respuestas incorrectas, alertas |
| Fondo de error suave | `#FEF2F2` | Cards de claves, errores o advertencias |
| Fondo de bloque neutro | `#F3F4F6` | Textos largos, lectura, tablas o celdas alternas |

![Paleta visual](output/paleta-guia-visual.png)

### Proporciones

- 80% fondos claros: `#F8FAFC`, `#FFFFFF`, `#F3F4F6`.
- 15% verde: `#059669`, `#7FD5B5`, `#ECFDF5`.
- 5% rojo: solo para error, negacion o distractores.

### No usar

- Marfil / beige.
- Dorado.
- Azul.
- Teal.
- Morados.
- Gradientes.

## 3. Tipografia

El sistema usa sans serif pesada para titulos y sans serif limpia para lectura.

Recomendacion:

- Titulos principales: `Montserrat ExtraBold`, `Inter ExtraBold`, `Aptos Display Bold` o `Arial Black`.
- Titulos internos: `Montserrat Bold`, `Inter Bold`, `Aptos Display Bold`.
- Cuerpo: `Inter`, `Aptos`, `Segoe UI`, `Arial`.

Jerarquia para formato 16:9:

| Elemento | Tamano | Peso | Color |
| --- | ---: | --- | --- |
| Portada | 50-68 pt | 800-900 | `#000000` |
| Titulo de slide | 30-42 pt | 800 | `#111111` |
| Pregunta principal | 18-24 pt | 700-800 | `#111111` |
| Titulo de card | 14-20 pt | 700-800 | `#111111` o `#059669` |
| Cuerpo | 12-17 pt | 400-500 | `#4B5563` |
| Etiquetas/pills | 8-11 pt | 700-800 | `#059669` |

Reglas:

- Titulos grandes, negros y contundentes.
- Texto secundario siempre mas liviano y en `#4B5563`.
- Mayusculas solo en portadas, etiquetas y titulos muy especificos.
- Interlineado amplio en textos largos.
- No justificar textos.

## 4. Espaciado y composicion

Formato base: 16:9 horizontal.

Margenes recomendados:

- Margen exterior general: 56-80 px.
- Margen para slides de lectura/evaluacion: 72-96 px.
- Separacion entre cards: 16-24 px.
- Padding interno de cards: 22-28 px.
- Separacion titulo-contenido: 28-48 px.

Reticula:

- Usar alineacion izquierda como norma.
- Usar composicion centrada solo en portadas de pausa o slides de una sola pregunta.
- Mantener mucho aire visual.
- Una diapositiva debe comunicar una funcion: concepto, lectura, pregunta, retroalimentacion, tabla o portada.

## 5. Componentes principales

### Cards

Las cards son el componente base del sistema.

Especificacion:

- Fondo normal: `#FFFFFF`.
- Fondo positivo: `#ECFDF5`.
- Fondo de error/clave negativa: `#FEF2F2`.
- Borde: `#E5E7EB`.
- Borde positivo: verde suave o `#059669` con opacidad baja.
- Radio: 8-12 px.
- Sombra: ninguna o casi imperceptible.
- Padding: 22-28 px.

Uso:

- Grid 2x2 de conceptos.
- Opciones de respuesta.
- Bloques de retroalimentacion.
- Comparaciones.
- Resumenes cortos.

Regla de contenido:

- Titulo corto.
- 1 a 3 lineas de explicacion.
- Palabras clave en negrita.
- No meter parrafos largos dentro de cards pequenas.

### Pills o bandas superiores

Sirven para identificar item, caso, area, nivel o retroalimentacion.

Especificacion:

- Fondo: `#7FD5B5` con opacidad aproximada al 47%, o equivalente visual `#CFF8E2`.
- Texto: `#059669`.
- Forma: pill horizontal con radio alto.
- Altura: 22-30 px.
- Texto en mayusculas, tracking moderado.

Uso tipico:

- `ITEM 1`
- `CASO 3`
- `AREA 1`
- `RETROALIMENTACION ITEM 3`

### Linea de acento

La linea verde es una firma visual del sistema.

Especificacion:

- Color: `#059669`.
- Grosor: 3-5 px.
- Largo: 45-90 px.
- Ubicacion: al lado derecho del titulo o como borde izquierdo de un bloque.

Usos:

- Despues de titulos: `Responsabilidades e Instrumentos  ____`
- Borde izquierdo de textos largos.
- Borde izquierdo de retroalimentacion correcta.

### Bloques de lectura

Para textos largos, usar una caja neutra con borde verde izquierdo.

Especificacion:

- Fondo: `#F3F4F6` o `#FFFFFF`.
- Borde izquierdo: `#059669`, 4-5 px.
- Radio: 8-10 px.
- Padding: 32-48 px.
- Texto: negro o `#111111` si es lectura principal; `#4B5563` si es explicacion.

### Tablas

Las tablas deben verse limpias, no como hojas de calculo.

Especificacion:

- Fondo tabla: `#FFFFFF` o muy cercano.
- Encabezado: `#F8FAFC`.
- Linea bajo encabezado: `#059669`, 2-3 px.
- Celdas alternas: `#F3F4F6` o un gris neutro muy suave dentro de la misma familia.
- Bordes internos: minimo uso, preferir separacion por fondo.
- Texto de encabezado: `#111111`, bold.
- Texto de celda: `#4B5563`.

## 6. Iconografia e imagenes

Iconos:

- Usar iconos solidos o lineales simples.
- Color normal: `#111111`.
- Color de accion/positivo: `#059669`.
- Color de error: `#FF4444`.
- Evitar iconos en azul, dorado o teal.

Imagenes:

- Se permiten fotografias solo cuando funcionan como contexto real, por ejemplo una portada de area con imagen lateral.
- La imagen debe ocupar un bloque grande y limpio, no una miniatura decorativa.
- Usar fotos luminosas, educativas y reales.
- No aplicar filtros fuertes.

## 7. Layouts reutilizables

### A. Portada fuerte sin imagen

Uso: titulo principal de presentacion o modulo.

Estructura:

- Fondo `#F8FAFC`.
- Titulo enorme en negro, alineado a la izquierda.
- Subtitulo en `#4B5563`.
- Mucho espacio vacio.
- Sin cards.

### B. Portada con imagen lateral

Uso: areas, bloques tematicos o secciones institucionales.

Estructura:

- Fondo blanco o `#F8FAFC`.
- Columna izquierda con pill, titulo y subtitulo.
- Imagen a la derecha ocupando 45-50% del ancho.
- Titulo en negro, subtitulo en `#4B5563`.

### C. Grid 2x2 de conceptos

Uso: explicar familias de ideas.

Estructura:

- Cuatro cards.
- Cards normales en blanco.
- Una card positiva puede usar `#ECFDF5`.
- Una card de alerta puede usar `#FEF2F2`.
- Icono al inicio del titulo.
- Titulos negros, verdes o rojos segun funcion.

### D. Pregunta de simulacro

Uso: item con opciones.

Estructura:

- Pill superior larga: `ITEM X`.
- Pregunta debajo en `#111111`.
- Divisor horizontal `#E5E7EB`.
- Opciones como cards blancas con borde `#E5E7EB`.
- Letra de opcion dentro de chip gris `#F3F4F6`.

### E. Retroalimentacion

Uso: explicar respuesta correcta y distractores.

Estructura:

- Pill superior larga: `RETROALIMENTACION ITEM X`.
- Bloque correcto en `#ECFDF5`.
- Borde izquierdo verde `#059669`.
- Dos columnas debajo:
  - Por que es correcta.
  - Por que las otras no son correctas.
- Letras incorrectas en `#FF4444`.

### F. Lectura o caso

Uso: presentar texto base.

Estructura:

- Pill superior: `CASO X`.
- Titulo grande negro.
- Caja de lectura neutra.
- Borde izquierdo verde.
- Parrafos con interlineado amplio.

### G. Tabla comparativa

Uso: responsabilidades, instrumentos, evaluacion o aplicacion.

Estructura:

- Titulo grande con linea verde a la derecha.
- Tabla ancha centrada.
- Encabezado fuerte.
- Linea verde bajo encabezado.
- Celdas alternas suaves.

## 8. Reglas de uso del color

- Verde significa estructura, avance, respuesta correcta o categoria activa.
- Rojo significa error, negacion, distractor o alerta.
- Gris significa lectura, soporte, cuerpo o informacion secundaria.
- Blanco significa unidad de informacion: card, opcion, tabla o bloque.
- Negro significa jerarquia alta.

No usar colores solo para decorar. Cada color debe tener una funcion.

## 9. Checklist antes de exportar

- El fondo principal es `#F8FAFC` o blanco.
- No aparece marfil, dorado, azul ni teal.
- Los titulos son negros y fuertes.
- El texto secundario usa `#4B5563`.
- Las cards tienen fondo blanco y borde `#E5E7EB`.
- Los subtitulos tipo pill usan verde suave.
- La respuesta correcta usa verde.
- La negacion o error usa `#FF4444`.
- Hay suficiente aire alrededor de los bloques.
- Las tablas tienen linea verde bajo el encabezado.
- Los textos largos estan en cajas amplias, no en cards pequenas.

## 10. Tokens rapidos

```css
:root {
  --slide-bg: #f8fafc;
  --title-main: #000000;
  --title: #111111;
  --text: #4b5563;
  --primary: #059669;
  --primary-47: rgba(5, 150, 105, 0.47);
  --primary-soft: #ecfdf5;
  --border: #e5e7eb;
  --card-bg: #ffffff;
  --error: #ff4444;
  --error-soft: #fef2f2;
  --neutral-block: #f3f4f6;
  --radius-card: 10px;
  --slide-padding-x: 72px;
  --slide-padding-y: 56px;
}
```

## 11. Muestras de referencia

La guia queda alineada a estas estructuras visuales:

- Portada fuerte con fondo `#F8FAFC`, titulo negro enorme y subtitulo gris.
- Grid 2x2 de cards blancas, verdes y rojas suaves.
- Preguntas con pill superior verde, opciones en cards blancas y chips grises.
- Retroalimentacion con bloque correcto verde suave y borde izquierdo verde.
- Casos de lectura con caja gris clara y borde verde.
- Tablas anchas con encabezado limpio, linea verde y celdas alternas.
- Portadas con imagen lateral para secciones o areas.
