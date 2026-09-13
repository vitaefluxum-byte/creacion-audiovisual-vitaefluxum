# Referencias y continuidad entre generaciones

## Carácter obligatorio

Las clasificaciones, jerarquías, bloqueos, controles anatómicos, controles de textura y criterios de rechazo de este documento son normas operativas obligatorias. No son consejos opcionales. Cuando una comprobación no pueda realizarse con seguridad o dos referencias no puedan resolverse mediante la jerarquía establecida, no aprobar ni presentar el resultado como correcto.

Utiliza esta referencia para preparar imágenes antes de generar, mantener continuidad entre clips y reducir errores, versiones inútiles y consumo innecesario de créditos.

## Preparación, inspección y clasificación de referencias

Antes de escribir el prompt, revisa visualmente todas las imágenes y asigna a cada una una función principal explícita:

- identidad y cuerpo;
- vestuario;
- escenario;
- composición o postura;
- primer fotograma;
- último fotograma;
- objeto;
- objetivo de edición.

Una imagen no controla automáticamente todos los elementos. En el prompt declara qué debe extraerse de cada referencia y qué no debe copiarse.

Comprueba que el rostro sea legible, que el vestuario y los colores puedan identificarse, que las imágenes no estén reflejadas y que no existan contradicciones. Revisa también piel plástica, patrones artificiales, identidad degradada, anatomía incorrecta, sangre accidental, heridas no deseadas, objetos deformados y arquitectura incorrecta. Ningún defecto puede convertirse en continuidad por aparecer en una imagen anterior.

> Si una imagen de composición contiene defectos visuales, utilizarla únicamente para recuperar cámara, postura, perspectiva y distribución espacial. La identidad, el rostro, la piel, el cuerpo, el vestuario y las marcas permanentes deben proceder de blueprints limpios. Nunca reproducir un defecto solamente porque aparece en una imagen anterior.

Considera también defectuosa cualquier superficie que muestre formas, surcos, manchas o relieves repetidos de manera artificial. Revisa especialmente piel, asfalto, pavimento, paredes, ropa, vegetación, agua, suciedad y escombros. Las texturas naturales deben variar sin periodicidad visible; no apruebes patrones circulares, geométricos, grabados, clonados o procedurales, incluso si se vuelven evidentes únicamente al ampliar o enfocar la imagen.

## Jerarquía obligatoria de referencias

1. El blueprint de identidad controla rostro, edad, cuerpo, piel, cabello, barba y marcas permanentes.
2. El blueprint de vestuario controla ropa, calzado, accesorios, materiales y desgaste.
3. La referencia del escenario controla arquitectura, distribución y elementos permanentes.
4. El fotograma o storyboard controla composición, cámara, postura y acción.
5. El primer y el último fotograma controlan exclusivamente los estados inicial y final del vídeo.

Cuando dos referencias se contradigan, no mezcles sus rasgos. Aplica esta jerarquía. Si el conflicto afecta a una decisión que el usuario debe conservar de forma diferente, adviértelo y pregunta cuál debe prevalecer antes de generar.

## Configuración previa

Antes de preparar una generación confirma o deduce de forma segura:

- herramienta de destino;
- imagen o vídeo;
- relación de aspecto y resolución;
- duración y velocidad narrativa;
- presencia de sonido o diálogo;
- número de personajes;
- referencias disponibles;
- uso de imagen inicial, final o ambas.

Si el usuario no indica formato, utiliza 16:9 horizontal y 1920 × 1080. No inventes una duración de vídeo cuando afecte al diálogo o a la viabilidad de la acción: pregúntala o propón una duración razonada.

## Continuidad entre clips

Registra el final de cada clip y úsalo como estado inicial del siguiente:

- posición y orientación de personajes;
- postura, mirada y emoción;
- mano y agarre de objetos;
- estado de ropa, cabello, heridas y suciedad;
- posición de elementos móviles;
- dirección de cámara y eje de acción;
- iluminación, clima y momento del día;
- diálogo o sonido que continúa.

Cuando sea posible, utiliza el último fotograma aprobado de un clip como referencia inicial del siguiente. No asumas que el generador recordará el plano anterior.

## Primer y último fotograma

Si la herramienta admite referencias inicial y final, comprueba antes que ambas imágenes sean compatibles:

- misma identidad y vestuario;
- misma escena y dirección de luz;
- cambio corporal físicamente posible;
- objetos presentes en ambos extremos o traslado explicado;
- perspectiva y escala que permitan una transición plausible.

