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

## Contenido del repositorio

```
.
├── prototipo-v9.html     Prototipo jugable de una semana (versión actual)
├── prototipo-v8.html     Versión anterior del prototipo, como referencia
├── documentacion/        Documentos de diseño del juego (PDF)
└── croquis/              Plan del croquis y croquis de pantallas (PDF)
```

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

Todos los documentos están en [`documentacion/`](documentacion/). Si dos documentos no coinciden, manda **Atributos y fórmulas comunes** para atributos, fórmulas y constantes, y la **Especificación Master** para todo lo demás.

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
