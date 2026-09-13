# Del guion a las imágenes

## Cumplimiento obligatorio

El orden del flujo, la separación entre referencias y la reconstrucción generativa de fotogramas establecidas aquí son normas obligatorias cuando corresponda. No sustituir la reconstrucción por un recorte ampliado ni saltar controles para acelerar la entrega. Si el resultado no puede compararse visualmente con el cuadro y las referencias limpias, no aprobarlo.

Utiliza este flujo cuando el usuario quiera convertir un guion, una escena o una secuencia escrita en referencias visuales, storyboards o fotogramas para vídeo.

Si el usuario está desarrollando un proyecto completo, sigue también [flujo-proyecto.md](flujo-proyecto.md) para anunciar cada apartado y guiarlo en el orden correcto. No saltes directamente del guion al storyboard: primero consolida los blueprints necesarios de personajes y objetos, y después los escenarios.

## Principio de trabajo

No generar una colección de imágenes aisladas. Extraer primero la continuidad del guion y construir un sistema de referencias reutilizables.

El usuario no necesita decidir todos los aspectos técnicos. Pregunta solo por preferencias personales que cambien sustancialmente el resultado. Si no indica estilo visual, utiliza realismo cinematográfico natural. Si no indica formato, utiliza horizontal 16:9 y 1920 × 1080.

Antes de cualquier generación pregunta si quiere:

1. solo los prompts;
2. solo las imágenes;
3. prompts e imágenes.

Mostrar ejemplos ya existentes no cuenta como generación y puede ofrecerse antes de decidir.

## Flujo desde el guion

1. Divide el material en escenas narrativas.
2. Realiza el desglose visual de cada escena.
3. Identifica qué elementos ya tienen referencias aprobadas.
4. Prepara únicamente las referencias que falten.
5. Consolida personajes, vestuario, objetos y escenarios antes de crear planos definitivos.
6. Si una escena contiene un solo plano, prepara directamente su imagen de referencia.
7. Si una escena contiene varios planos, utiliza un storyboard para diseñar la secuencia completa antes de reconstruir fotogramas individuales.
8. Reconstruye mediante generación únicamente los fotogramas aprobados del storyboard; no entregues recortes ampliados de la cuadrícula.
9. Utiliza esos fotogramas como referencias iniciales para los vídeos.

No saltes directamente a los fotogramas finales cuando falten referencias esenciales de identidad o continuidad.

## Referencias que pueden derivarse del guion

Según el contenido, prepara solo las necesarias:

- identidad facial;
- cuerpo y vestuario;
- personaje completo;
- ficha maestra;
- escenario sin personajes;
- objeto o accesorio importante;
- vehículo, criatura o elemento recurrente;
- relación de escala entre personajes y entorno;
- imagen de situación inicial de una escena.

Las descripciones del guion orientan el diseño, pero una imagen aprobada posterior se convierte en la fuente principal para ese elemento.

## Escenas con varios planos

Cuando la escena incluya diferentes encuadres, ángulos o momentos consecutivos, crea un storyboard coherente. Para VitaeFluxum, el formato principal es una cuadrícula 3×3 de nueve planos iguales y numerados del 1 al 9.

Antes del storyboard fija:

- objetivo narrativo de la escena;
- posición inicial y final de los personajes;
- eje de acción y orientación del escenario;
- dirección de miradas y desplazamientos;
- mano y lado anatómico de objetos y marcas;
- estado del vestuario, objetos y entorno;
- dirección de luz y momento del día;
- progresión emocional y ritmo.

Los nueve cuadros no deben ser nueve imágenes decorativas. Deben formar una secuencia filmable en la que cada plano aporte información, emoción o avance de acción.

Si el guion necesita menos de nueve momentos, utiliza los cuadros restantes para cobertura útil, reacciones, detalles o transiciones sin inventar una subtrama. Si necesita más, divide la escena en dos storyboards o en bloques narrativos coherentes.

## De storyboard a vídeo

Después de aprobar el storyboard:

1. el usuario elige uno o varios números;
2. utiliza el cuadro seleccionado únicamente como guía de composición y reconstrúyelo mediante generación a resolución máxima, sin mezclarlo con los demás;
3. revisa identidad, composición, lateralidad, vestuario, color y escenario;
4. prepara el prompt de vídeo específico para ese plano;
5. conserva el final de un plano como continuidad para el siguiente cuando sea necesario.

No generes automáticamente los nueve fotogramas independientes. Pregunta cuáles necesita el usuario para evitar generaciones innecesarias.

## Entrega por fases

En proyectos largos, entrega primero un resumen compacto con:

- escenas detectadas;
- referencias disponibles;
- referencias que faltan;
- escenas de un solo plano;
- escenas que necesitan storyboard;
- riesgos de continuidad o generación;
- siguiente pieza recomendada.

Espera la elección del usuario antes de iniciar las generaciones.
