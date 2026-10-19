# Revisión del recurso y alineación pedagógica

**Fuente:** [Guía de Mantenimiento de Equipos de Cómputo](https://jabermudez.github.io/Gu-a-Mantenimiento-de-Computadores/).

**Repositorio público de referencia:** [jabermudez/Gu-a-Mantenimiento-de-Computadores](https://github.com/jabermudez/Gu-a-Mantenimiento-de-Computadores).

**Fecha de revisión:** 19 de octubre de 2026.

## Alcance de la revisión

Se recuperaron el HTML publicado, el recurso JavaScript público y los archivos fuente de la aplicación. Se revisaron las 15 secciones montadas por `App.tsx`, los datos de herramientas, diagnóstico y checklist, y las implementaciones de simuladores y reporte. La revisión fue de estructura, contenidos y lógica disponibles en el código; no se presenta como una auditoría de accesibilidad, validación científica de los modelos ni prueba de todos los controles de la web original. No se verificó la reproducción de los videos enlazados.

La guía tiene una cobertura amplia y conecta conceptos con simuladores visuales. Para trabajo autónomo en casa, convenía añadir encargos explícitos, productos de entrega, comparación de ensayos, reflexión y criterios docentes. Por ello se elaboró una aplicación complementaria con 12 misiones y una ruta de ocho horas. Se usan enlaces a la fuente en lugar de duplicar sus recursos.

## Matriz de cobertura de las 15 secciones

| Sección de la guía | Contenido revisado | Misión complementaria | Evidencia esperada |
|---|---|---|---|
| Introducción | Preventivo, correctivo, predictivo y evolutivo | 01, 11 | Ejemplos y criterio para distinguir propósitos. |
| Glosario | ESD, POST, térmica, VRM, almacenamiento y procedimientos | 03, 11 | Asociación y explicación al cliente con palabras propias. |
| Taller virtual | Descarga/aislamiento, bloqueo, disipador, limpieza, pasta, apriete y POST | 04 | Procedimiento ordenado con punto de detención. |
| Explorador de placa base | Socket, VRM, DIMM, PCIe, M.2, panel frontal y diagnóstico | 03, 10 | Mapa conceptual de funciones y uso de pistas de conexión. |
| Seguridad y ESD | Aislamiento, control electrostático, prohibición de apertura de PSU y químicos | 01, 08 | Estación segura y límites del trabajo doméstico. |
| Herramientas | Precisión, protección ESD, insumos y medición | 02 | Kit asociado a tareas y precauciones. |
| Protocolo de hardware | Ventiladores, disipador, RAM y apriete en cruz | 04, 05 | Secuencia y justificación de uniformidad de montaje. |
| Simulador térmico | Patrones, presión, plataforma y estimación | 05 | Tres configuraciones, comparación y límites del modelo. |
| Flujo de aire | Entradas, salidas, caudal estimado y balance | 06 | Tres balances y decisión contextualizada para polvo. |
| Sonda PSU | Rieles ATX, tolerancias y señales | 08 | Intervalos calculados e interpretación de lecturas ficticias. |
| Thermal pads y rodamientos | Espesor, contacto y tipos de rodamientos | 07 | Microguía de errores y compatibilidad. |
| Protocolo de software | DISM, SFC, optimización, CHKDSK y DNS | 09 | Herramienta pertinente, cautelas y plan lógico. |
| Diagnóstico | Energía, ausencia de imagen, temperatura y BSOD | 10, 12 | Ticket por pistas y transferencia a reinicios o BSOD. |
| Procedimientos animados | Aislamiento, disipador, RAM y medición ATX | 04, 07 | Orden de servicio y análisis de decisiones; pruebas eléctricas solo virtuales. |
| Checklist y reporte | Auditoría de tareas, datos del servicio y resultados | 12 | Informe de seis apartados, control de calidad y plan preventivo. |

## Decisiones de adaptación y límites técnicos

Se preservaron los temas y se redactaron actividades originales. Algunas afirmaciones de la guía son muy generales para trasladarlas directamente a una tarea doméstica o a todos los modelos. En la propuesta se aplicaron estos ajustes pedagógicos:

1. **Aislamiento no equivale a apertura segura de la fuente.** La pulsación del botón frontal no se utiliza como garantía de que los condensadores internos de una PSU estén descargados. No se abre la fuente ni se realizan puentes en casa. El ejercicio ATX se limita a interpretar datos ficticios.
2. **Una sola prueba no confirma una causa.** No se adopta la equivalencia entre ventilador detenido y fuente averiada, ni entre temperatura alta y una única causa. El diagnóstico pide hipótesis y evidencias. No se ofrece el giro del ventilador como prueba definitiva.
3. **La especificación depende del modelo.** Ranuras prioritarias de RAM, capacidad gráfica de CPU, espesor de pads, torque, tiempos de espera y productos de limpieza se remiten a documentación del fabricante. No se convierten A2/B2, un sufijo de procesador o un espesor en reglas universales.
4. **Los modelos virtuales no predicen temperaturas reales.** Contacto térmico utiliza un índice artificial explicado en pantalla. Aire utiliza entrada menos salida en CFM supuestos y no presenta ese resultado como una presión en pascales ni como un cálculo térmico validado.
5. **Las tolerancias se calculan sin redondeos ambiguos.** Para +3,3 V al ±5 %, el intervalo del ejercicio es 3,135–3,465 V. La actividad no extiende ±5 % a todos los rieles ni evalúa condiciones dinámicas o la totalidad de una revisión ATX.
6. **Limpieza con criterio de compatibilidad.** No se exige pulir contactos con goma, usar agujas en el socket ni asumir un tiempo fijo de evaporación. Se prioriza no contaminar, no abrasionar y seguir el producto y manual correspondientes. La ruta no prescribe un químico doméstico como sustituto.
7. **Mantenimiento lógico según necesidad.** La consola es una simulación sin ejecución real. No se prescribe CHKDSK `/f /r` como rutina, ni se promete resolver cualquier problema de red con DNS. Se explica que `/O` solicita la optimización apropiada al medio y se evita una prohibición simplista de todas las operaciones que Windows agrupa bajo optimización.
8. **Evidencia formativa frente a certificación.** El reporte se denomina portafolio de aprendizaje. El progreso automático no se presenta como acta oficial, verificación de un servicio real o aprobación de competencia.

Estos ajustes no constituyen una auditoría normativa del material original. Antes de una intervención real se debe contrastar el modelo concreto y el procedimiento del fabricante en un entorno de práctica autorizado.

Referencias primarias complementarias consultadas para los comandos de Windows:

- [Microsoft Support: uso del Comprobador de archivos de sistema](https://support.microsoft.com/en-us/windows/experience/backup-recovery/using-system-file-checker-in-windows): flujo DISM y SFC.
- [Microsoft Learn: defrag](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/defrag): función de `/O` para la optimización adecuada al medio.
- [Microsoft Learn: chkdsk](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/chkdsk): alcance de `/f` y `/r` y posibles requisitos de reinicio.

## Diseño del trabajo en casa

La ruta combina preguntas situadas, asociaciones, secuencias, observación de un esquema, dos experimentos comparativos, interpretación numérica, consola ficticia, investigación por etapas y proyecto integrador. No obliga a comprar piezas ni a tener un computador desmontable.

Cada misión exige tres respuestas de evidencia. Las consignas solicitan observar, explicar y transferir. Los dibujos y diagramas se describen en texto para que el portafolio funcione también desde un celular. El instructor puede pedir anexos por su canal habitual, sin que la web almacene imágenes.

No hay nota centralizada, seguimiento remoto ni envío automático. Los archivos HTML/JSON descargados permiten entregar el trabajo y continuarlo. La rúbrica docente evalúa lo que la autocorrección no puede: precisión de las explicaciones, pertinencia de las pruebas, cuidado de datos y coherencia del informe.
