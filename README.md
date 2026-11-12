# Miami English

Inglés **a medida para viajar a Miami** (interfaz y explicaciones en castellano). Funciona en el navegador, sin instalación ni cuentas, y se puede **instalar como app** en el móvil y usar **sin conexión** una vez cargada.

**Abrir la app:** https://pekemtir.github.io/Miami-English/

## Cómo funciona
1. **Cuéntame sobre ti**: nombre, para qué quieres inglés, qué te preocupa, tiempo hasta el viaje, minutos al día y autoevaluación.
2. **Test de nivel adaptativo** (hasta 30 preguntas): vocabulario, gramática, lectura y comprensión oral con acento americano. Resultado A1 / A2 / B1 / B2 y puntos débiles.
3. **Plan personalizado** generado por reglas (sin IA en vivo): nivel → dificultad; miedos y objetivo → orden de módulos; tiempo → cuántos caben; puntos débiles → más práctica en eso.
4. **Módulos de Miami** con frases, audio, consejos culturales, práctica y **simulaciones de conversación** ramificadas.
5. **Refuerzo sugerido** al acabar cada módulo (tú decides) y **test final** que compara con el inicial.

## Contenido
- 9 módulos: Supervivencia, Aeropuerto y migración, Restaurante y propinas, Taxi/Uber y direcciones, Urgencias (los 5 primeros son imprescindibles); Compras, Hotel, Conversación social, Cultura y dinero (opcionales).
- 165 frases en 3 niveles (A1, A2, B1; el B2 se cubre con su curso de gramática y léxico), 14 simulaciones, 10 preguntas de cultura práctica, tarjeta de 30 frases clave.
- **Curso B1 completo**: 18 lecciones de gramática, léxico y funciones (146 ejercicios), contrastado con el currículo del nivel Intermedio B1 (RD 1041/2017) y el MCER.
- **Curso B2 completo**: 22 lecciones (221 ejercicios), contrastado con el currículo del nivel Intermedio B2 (RD 1041/2017), el MCER y una programación de EOI de inglés B2.1/B2.2.
- 6 mini-lecciones de refuerzo A1-A2; repaso espaciado; escucha rápida; insignias y copia de seguridad.

## Privacidad
Todo funciona en tu dispositivo. Sin cuentas, anuncios, cookies ni rastreo. El progreso se guarda en `localStorage`.

## Propiedad intelectual y licencias
- **Código**: MIT (ver `LICENSE`).
- **Contenidos del curso** (textos, ejercicios, frases, simulaciones): obra original, licencia [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).
- **Tipografías** Patrick Hand y Nunito (incrustadas): SIL Open Font License 1.1 (`LICENSE-FONTS.txt`).
- El temario B1 se ha contrastado con el MCER (Volumen Complementario 2020) y con el currículo de nivel Intermedio B1 (Real Decreto 1041/2017, tal como lo recoge una programación de EOI), **solo como referencia de contenidos**: no se ha copiado ni traducido ningún texto. Ver `REFERENCIAS.md`.
- Proyecto independiente, **sin afiliación ni aval** de ninguna entidad oficial. No es un curso oficial ni emite certificados.
- Los consejos de viaje (propinas, impuestos, 911, requisitos de entrada) son orientativos: comprueba siempre las webs oficiales.

## Desarrollo
Un único `index.html` (fuentes incrustadas, sin peticiones externas) más `sw.js`, `manifest.webmanifest` e `icon.svg`. El código por partes y las pruebas están en `source.zip` (`src/` + `tests/`): `python3 src/build.py index.html` reconstruye la app y `node tests/audit_data.js`, `run_a.js`, `run_b.js`, `run_c.js` la prueban con un DOM simulado.
