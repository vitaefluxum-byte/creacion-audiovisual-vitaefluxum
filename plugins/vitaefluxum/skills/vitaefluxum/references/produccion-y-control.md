# Producción y control audiovisual

## Cumplimiento obligatorio

Los controles de referencias, continuidad, anatomía, lateralidad, texturas, resolución y aprobación de este documento son condiciones obligatorias de entrega. No deben interpretarse como recomendaciones. Si un control falla o no puede verificarse, declarar el resultado pendiente o rechazado y no describirlo como corregido, coherente o final.

Utiliza esta referencia para convertir un guion o una idea en materiales producibles y para corregir imágenes o vídeos ya generados. El usuario no necesita conocer terminología técnica: interpreta su intención, toma las decisiones profesionales razonables y pregunta únicamente cuando una preferencia personal pueda cambiar sustancialmente el resultado.

## Elegir la función

- **Desglose de guion:** identifica personajes, vestuario, localizaciones, objetos, efectos, sonido y necesidades de continuidad por escena.
- **Lista de planos:** convierte una escena en planos ordenados con función narrativa, encuadre, ángulo, lente orientativa, movimiento, acción, sonido y duración aproximada.
- **Biblia de continuidad:** consolida los rasgos que no pueden cambiar entre imágenes y vídeos.
- **Secuencia cinematográfica:** diseña varios planos consecutivos respetando eje, geografía, miradas, posiciones, acciones y raccord.
- **Revisión de imagen:** detecta problemas antes de animar.
- **Diagnóstico de vídeo:** localiza el fallo observable y propone una corrección mínima del prompt.
- **Adaptación por herramienta:** conserva la intención y reformula solo la estructura que dependa del generador elegido.
- **Plan de producción:** ordena la creación de referencias, pruebas, planos y vídeos para reducir repeticiones y generaciones innecesarias.
- **Control de calidad:** compara los resultados con las referencias y entrega correcciones priorizadas.

Usa únicamente la función necesaria. No conviertas una petición sencilla en todo el proceso completo.

## Desglose de guion

Para cada escena, extrae solo lo que debe producirse o conservarse:

- personajes presentes y estado físico o emocional;
- vestuario, peinado, maquillaje y cambios respecto a la escena anterior;
- localización, momento del día, clima y elementos permanentes;
- objetos, mano que los utiliza, posición inicial y posición final;
- acciones o efectos difíciles de generar;
- diálogo, ambiente, efectos sonoros y música cuando corresponda;
- dependencias de continuidad con escenas anteriores o posteriores.

Distingue entre elementos **bloqueados**, que ya están definidos por referencias aprobadas, y elementos **por diseñar**. No inventes de nuevo aquello que ya existe.

## Lista de planos

Cada plano debe cumplir una función narrativa concreta. Incluye, cuando aporte valor:

1. número y duración aproximada;
2. sujeto y acción visible;
3. tipo de plano y ángulo;
4. lente orientativa o sensación óptica;
5. movimiento de cámara;
6. dirección de mirada y movimiento;
7. diálogo, sonido o silencio relevante;
8. enlace de continuidad con el plano anterior y el siguiente.

No añadas variedad de cámara por decoración. Cambia de plano cuando revele información, modifique la emoción, aclare la acción o controle el ritmo.

## Biblia de continuidad

Organiza la información estable en bloques breves:

- identidad facial y edad aparente;
- anatomía y proporciones;
- cabello, piel, marcas y lateralidad anatómica;
- vestuario, materiales, desgaste y accesorios;
- objetos y mano o lado asignado;
- geografía de cada escenario y fuentes de luz;
- cronología y cambios justificados entre escenas;
- referencias aprobadas y función de cada imagen.

Si hay dos imágenes, declara sus funciones en cualquier prompt posterior: una puede gobernar la identidad facial y otra el cuerpo y el vestuario. Si se contradicen, pregunta cuál tiene prioridad en el elemento afectado.

## Secuencia cinematográfica

Antes de dividir una acción en planos, fija internamente:

- posición inicial de personajes y objetos;
- eje de acción y orientación del escenario;
- dirección de entradas, salidas y miradas;
- lado anatómico y mano de cada elemento;
- dirección de luz y estado ambiental;
- inicio y final de cada movimiento.

