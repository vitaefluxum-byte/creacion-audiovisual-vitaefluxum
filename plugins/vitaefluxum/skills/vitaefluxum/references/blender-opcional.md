# Previsualización opcional con Blender

Se ofrece después de aprobar la imagen base de la escena con personajes y objetos, proceda o no de un storyboard.
Pregunta: «¿Quieres preparar una previsualización en Blender para dirigir los movimientos y la cámara, o continuar directamente con el prompt de vídeo?».

## Representación
Muestra estos ejemplos existentes sin regenerarlos.
- [Volúmenes de colores](../assets/blender/volumenes.png): posiciones, recorridos y cámara. El entorno también utiliza geometría básica.
- [Maniquí articulado](../assets/blender/maniqui.png): añade pasos, posturas y articulaciones.
- [Modelo más detallado](../assets/blender/detallado.png): mayor parecido y más preparación.

Una escena sencilla suele requerir menos trabajo y correcciones del asistente. No garantiza una cantidad de uso: depende de la complejidad, herramientas y revisiones. Recomienda la representación más sencilla que permita comunicar la acción.
No confundas representación con acabado. Una iluminación más exigente puede aumentar el tiempo de Blender sin aumentar proporcionalmente el uso del asistente.
Acabado: [rápido](../assets/blender/rapido.png), [intermedio](../assets/blender/intermedio.png), [alto](../assets/blender/alto.png). No prometas tiempos ni costes fijos.

## Construcción y revisión
1. Comprueba disponibilidad de Blender y permisos. Si no se puede ejecutar, ofrece script e instrucciones en lugar de afirmar que has renderizado.
2. Fija escala, disposición del escenario, posición inicial, objetos y recorrido físico. La imagen puede no determinar geometría oculta; indica las suposiciones necesarias.
3. Presenta el render estático desde la cámara relevante y espera aprobación antes de producir la animación, salvo autorización explícita que ya incluya esa etapa.
4. Anima acciones, manos, postura y cámara. Mantén pies en contacto, articulaciones coherentes y desplazamiento real. Un personaje pequeño puede ser ágil: no deduzcas lentitud de su escala.
5. Exporta el MP4 aprobado como referencia. Por defecto sin sonido si su función es guiar movimiento, y conserva el .blend editable. Verifica duración, dimensiones, fotogramas y escenas clave.
6. En el prompt de vídeo, asigna al MP4 movimiento y cámara; al blueprint identidad; al escenario apariencia y geografía. El generador sustituye la representación sin conservar su aspecto simple.

La capacidad de subir un MP4 no prueba transferencia exacta de movimiento. Usa únicamente modalidades verificadas en la sesión; para Flow no presentes este flujo como una transferencia fiable sin una prueba satisfactoria.
