# Guía del instructor · Bitácora PC

## Propósito y alcance

Proponer trabajo autónomo que transforme la consulta de la guía de mantenimiento en decisiones, ensayos comparativos y comunicación técnica. Nivel sugerido: aprendices que inician o consolidan fundamentos de soporte y mantenimiento de computadores. No se asigna un código de competencia, resultado de aprendizaje o acreditación institucional que no haya sido proporcionado por el instructor.

La totalidad de las tareas puede desarrollarse sin disponer de un equipo para desmontar. Las intervenciones reales se deben planear como prácticas distintas con autorización, manuales, supervisión y condiciones apropiadas. Las consignas de la ruta no autorizan mediciones eléctricas en casa.

## Objetivos observables

Al terminar, el aprendiz podrá:

1. Identificar riesgos, tipos de mantenimiento y recursos de servicio pertinentes.
2. Reconocer funciones de componentes de la placa base y organizar un procedimiento documentado.
3. Comparar ensayos virtuales de refrigeración y declarar los límites del modelo.
4. Calcular intervalos de tolerancia para lecturas positivas ATX y distinguir indicio de diagnóstico.
5. Elegir herramientas lógicas según el síntoma y valorar precauciones de datos y autorización.
6. Resolver un caso mediante hipótesis, pistas y validación, y redactar un reporte trazable.

## Preparación

- Comparta el enlace de Pages o el ZIP descomprimible y compruebe que todos puedan abrirlo.
- Indique las fechas y el canal de entrega; la aplicación no fija plazos ni recibe archivos.
- Explique cómo identificar el portafolio y descargar la copia JSON.
- Aclare que las respuestas automáticas son práctica y que se valorará la argumentación propia.
- Entregue apoyos de lectura o más tiempo cuando sean necesarios. No condicione la nota a tener hardware o herramientas en casa.
- Si se comparte un navegador, cada aprendiz debe restaurar su copia al iniciar y exportarla/borrar la sesión al terminar. No hay perfiles múltiples simultáneos.

## Planeación de cuatro sesiones

| Sesión | Misiones | Tiempo total | Evidencias principales |
|---|---|---:|---|
| 1 · Preparación | 01: 35 min; 02: 35 min; 03: 40 min | 110 min | Estación segura descrita, kit con precauciones y dibujo/esquema de placa explicado. |
| 2 · Intervención virtual | 04: 40 min; 05: 45 min; 06: 45 min | 130 min | Flujo de procedimiento, tres configuraciones de contacto térmico y tres balances de aire. |
| 3 · Interpretación y diagnóstico | 07: 30 min; 08: 35 min; 09: 45 min | 110 min | Microguía de errores, cálculo ATX y plan de mantenimiento lógico. |
| 4 · Comunicación y cierre | 10: 50 min; 11: 30 min; 12: 50 min | 130 min | Ticket resuelto, explicación al cliente y reporte final. |
| **Total** | **12 misiones** | **480 min / 8 horas** | **36 respuestas de evidencia, ensayos e informe de seis secciones.** |

Los tiempos incluyen lectura, interacción y redacción. Pueden distribuirse en varios días. Las categorías del menú son temáticas; la misión 07 cierra refrigeración antes de la interpretación ATX y el software.

## Estructura común de cada misión

1. **Tu encargo:** objetivo, caso, pasos y enlaces específicos a la guía.
2. **Resuelve el reto:** interacción, resultado y explicación de la respuesta.
3. **Deja una evidencia:** tres consignas abiertas para observación, razonamiento y transferencia.

Si el aprendiz elabora un dibujo, lo describe en el portafolio. Las imágenes no se cargan ni se almacenan. Puede anexar fotos por el canal docente acordado, evitando personas y datos sensibles.

## Interacciones y criterios especiales

