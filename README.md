# Bitácora PC · Laboratorio en casa

Web estática en español con 12 misiones de mantenimiento de computadores. Diseñada para trabajo autónomo, celulares y computadores, sin cuentas, servidor de datos ni instalación de paquetes.

**Acceso para aprendices:** [Abrir Bitácora PC](https://jabermudez.github.io/bitacora-pc/).

**Repositorio:** [jabermudez/bitacora-pc](https://github.com/jabermudez/bitacora-pc). GitHub Pages publica desde `main`, carpeta raíz. Los cambios subidos a esa rama generan una nueva publicación.

## Abrir y usar

1. Descomprime el ZIP completo.
2. Abre `index.html` en un navegador moderno. Mantén `styles.css`, `data.js`, `app.js` y `favicon.svg` junto a él.
3. En **Mi portafolio**, escribe tu nombre o alias y ficha/grupo.
4. Resuelve las misiones y desarrolla las evidencias. El avance se guarda en este navegador.
5. Descarga la entrega HTML o imprime a PDF. Entrega el archivo por el medio que indique tu instructor.
6. Descarga también la copia JSON si necesitas continuar en otro dispositivo.

El comportamiento de almacenamiento al abrir archivos con `file://` puede variar entre navegadores. Para un guardado más consistente, usa GitHub Pages o un servidor local. Conserva siempre una copia JSON. Para probar con Python, abre una terminal en esta carpeta y ejecuta:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Después abre `http://127.0.0.1:8000/`.

## Publicar en GitHub Pages sin compilar

1. Crea un repositorio en GitHub, por ejemplo `bitacora-pc`.
2. En **Add file → Upload files**, sube **el contenido** de esta carpeta a la raíz del repositorio. `index.html` debe quedar directamente en la raíz, no dentro de otra carpeta. No subas únicamente el ZIP.
3. Confirma los archivos con un commit.
4. Abre **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**.
6. Elige la rama que contiene tus archivos (normalmente `main`) y la carpeta **/ (root)**. Guarda.
7. Espera a que termine la publicación y abre el enlace que muestre GitHub Pages. Habitualmente será `https://TU-USUARIO.github.io/bitacora-pc/`.

No requiere `npm install`, claves de API, base de datos ni GitHub Actions personalizado. Todas las rutas de recursos son relativas, por lo que funciona bajo una subcarpeta de GitHub Pages. Se incluye `.nojekyll`. Si tu organización o plan limita Pages, comprueba las opciones disponibles en la configuración del repositorio.

Referencia de publicación: [Configurar la fuente de publicación de GitHub Pages — documentación de GitHub](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site), consultada el 19 de octubre de 2026.

## Qué incluye

- Ruta de 8 horas sugeridas, distribuida en cuatro sesiones.
- Decisiones con retroalimentación, asociaciones, esquema de placa y ordenamiento accesible con botones.
- Laboratorios de contacto térmico y balance de aire con registro de pruebas distintas.
- Interpretación de lecturas ATX ficticias y consola de Windows simulada.
- Caso de diagnóstico con pistas progresivas.
- Informe final, portafolio, historial de hasta 50 intentos por misión y progreso local.
- Copia/restauración JSON con validación de estructura y recálculo al importar.
- Entrega HTML autónoma con respuestas, pruebas, evidencias y reporte, imprimible a PDF desde el navegador.
- Orientaciones para instructor, rúbrica y matriz de alineación con las 15 secciones de la guía base.

## Criterio de avance

Cada misión suma 100 XP cuando alcanza al menos 80 % en el reto y contiene tres evidencias de al menos 40 caracteres cada una. Los laboratorios exigen tres configuraciones distintas; flujo de aire requiere los tres tipos de balance. El informe final exige seis secciones y cuatro comprobaciones. Modificar las respuestas invalida el resultado hasta verificar de nuevo.

Los puntajes son formativos. La longitud de las respuestas no certifica su calidad. La valoración final corresponde al instructor mediante la rúbrica. El sistema no supervisa identidad, no impide consultar respuestas y no es una plataforma de evaluación de alto impacto.

## Privacidad, conectividad y seguridad

Los datos se guardan únicamente en `localStorage` con la clave `bitacora-pc-v1`. No existe envío automático, registro remoto, analítica ni panel central de aprendices. El borrado de datos del sitio, la navegación privada o el cambio de navegador/dominio puede eliminar o separar el progreso. En un computador compartido, exporta tu copia y borra la sesión al terminar.

Google Fonts es el único recurso visual externo y tiene fuentes de respaldo locales. La guía base requiere conexión. Una vez descargada la carpeta completa, las actividades funcionan localmente sin internet; la versión alojada no promete caché sin conexión. No incluyas datos sensibles ni datos reales de clientes.

La ruta es virtual. No exige abrir equipos, puentear fuentes, medir circuitos energizados, modificar firmware ni ejecutar comandos reales. Los índices de los simuladores son modelos didácticos, no predicciones físicas ni instrucciones para una instalación concreta.

## Editar y adaptar

- `data.js`: títulos, tiempos, preguntas, respuestas, secciones de referencia y consignas de evidencia.
- `app.js`: comportamiento, exportación, validación y páginas de recursos/instructor.
- `styles.css`: diseño adaptable, colores y estilos de impresión.
- `GUIA-DOCENTE.md`: planeación y revisión.
- `REVISION-Y-ALINEACION.md`: revisión de la fuente y decisiones de adaptación.

Si cambias IDs o el esquema de datos, migra el almacenamiento o cambia la versión y la clave para no interpretar avances anteriores como nuevas actividades. Si solo cambias preguntas, considera reiniciar la ruta: un resultado previo corresponde a la versión anterior del reto.

## Fuente y atribución

Material base: [Guía de Mantenimiento de Equipos de Cómputo](https://jabermudez.github.io/Gu-a-Mantenimiento-de-Computadores/), publicada por `jabermudez`. Repositorio consultado: [Gu-a-Mantenimiento-de-Computadores](https://github.com/jabermudez/Gu-a-Mantenimiento-de-Computadores). Revisión: 19 de octubre de 2026.

Las actividades, textos complementarios, interfaz y esquemas de Bitácora PC son originales. No se redistribuyen el código, videos ni imágenes de la guía. No se atribuye una licencia a los materiales ajenos ni se presenta esta herramienta como un producto oficial del SENA o de la guía.
