# Miami English · cambios

## v1.0 · 2026-11-12
- App completa: onboarding (nombre, objetivo, miedos, tiempo, autoevaluación), test de nivel adaptativo (A1/A2/B1 + 4 habilidades) y plan generado por reglas.
- 9 módulos de Miami (5 imprescindibles + 4 opcionales), 165 frases en 3 niveles, consejos culturales, 14 simulaciones ramificadas, refuerzo sugerido por punto débil, escucha rápida con acento americano, repaso espaciado, cultura práctica, tarjeta de 30 frases clave, test final.
- Curso B1: 18 lecciones (146 ejercicios) + 6 mini-lecciones de refuerzo A1-A2.
- Diseño estilo Miami Vice (rosa neón, turquesa, atardecer y cuadrícula retro), tema noche/día.
- PWA: `manifest.webmanifest`, `icon.svg` y `sw.js` (red primero, caché para uso sin conexión).
- Pruebas automáticas con un DOM simulado: ~8.100 comprobaciones (planes, test, módulos, simulaciones, lecciones, generadores, ajustes, copia, persistencia). Errores encontrados y arreglados durante las pruebas: botón «Continúa» sin acción al acabar una sesión; huecos mal generados en frases con guion; distractores de nivel superior en A1; tolerancia al apóstrofo al escribir.