Si las imágenes exigen una transformación imposible en la duración disponible, divide la acción en más de un plano.

## Movimiento e interacción física

Describe cada acción mediante sujeto, inicio, trayectoria, contacto y resultado. Mantén peso, equilibrio, inercia y reacción del entorno.

Para caminar o correr, fija dirección, ritmo, contacto de pies y seguimiento de cámara. Para manipular objetos, fija mano, agarre, peso, posición inicial y destino. Para cabello y ropa, describe solo la reacción causada por movimiento, viento o gravedad.

Interpreta cualquier indicación de derecha o izquierda desde la anatomía del sujeto, nunca desde la pantalla. Esto incluye extremidades, rasgos faciales, cicatrices, tatuajes, lunares, heridas, cabello, prendas asimétricas, joyas, relojes, fundas, bolsas, armas, accesorios y objetos. Al revisar, sigue visualmente la parte corporal correspondiente y no des por correcta la lateralidad solo porque estaba escrita en el prompt.

Comprueba que cada extremidad visible o parcialmente oculta tenga continuidad física con el cuerpo. Si la mano asignada a un objeto queda fuera de plano, el objeto también debe quedar fuera de plano u oculto de manera coherente. No permitas manos o extremidades flotantes, desconectadas, duplicadas o añadidas para hacer visible un objeto. Si el lado o la conexión no pueden verificarse con seguridad, marca el resultado como ambiguo y no lo apruebes.

Evita acumular acciones complejas simultáneas. Si existen cruces, multitudes, combate, vehículos o contacto entre cuerpos, prioriza trayectorias separadas y legibles.

## Varios personajes

Asigna a cada personaje:

- una referencia de identidad;
- posición inicial;
- acción y trayectoria;
- dirección de mirada;
- diálogo y turno de habla;
- objetos y lateralidad;
- relación espacial con los demás.

Evita descripciones como «ellos hablan y se mueven» cuando las acciones puedan confundirse. Nombra o identifica visualmente a cada sujeto y distribuye las acciones en el tiempo.

## Dividir planos difíciles

Considera dividir el plano cuando contenga varias de estas dificultades:

- más de dos personajes protagonistas;
- diálogo simultáneo;
- cambio complejo de cámara;
- carrera con obstáculos o cruces;
- intercambio de objetos;
- transformación física o de vestuario;
- multitudes, vehículos, agua, fuego o destrucción;
- recorrido largo con cambios de escenario.

Explica brevemente el riesgo y propone la división más sencilla antes de consumir una generación.

## Control de créditos

- No generar una imagen o vídeo si el usuario solo ha pedido un prompt.
- Ante blueprints o fichas técnicas, preguntar si quiere prompt, imagen o ambos.
- Mostrar ejemplos existentes antes de generar cuando ayuden a elegir.
- Revisar el prompt antes de enviarlo al generador.
- No crear todas las variantes posibles: generar solo la seleccionada.
- No reconstruir automáticamente todos los cuadros de un storyboard.
- No repetir una generación para corregir un fallo sin autorización, salvo que el usuario haya autorizado expresamente un proceso iterativo.
- Preferir una edición localizada cuando el resto del resultado ya sea correcto.
- Si una edición o corrección degrada una zona que antes era correcta, rechazar el resultado completo. No volver a reparar esa versión: regresar a la mejor imagen original y a las referencias limpias para generar de nuevo.

## Registro de versiones

Para cada resultado aprobado, conserva cuando el entorno lo permita:

- nombre breve y número de versión;
- herramienta y configuración relevante;
- prompt utilizado;
- referencias y función de cada una;
- formato, resolución y duración;
- decisiones de continuidad;
- errores observados y correcciones aplicadas;
- archivo aprobado que sustituye a versiones anteriores.

No borres versiones anteriores sin permiso. Diferencia claramente borrador, candidato y aprobado.

## Acabado final

Antes del montaje, comprueba:

- coincidencia de color y exposición entre planos;
- estabilidad de cara, manos, ropa y objetos;
- ausencia de parpadeos, deformaciones y elementos que aparecen o desaparecen;
- sincronización de diálogo y labios;
- continuidad de ambiente, efectos y música;
- resolución y relación de aspecto correctas;
- márgenes seguros para recorte, subtítulos o formato final.

No ocultes defectos importantes mediante reescalado, enfoque, grano o corrección de color. Corrige primero la causa cuando sea viable.
