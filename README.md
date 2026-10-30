# Golden Moments FC

> «Tú diriges el club. Tú decides los momentos que lo cambian todo.»

Golden Moments FC es un mánager de fútbol para PC. La semana se gestiona desde un único panel y el partido se juega solo en sus jugadas clave: entre 6 y 10 jugadas destacadas por partido, de acción arcade en vista isométrica, de 15 a 40 segundos cada una. Lo que preparas en el despacho (táctica, moral, forma física, química) cambia lo que ocurre en cada jugada que controlas.

| | |
| --- | --- |
| **Género** | Mánager de fútbol ligero + acción arcade |
| **Plataforma** | PC (Steam), Windows 10/11, ratón y teclado |
| **Motor** | Unity 6 LTS (URP, UI Toolkit) |
| **Modo** | Un jugador, carrera de mánager |
| **Partidos** | 3–5 minutos reales; temporada completa en 4–6 horas |
| **Modelo** | Premium, sin microtransacciones ni licencias oficiales |
| **Estado** | Documentación de diseño cerrada (octubre de 2026) y prototipo jugable de una semana |

## Índice

### Prototipo

- [Prototipo v9](prototipo-v9.html) · versión actual ([cómo abrirlo](#cómo-abrirlo))
- [Prototipo v8](prototipo-v8.html) · versión anterior, como referencia

### Documentación de diseño

Todos los documentos están en [`documentacion/`](documentacion/).

- **Visión general**: [Contexto](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Contexto.pdf) · [Especificación Master](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Especificaci%C3%B3n%20Master.pdf) · [Roadmap y producción](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Roadmap%20y%20producci%C3%B3n.pdf)
- **Partido**: [Motor de simulación del partido](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Motor%20de%20simulaci%C3%B3n%20del%20partido.pdf) · [Sistema de Jugadas Destacadas](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Sistema%20de%20Jugadas%20Destacadas.pdf) · [Controles y mecánicas (PC)](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Controles%20y%20mec%C3%A1nicas%20%28PC%29.pdf) · [Sistema de tiro y pase](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Sistema%20de%20tiro%20y%20pase.pdf) · [IA de jugadores de campo](documentacion/Golden%20Moments%20FC%20%E2%80%94%20IA%20de%20jugadores%20de%20campo.pdf) · [Alcance y Toma de Decisiones del Portero](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Alcance%20y%20Toma%20de%20Decisiones%20del%20Portero.pdf) · [Balón Parado Portero e IA de Marcaje](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Bal%C3%B3n%20Parado%20Portero%20e%20IA%20de%20Marcaje.pdf) · [Reglamento y árbitro](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Reglamento%20y%20%C3%A1rbitro.pdf)
- **Gestión**: [Gestión de plantilla](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Gesti%C3%B3n%20de%20plantilla.pdf) · [Atributos y fórmulas comunes](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Atributos%20y%20f%C3%B3rmulas%20comunes.pdf) · [Subida de GRL y ADN de Canteranos](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Subida%20de%20GRL%20y%20ADN%20de%20Canteranos.pdf) · [Economía y base de datos de jugadores](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Econom%C3%ADa%20y%20base%20de%20datos%20de%20jugadores.pdf) · [Carrera del mánager](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Carrera%20del%20m%C3%A1nager.pdf) · [Competiciones y mundo](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Competiciones%20y%20mundo.pdf)
- **Presentación**: [UX y flujo de pantallas](documentacion/Golden%20Moments%20FC%20%E2%80%94%20UX%20y%20flujo%20de%20pantallas.pdf) · [Guía de arte, animación y audio](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Gu%C3%ADa%20de%20arte%2C%20animaci%C3%B3n%20y%20audio.pdf) · [Narrativa y presentación](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Narrativa%20y%20presentaci%C3%B3n.pdf)
- **Técnica**: [Arquitectura técnica y guardado](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Arquitectura%20t%C3%A9cnica%20y%20guardado.pdf)
- **Pendientes**: [Documentaciones pendientes](documentacion/Golden%20Moments%20FC%20%E2%80%94%20Documentaciones%20pendientes.docx) (`.docx`)

### Croquis

Todos los croquis están en [`croquis/`](croquis/).

- [Plan del croquis](croquis/Golden%20Moments%20FC%20%E2%80%94%20Plan%20del%20croquis.pdf)
- [Fase 1](croquis/Golden%20Moments%20FC%20%E2%80%94%20Croquis%20fase%201.pdf)
- [Fases 1 y 2](croquis/Golden%20Moments%20FC%20%E2%80%94%20Croquis%20fases%201%20y%202.pdf)
- [Fase 3 (color)](croquis/Golden%20Moments%20FC%20%E2%80%94%20Croquis%20fase%203%20%28color%29.pdf)

### En esta página

- [Prototipo de semana](#prototipo-de-semana)
- [Documentación de diseño](#documentación-de-diseño-1)
- [Croquis](#croquis-1)
- [Hoja de ruta](#hoja-de-ruta)

## Prototipo de semana

Es una semana completa del CD Altamar en un único archivo HTML, sin instalación ni dependencias:

1. **Gestión**: las ocho secciones del menú lateral (Inicio, Plantilla, Táctica, Entrenamiento, Mercado, Competiciones, Mi club y Bandeja de mensajes).
2. **Previa**: charla al equipo antes del partido.
3. **Partido simulado**: narración minuto a minuto con jugadas destacadas que puedes jugar o delegar, y pausa táctica para hacer cambios.
4. **Resumen final** y cierre de la semana.

### Cómo abrirlo

1. Descarga `prototipo-v9.html` y ábrelo en Chrome o Edge, a pantalla completa (1920×1080 o mayor).
2. En la pantalla del moderador, escribe el código del probador y pulsa «Pasar al probador».
3. Juega con ratón y teclado. La tira inferior muestra en cada momento las teclas disponibles.

### Controles principales

| Tecla | Acción |
| --- | --- |
| `Espacio` ×2 | Avanzar (ir al partido, empezar, cerrar la semana) |
| `1`–`8` | Secciones del menú lateral |
| `Esc` | Volver a Inicio; en el partido, pausa táctica |
| `Intro` / `Retroceso` | Jugar o delegar una jugada destacada |
| `WASD` + ratón | Moverte y apuntar en una jugada; clic para pasar, `Espacio` (mantener) para tirar |
| `Ctrl`+`Fin` | Simular el resto del partido |
| `H` | Guía de controles |
| `Ctrl`+`Mayús`+`M` | Barra de medición, con la descarga del CSV de resultados |

### Pruebas con probadores

El prototipo está pensado para sesiones de prueba moderadas. La barra de medición registra tiempo, acciones y tareas de cada semana, y se exporta a CSV. Con la misma semilla, dos probadores reciben los mismos sucesos. El prototipo no guarda la partida: al recargar la página empieza de nuevo.

### Historial

- **v9** (30 oct 2026): si dejas ir a un jugador en su renovación («Dejar que se vaya»), su renovación ya no vuelve a salir como urgente en semanas posteriores. Ahora llegan las siguientes de la lista (Ferrer en la semana 5, Ibarra en la 6).
- **v8** (29 oct 2026): versión anterior, que se conserva como referencia.

## Documentación de diseño

Si dos documentos no coinciden, manda **Atributos y fórmulas comunes** para atributos, fórmulas y constantes, y la **Especificación Master** para todo lo demás.

| Área | Documentos |
| --- | --- |
| Visión general | Contexto · Especificación Master · Roadmap y producción |
| Partido | Motor de simulación del partido · Sistema de Jugadas Destacadas · Controles y mecánicas (PC) · Sistema de tiro y pase · IA de jugadores de campo · Alcance y Toma de Decisiones del Portero · Balón Parado Portero e IA de Marcaje · Reglamento y árbitro |
| Gestión | Gestión de plantilla · Atributos y fórmulas comunes · Subida de GRL y ADN de Canteranos · Economía y base de datos de jugadores · Carrera del mánager · Competiciones y mundo |
| Presentación | UX y flujo de pantallas · Guía de arte, animación y audio · Narrativa y presentación |
| Técnica | Arquitectura técnica y guardado |
| Pendientes | Documentaciones pendientes (`.docx`) |

## Croquis

En [`croquis/`](croquis/) están el plan del croquis y los croquis de pantallas, que siguen el flujo del documento UX y flujo de pantallas: 15 pantallas en 3 fases, primero la estructura en gris (fases 1 y 2) y después la capa de color (fase 3).

## Hoja de ruta

| Hito | Fecha objetivo | Qué incluye |
| --- | --- | --- |
| Documentación cerrada | Octubre de 2026 | Todos los documentos de diseño |
| Vertical slice | Marzo de 2027 | 1 liga de 20 clubes, 1 temporada, 5 tipos de jugada destacada |
| Demo de Steam Next Fest | Junio de 2027 | Partido de exhibición, temporada corta, tutorial, 8 tipos de jugada destacada |
| Acceso Anticipado | Noviembre de 2027 | Carrera completa con 40 ligas y 800 clubes |
| Versión 1.0 | Mayo de 2028 | Steam Workshop con editor, inglés, logros de Steam, balance final |

El detalle está en *Roadmap y producción*.

## Autor

Diseño y desarrollo: Andoni Prieto.
