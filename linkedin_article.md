# He enseñado a Claude a resolver problemas complejos (y tú también puedes)

Llevo un tiempo explorando cómo sacar partido real a la IA generativa más allá del "hazme un resumen" o "escríbeme un email". Y hace unos días me hice una pregunta que me llevó a un proyecto que quiero compartir:

**¿Y si pudiera enseñarle a Claude toda la metodología de Complex Problem Solving que he estudiado durante años, para que la aplique de forma rigurosa cada vez que le planteo un problema?**

La respuesta es que sí se puede. Y el resultado está en GitHub, abierto para quien quiera usarlo o adaptarlo.

Pero antes de entrar en el qué, déjame explicar el cómo — porque creo que la pieza más interesante es un concepto que poca gente conoce todavía.

---

## Qué es una "skill" de Claude (explicado para mortales)

Cuando usas Claude — ya sea en claude.ai, en Claude Code (la herramienta de terminal) o en Cowork (el modo escritorio) — estás interactuando con un modelo que sabe mucho de muchas cosas, pero que no conoce TU forma específica de trabajar.

Una **skill** es, en esencia, un conjunto de instrucciones que le enseñan a Claude una metodología concreta. Piensa en ello como un manual de procedimientos que Claude consulta cuando detecta que el problema que le planteas encaja con esa skill.

Técnicamente, una skill es una carpeta con un archivo principal (SKILL.md) que contiene las instrucciones, y opcionalmente archivos de referencia que Claude carga solo cuando necesita profundizar en un tema concreto. Es elegante porque no sobrecarga el contexto: Claude lee lo justo en cada momento.

Lo interesante es que cualquiera puede crear skills. No necesitas saber programar. Solo necesitas saber qué quieres que Claude haga y cómo quieres que lo haga. El resto es estructurar bien las instrucciones.

Y aquí es donde se pone interesante.

---

## Por qué una skill de Complex Problem Solving

Los que trabajamos en consultoría, estrategia o gestión de proyectos complejos sabemos que resolver problemas de verdad — los que no tienen solución obvia, los que persisten a pesar de múltiples intentos, los que involucran a stakeholders con intereses contrapuestos — requiere método.

No vale con "pensar mucho". Hay que saber clasificar el problema, diagnosticarlo con rigor, analizar las causas raíz (que suelen ser múltiples), verificar que nuestros propios sesgos no nos están engañando, generar opciones sin contaminarlas con juicio prematuro, evaluar estratégicamente y planificar la implementación.

El problema es que hacer todo esto bien, cada vez, es difícil. Se nos olvidan pasos. Saltamos al solucionismo. Nos dejamos llevar por la intuición cuando deberíamos activar el pensamiento deliberado.

**Una skill de CPS convierte a Claude en un compañero de análisis que nunca se salta un paso.**

---

## Qué hay dentro de la skill

He integrado el conocimiento de más de 14 autores y frameworks en una metodología cohesiva de 7 fases, con el **Problem Solving Estratégico de Giorgio Nardone** como columna vertebral.

¿Por qué Nardone como eje? Porque su enfoque tiene una idea central que cambia la forma de pensar sobre los problemas: **la mayoría de problemas persisten no a pesar de los intentos de solución, sino a causa de ellos.** Entender qué mantiene vivo un problema es más útil que entender qué lo originó.

Las 7 fases son:

**Fase 0 — Clasificar el problema.** Usando el framework Cynefin de Dave Snowden. No todos los problemas son iguales: un problema simple requiere una mejor práctica; un problema complejo requiere experimentación. Usar la herramienta equivocada es peor que no usar ninguna.

**Fase 1 — Definir el problema con rigor.** Aquí entran el Reductor de Complejidad de Nardone, las Soluciones Intentadas Redundantes (qué se ha intentado y por qué no ha funcionado), CATWOE, IS/IS NOT, y Jobs to Be Done para problemas de producto o mercado.

**Fase 2 — Analizar las causas raíz.** Con 5 Porqués, Ishikawa, árboles lógicos, los Puntos de Apalancamiento de Donella Meadows y Wardley Mapping para problemas con componente tecnológico. Con la advertencia de Javier Recuenco: los problemas complejos tienen múltiples causas raíz. No busques una; busca la constelación.

