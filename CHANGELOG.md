# Miami English · cambios

## v1.3.3 · 2026-11-13
- Auditoría de las frases de voz (revisada con Opus): más variantes naturales (AC, «Here's», «hasn't arrived», «Just a minute», «Have a good one», drugstore/grocery store…) y variantes erróneas retiradas (embassy, robbery, bus station, «nine eleven», «to go please»…).
- Notas de registro corregidas (nuts/peanuts, fitting/dressing rooms, split the bill, address, etc.).
- Puntuación más precisa: números a cifras («for 2» = «for two»), A/C, wifi y más contracciones; ya no aceptan lo contrario (turn right por left, «I'm not lost», negaciones, números distintos, on/off…) y las variantes de ≤4 palabras exigen todas.

## v1.3.2 · 2026-11-13
- Micrófono: al terminar se cierra con stop() y abort() (y otro abort a los 0,3 s) para que iOS libere la captura y apague el indicador.

## v1.3.1 · 2026-11-13
- Actualización automática: al volver a la app comprueba si hay versión nueva y se recarga sola (si no estás en mitad de una pregunta).

## v1.3 · 2026-11-13
- Hablar: se aceptan variantes con el mismo significado (p. ej. «Wait a moment, please» para «One moment, please»): las 165 frases con 2–10 variantes, contracciones y «911» como cifras, y sin penalizar «please», «a», «the».
- Cuando dices una variante válida, la app te dice que es correcta y explica por qué la suya es mejor (más cordial, más informal, más americana…).
- El micrófono solo está abierto mientras grabas: se corta al oír la frase, al pasar de pregunta, a los 8 s, al minimizar la app o cambiar de pestaña, y se puede parar pulsando de nuevo.

## v1.2 · 2026-11-13
- Hablar: nueva práctica oral con micrófono (reconocimiento de voz del navegador, 75 % de las palabras) o autoevaluación si no hay reconocimiento; un paso «Habla» por módulo imprescindible en el plan.
- Aviso para iPhone/Safari: instalar la web en la pantalla de inicio para no perder el progreso; petición de almacenamiento persistente.
- El test de nivel y el final funcionan sin sonido (omiten la escucha y no valoran esa habilidad).
- Temarios B1 y B2 renombrados «repaso» con su duración real (≈3 h y ≈4,5 h) y nota en Referencias.
- Pruebas: ~13.000 comprobaciones automáticas y `tests/mc_test.js` (precisión del test de nivel con alumnos simulados: 73–83 % exacta, errores solo de un nivel).

## v1.1 · 2026-11-13
- Curso B2: 22 lecciones (221 ejercicios): tiempos perfectos y de futuro avanzados, condicionales 3 y mixtos, deseos, deducción, pasiva y causativa, estilo indirecto, relativos, gerundio/infinitivo, inversión, conectores, phrasal verbs, colocaciones, idioms y registro, argumentar, comparar, reclamar y negociar, tags/so-such/artículos, adjetivos y adverbios, léxico de trabajo, ley, sociedad, tecnología, consumo y medios.
- El test de nivel llega hasta B2 (20 preguntas nuevas), el plan incluye lecciones B2 si el nivel es B2 y el test final compara 4 niveles.
- Temario y referencias: tabla de cobertura B2 contrastada con RD 1041/2017, MCER y programación EOI B2.1/B2.2 (incluida la secuenciación gramatical).
- Pruebas: ~11.000 comprobaciones automáticas.

## v1.0 · 2026-11-12
- App completa: onboarding (nombre, objetivo, miedos, tiempo, autoevaluación), test de nivel adaptativo (A1/A2/B1 + 4 habilidades) y plan generado por reglas.
- 9 módulos de Miami (5 imprescindibles + 4 opcionales), 165 frases en 3 niveles, consejos culturales, 14 simulaciones ramificadas, refuerzo sugerido por punto débil, escucha rápida con acento americano, repaso espaciado, cultura práctica, tarjeta de 30 frases clave, test final.
- Curso B1: 18 lecciones (146 ejercicios) + 6 mini-lecciones de refuerzo A1-A2.
- Diseño estilo Miami Vice (rosa neón, turquesa, atardecer y cuadrícula retro), tema noche/día.
- PWA: `manifest.webmanifest`, `icon.svg` y `sw.js` (red primero, caché para uso sin conexión).
- Pruebas automáticas con un DOM simulado: ~8.100 comprobaciones (planes, test, módulos, simulaciones, lecciones, generadores, ajustes, copia, persistencia). Errores encontrados y arreglados durante las pruebas: botón «Continúa» sin acción al acabar una sesión; huecos mal generados en frases con guion; distractores de nivel superior en A1; tolerancia al apóstrofo al escribir.