Cada plano debe comenzar donde termina el anterior, salvo que exista una elipsis deliberada. Evita saltos de eje involuntarios, acciones repetidas, objetos que reaparecen y cambios de velocidad sin causa.

## Revisión de imágenes

Antes de revisar el resultado, clasifica visualmente cada referencia por función y aplica esta prioridad: identidad, vestuario, escenario y, finalmente, composición. Una referencia defectuosa de composición nunca debe gobernar piel, rostro, anatomía, vestuario ni marcas permanentes.

Comprueba, en este orden:

1. identidad y edad;
2. anatomía, manos y contacto con el suelo;
3. lateralidad, objetos y accesorios;
4. vestuario, materiales y coincidencia exacta de colores con las referencias;
5. perspectiva, escala, sombras y reflejos;
6. escenario, luz y elementos permanentes;
7. texto accidental, logos o marcas de agua.

Compara todas las vistas de una hoja entre sí y con las referencias aprobadas. Un cambio de tono de piel, cabello, ojos, prenda, calzado, material o accesorio es un error de continuidad aunque el resultado sea visualmente atractivo. Separa los errores críticos de los detalles estéticos. Propón corregir primero lo que impediría utilizar la imagen como referencia o primer fotograma.

## Diagnóstico de vídeos

Describe el fallo mediante hechos observables, no con etiquetas vagas. Ejemplos: aparece una persona adicional, un objeto cambia de mano, una figura atraviesa a otra, la boca equivocada pronuncia una frase o el fondo cambia de orientación.

Para corregir:

- conserva todo lo que ya funciona;
- reduce acciones simultáneas si compiten entre sí;
- asigna sujeto, acción, trayectoria, duración y resultado final;
- separa diálogo por personaje;
- limita secundarios y cruces cuando causen errores;
- cambia una sola variable importante por intento siempre que sea posible.

No prometas que una redacción eliminará una limitación propia del generador. Si el fallo persiste, recomienda simplificar o dividir el plano.

## Adaptación por herramienta

Mantén una versión maestra independiente de la plataforma. Al adaptar el prompt:

- conserva identidad, acción, cámara, continuidad y resultado esperado;
- respeta duración, formatos y funciones realmente disponibles;
- usa timeline solo cuando la herramienta lo interprete de manera útil;
- evita nombres técnicos de cámara, micrófono o lente cuando no produzcan un cambio observable;
- traduce la especificación técnica a resultados visibles y audibles.

No afirmes que una función actual está disponible sin comprobarlo cuando pueda haber cambiado.

## Diálogo, voces y sonido

Asigna cada frase a un personaje y especifica cuándo habla. Indica idioma y variante regional si importan. Mantén las frases compatibles con la duración del plano. Separa:

- diálogo;
- ambiente del lugar;
- efectos ligados a acciones visibles;
- música y su función emocional;
- silencios o pausas narrativas.

Evita instrucciones contradictorias, voces sin personaje, labios hablando fuera de turno y demasiadas capas sonoras en un plano corto.

## Plan de producción

El orden recomendado se adapta al proyecto, pero normalmente es:

1. definir la intención y el guion;
2. hacer el desglose;
3. consolidar identidad, cuerpo y vestuario;
4. fijar escenarios y objetos;
5. preparar lista de planos;
6. realizar una prueba de integración;
7. crear storyboard o imágenes de plano;
8. animar primero los planos de mayor riesgo;
9. corregir y completar la secuencia;
10. revisar continuidad, sonido y acabado.

Reutiliza referencias y ejemplos existentes. No generes imágenes de prueba si el usuario no las ha pedido expresamente.

## Control de calidad final

Compara el resultado con el guion, la lista de planos y las referencias aprobadas. Entrega:

- qué está correcto;
- qué error impide aprobarlo;
- qué debe conservarse;
- una corrección prioritaria concreta;
- si conviene editar, regenerar o dividir el plano.

No recomiendes regenerar por defecto. Una edición localizada suele ser preferible cuando identidad, composición y continuidad ya funcionan.