- **01 y 07:** decisiones con opciones y justificación después de verificar.
- **02, 03 y 11:** asociaciones mediante selectores; 03 añade un esquema conceptual con pistas.
- **04:** orden de seis etapas mediante botones; permite teclado y evita depender de arrastrar.
- **05:** cobertura, limpieza y uniformidad de montaje. Deben registrarse tres configuraciones distintas. Índice artificial = cobertura × factor de limpieza (1 o 0,55) × factor de uniformidad (1 o 0,65), redondeado. No representa eficiencia ni temperatura.
- **06:** balance artificial = entrada efectiva supuesta − salida efectiva supuesta. Positivo >10 CFM, negativo <−10 CFM y similar entre −10 y +10. Deben existir ensayos de los tres tipos. Estas categorías son umbrales de la actividad, no una norma física.
- **08:** límites de ±5 % para los tres rieles positivos del ejercicio: +12 V → 11,400–12,600 V; +5 V → 4,750–5,250 V; +3,3 V → 3,135–3,465 V. Lecturas: 11,2 V fuera; 5,1 V dentro; 3,5 V fuera. La fuente no queda diagnosticada solo con estos valores.
- **09:** los comandos únicamente cambian texto en la web. No llaman a una terminal ni a APIs del sistema.
- **10:** para revelar pistas hay que validar cada etapa. Cambiar una decisión previa invalida las posteriores. Al cerrar, pedir que explique por qué la evidencia sostiene un error de conexión y no una falla confirmada de la placa.
- **12:** seis secciones de reporte, cada una de al menos 40 caracteres, y cuatro comprobaciones antes de completar.

## Evaluación

El avance automático requiere 80 % en el reto y tres evidencias de al menos 40 caracteres. Los laboratorios y el proyecto aplican requisitos adicionales. Se conservan hasta 50 intentos por misión; se muestra el mejor puntaje, pero el estado actual requiere que los cambios hayan sido verificados de nuevo. Cada misión completa suma 100 XP, hasta 1200. Las respuestas abiertas solo se verifican por extensión.

### Rúbrica docente sugerida

| Criterio | Peso | Indicadores del nivel 4 |
|---|---:|---|
| Seguridad y cuidado de datos | 25 % | Identifica riesgos, aislamiento y control ESD; incorpora autorización, respaldo y límites de la simulación. |
| Razonamiento técnico | 30 % | Relaciona hipótesis, pruebas y conclusiones; calcula intervalos; selecciona herramientas con criterios pertinentes. |
| Experimentación y evidencias | 25 % | Registra y compara ensayos distintos, explica resultados y límites y usa sus propias palabras. |
| Documentación y comunicación | 20 % | Informe trazable, validación, recomendaciones y mensaje comprensible al usuario. |

Escala común:

- **4:** cumple todos los indicadores con evidencias consistentes.
- **3:** cumple la mayoría; presenta omisiones menores que no alteran el razonamiento principal.
- **2:** desarrollo parcial, conexiones débiles o resultados insuficientemente explicados.
- **1:** menciona conceptos, pero no los aplica al caso o no aporta sustento.
- **0:** no presenta evidencia del criterio.

Puntaje sugerido sobre 100 = suma de `(nivel / 4) × peso`. Ejemplo: niveles 4, 3, 2 y 3 → 25 + 22,5 + 12,5 + 15 = 75. El instructor define su criterio institucional de aprobación. Una propuesta insegura requiere corrección antes de pasar a una práctica física.

## Entrega y retroalimentación

1. Reciba `bitacora-pc-entrega.html` o un PDF del portafolio. Pida JSON solo si necesita reabrir el trabajo.
2. Compruebe la identificación, la coherencia entre ensayos y explicaciones y el carácter real/simulado de los datos.
3. Seleccione una decisión al azar y solicite una explicación breve oral o escrita.
4. Devuelva una fortaleza y una corrección concreta por criterio.
5. Permita reintento y nueva exportación.

La web no dispone de un servidor de calificaciones ni anti fraude. Las respuestas correctas están en el código por tratarse de práctica formativa estática. No use XP ni longitud de texto como acreditación de desempeño profesional. El HTML exportado es una fotografía del momento de descarga; no se actualiza con cambios posteriores.

## Alternativas y extensión opcional

- **Solo celular:** todos los controles tienen alternativa táctil; redactar el esquema en texto es válido.
- **Sin conexión:** distribuir la carpeta completa. La guía externa puede prepararse previamente por el medio permitido por su autor; esta entrega no la reproduce.
- **Apoyo de lectura:** trabajar por parejas para debatir decisiones, con evidencia individual posterior.
- **Reto de profundización:** contrastar una generalización de la guía con el manual de un modelo concreto e indicar qué cambia en el procedimiento. No se exige manipular el equipo.
- **Socialización posterior:** comparar dos planes de diagnóstico y argumentar cuál reduce intervenciones innecesarias.

## Referencia

[Guía de Mantenimiento de Equipos de Cómputo](https://jabermudez.github.io/Gu-a-Mantenimiento-de-Computadores/) · revisión de estructura y contenidos: 19 de octubre de 2026. La matriz de revisión está en `REVISION-Y-ALINEACION.md`.
