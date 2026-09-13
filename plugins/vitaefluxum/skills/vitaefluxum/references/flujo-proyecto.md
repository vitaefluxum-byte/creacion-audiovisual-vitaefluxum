# Flujo guiado de un proyecto audiovisual

Utiliza este flujo cuando el usuario quiera desarrollar un proyecto completo o continuar desde un guion. Su finalidad es guiarlo en el orden de producción y evitar crear escenas antes de fijar sus elementos de continuidad.

No apliques toda la cadena a una petición aislada. Si el usuario solo quiere un guion, un blueprint, una imagen o un prompt concreto, resuelve únicamente esa petición. Si desea continuar el proyecto, retoma la primera fase pendiente.

## Forma de guiar

Después de completar cualquier acción, entrega o fase, aunque el usuario haya pedido una pieza aislada:

1. indica brevemente qué apartado ha quedado terminado;
2. anuncia con claridad el nombre del apartado siguiente;
3. explica en una frase qué se preparará y por qué es necesario;
4. propone un único siguiente paso y pregunta si desea continuar con él.

No termines mostrando solo el resultado ni esperes a que el usuario escriba «siguiente» para explicarle qué toca hacer. No presentes muchas rutas alternativas a la vez. Conserva una lista interna de elementos aprobados y pendientes. No repitas decisiones ya confirmadas. No inicies una nueva generación ni consumas créditos sin autorización.

Ejemplo de cierre después de crear un escenario: «El escenario base ya está preparado. El siguiente paso recomendado es planificar los planos de esta escena y crear el storyboard 3×3, incorporando entonces los personajes aprobados. ¿Quieres que continuemos con el storyboard?»

## Orden de producción

### 1. Guion

Cuando el genero y la premisa esten definidos, detente obligatoriamente antes de escribir y pregunta si quiere escoger una pelicula conocida de ese genero como referencia o dejar que VitaeFluxum decida, siguiendo `guion-referencias-cinematograficas.md`. No redactes la sinopsis, la escaleta ni el guion hasta recibir la respuesta. Después desarrolla y revisa la historia hasta que el usuario la apruebe. Al finalizar, explica que el siguiente paso recomendado es realizar el desglose y entrar en el apartado de blueprints.

Transición orientativa: «El guion ya está definido. Ahora conviene entrar en el apartado de blueprints para fijar los personajes y los objetos importantes antes de crear las escenas.»

### 2. Desglose de continuidad

Extrae del guion, sin pedir al usuario que haga el trabajo técnico:

- personajes que necesitan diseño visual;
- cambios de vestuario o estado;
- objetos recurrentes o narrativamente importantes;
- localizaciones y variaciones de luz, época o deterioro;
- escenas de un solo plano y escenas que necesitarán storyboard.

Muestra un resumen compacto. No crees un blueprint para figurantes u objetos irrelevantes.

### 3. Blueprints de personajes

Anuncia que comienza el **apartado de blueprints de personajes**. Trabaja los personajes principales uno por uno. Sigue `catalogo-blueprints.md` y pregunta, en un solo mensaje breve:

- qué personaje se prepara;
- cómo será físicamente y cómo irá vestido, o si VitaeFluxum debe proponerlo;
- qué clase de blueprint quiere: 1A, 1B, 2 o 3;
- si quiere ver los ejemplos;
- si desea imagen, imagen y prompt, o solo prompt.

No inventes el aspecto ni generes hasta recibir las decisiones necesarias. Marca cada personaje como aprobado antes de avanzar.

### 4. Blueprints de objetos

Cuando estén aprobados los personajes, anuncia el **apartado de blueprints de objetos**. Presenta únicamente los objetos relevantes detectados en el desglose. Pregunta cuáles desea fijar y aplica la opción 4 del catálogo. Conserva escala, materiales, color, daños, orientación y relación con el personaje.

Si el guion no contiene objetos que necesiten continuidad, indícalo y pasa a la fase siguiente sin inventarlos.

### 5. Producción escena por escena

Cuando personajes y objetos estén definidos, anuncia el **apartado de escenas**. A partir de aquí trabaja cada escena de principio a fin antes de pasar a la siguiente; no prepares primero todos los escenarios, después todos los storyboards y finalmente todos los fotogramas.

Para cada escena sigue este ciclo:

1. **Escenario e imagen base:** fija la localización, geografía, accesos, elementos permanentes, momento del día, iluminación y orientación. Genera la base del escenario sin personajes. Los personajes y los objetos manipulados se incorporan después al planificar el storyboard o el fotograma, utilizando sus blueprints aprobados.
2. **Planificación y storyboard:** crea una lista de planos cuando aporte valor. Si la escena contiene varios planos, prepara su storyboard 3×3. Si solo necesita un plano, crea directamente el fotograma de la escena incorporando los personajes y objetos aprobados sobre el escenario base; no lo confundas con otra imagen del escenario vacío.
3. **Revisión:** comprueba la progresión narrativa y la coherencia de identidad, vestuario, objetos, lateralidad, color, escenario, luz y composición. Señala cualquier error concreto y pide al usuario que apruebe o corrija la escena.
4. **Fotogramas seleccionados:** si hacen falta imágenes independientes, pregunta qué números aprobados del storyboard se deben reconstruir. Genera únicamente los seleccionados.
5. **Cierre de escena:** resume qué queda aprobado y anuncia que se pasa a la escena siguiente.

Conserva el funcionamiento que permite revisar y aceptar cada cuadrícula antes de continuar. No obligues a reconstruir fotogramas si el usuario solo quiere aprobar los storyboards en esta fase.

### 6. Vídeo y acabado

Cuando los fotogramas necesarios estén aprobados, anuncia el **apartado de vídeo**. Prepara el prompt específico de cada plano con acción, cámara, interpretación, sonido y timeline cuando la herramienta lo admita. Mantén continuidad entre el final de un plano y el inicio del siguiente.

Cuando todas las escenas necesarias estén aprobadas, prepara el vídeo plano por plano. Termina con una revisión general de montaje, continuidad, diálogo, sonido y acabado.

## Cambios de orden

El usuario puede saltar una fase o pedir una pieza concreta. Respeta su decisión, pero avisa brevemente si falta una referencia que pueda provocar incoherencias. No bloquees el trabajo cuando el riesgo sea menor o el usuario acepte continuar.