**Fase 3 — Auditar sesgos cognitivos.** Kahneman (Sistema 1 y 2), los modelos mentales de Charlie Munger, y un checklist de falacias lógicas. Esta fase es incómoda pero esencial: consiste en cuestionar lo que creemos saber.

**Fase 4 — Generar soluciones.** Con las técnicas de Nardone (la brillante "Cómo Empeorar", el Escalador, Pequeños Pasos), los Seis Sombreros de De Bono, y técnicas creativas como la Flor de Loto o las Conexiones Morfológicas. Con una regla de oro de Diana Damas: nunca mezclar pensamiento creativo con pensamiento crítico.

**Fase 5 — Evaluar estratégicamente.** El Kernel de la Buena Estrategia de Richard Rumelt (Diagnóstico, Política Guía, Acciones Coherentes), pre-mortem, y tests de evaluación: ¿es más de lo mismo? ¿Intervenimos al nivel correcto del sistema? ¿A qué renunciamos?

**Fase 6 — Planificar e implementar.** Metodología 8D para problemas técnicos, Team of Teams de McChrystal para entornos complejos, y Empatía Táctica de Chris Voss para gestionar stakeholders.

**Fase 7 — Monitorizar y ajustar.** Porque los problemas complejos nunca se resuelven en un solo movimiento. Nardone lo llama el principio de la matrioshka: al resolver una capa, aparece la siguiente.

---

## Tres niveles de profundidad

No siempre necesitas las 7 fases. Por eso la skill ofrece un menú de 3 niveles al arrancar:

- **Análisis Rápido:** Clasificación + diagnóstico + causas principales. Para primeras impresiones.
- **Análisis Estándar:** Fases 0 a 5. Para análisis de situación y preparación de decisiones.
- **Análisis Completo:** Las 7 fases con documento entregable. Para proyectos estratégicos.

Funciona en español e inglés.

---

## Los autores que hay detrás

La skill no es una colección aleatoria de herramientas. Es una síntesis que intenta ser mayor que la suma de sus partes, integrando el trabajo de: Giorgio Nardone, Dave Snowden, Richard Rumelt, Donella Meadows, Daniel Kahneman, Charlie Munger, Edward de Bono, Stanley McChrystal, Chris Voss, Ken Watanabe, David Epstein, Simon Wardley, Clayton Christensen, Javier Recuenco y Diana Damas.

Cada autor aporta una lente diferente. La skill sabe cuándo activar cada una.

---

## Para qué sirve en la práctica

Algunos ejemplos de uso real:

- "Analízame por qué la transformación digital de esta unidad de negocio no avanza a pesar de llevar 2 años de inversión."
- "Estamos evaluando tres opciones estratégicas para entrar en un nuevo mercado. Ayúdame a decidir."
- "Tenemos un problema de retención de talento que no conseguimos resolver. Ya hemos probado varias cosas."
- "Necesito arrancar este proyecto complejo y no sé por dónde empezar."

En todos estos casos, Claude aplica la metodología CPS completa (o la parte que corresponda según el nivel elegido), con rigor, sin saltarse pasos, y sin los sesgos que inevitablemente tenemos los humanos cuando nos enfrentamos a problemas que nos afectan personalmente.

---

## Cómo usarla

La skill está publicada en GitHub con licencia MIT:

https://github.com/joobid/CPS-skills

Para instalarla en Claude Code, basta con copiar la carpeta `complex-problem-solving/` al directorio de skills. En Cowork, se puede empaquetar como .skill.

Si te dedicas a consultoría, estrategia, gestión de proyectos o simplemente te enfrentas a problemas complejos con frecuencia, pruébala. Y si crees que falta algo o que alguna herramienta debería tener más peso, las contribuciones son bienvenidas.

---

## La reflexión final

Lo que me parece más interesante de este proyecto no es la skill en sí, sino lo que representa: **la posibilidad de codificar conocimiento experto acumulado durante años en un formato que un agente de IA puede aplicar de forma consistente.**

No reemplaza el juicio humano. Lo amplifica. Te obliga a hacer las preguntas que se te olvidarían. Te recuerda verificar tus sesgos. Te impide saltar al solucionismo.

Y eso, francamente, nos viene bien a todos.

---

*¿Trabajas con problemas complejos? ¿Has probado a crear skills para Claude? Me encantaría conocer tu experiencia.*

#ComplexProblemSolving #IA #Claude #Estrategia #ProblemSolving #Innovación #Skills
