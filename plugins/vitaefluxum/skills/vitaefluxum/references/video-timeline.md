# Prompts de vídeo amb timeline

## Caràcter obligatori per a Grok

Quan el destí sigui Grok, l'estructura, els bloquejos, la selecció mínima de referències, el control d'àudio, la física, la continuïtat i la validació definits aquí són requisits obligatoris, no suggeriments. No els ometis ni els substitueixis per una interpretació lliure. Els blocs opcionals només es poden eliminar quan el document ho autoritza expressament. Si una condició no es pot comprovar en el vídeo generat, la prova queda pendent o fallida, mai aprovada per inferència.

Utilitza aquesta referència quan calgui animar una imatge, generar un vídeo, conservar un personatge o continuar un clip.

## Criteris pràctics

- El model interpreta el prompt aproximadament segons l'ordre temporal del vídeo.
- Utilitza un màxim de tres intervals per a clips curts.
- Assigna una única acció dominant a cada interval.
- Protegeix primer la identitat i la composició; després descriu el moviment.
- No tornis a descriure tota la imatge: indica només què es mou i què no pot canviar.
- Utilitza un únic moviment de càmera motivat.
- Especifica sons concrets. Si no hi ha veu, prohibeix el diàleg i el moviment de llavis.
- Per preservar millor la cara, prefereix accions petites, càmera suau i clips de 6 a 10 segons.

## Regla específica para Grok

Cuando el destino sea Grok, utilizar obligatoriamente la plantilla siguiente como base real. Completar únicamente los apartados necesarios y eliminar por completo cualquier bloque opcional que no corresponda. No sustituirla por un prompt improvisado ni combinarla con otras plantillas completas.

Antes de redactarla, revisar visualmente las referencias y asignar a cada una una sola función. Dentro del prompt, mencionar cada referencia mediante el identificador real que Grok haya asignado al seleccionarla con `@`. No inventar nombres, números de imagen ni identificadores. No usar el nombre narrativo del personaje u objeto si puede confundirse con el identificador de Grok.

## Plantilla maestra de vídeo para Grok

```text
[GENERATION GOAL]

Crear un vídeo de [6 / 10 / 15] segundos en el que [SUJETO PRINCIPAL] [ACCIÓN PRINCIPAL] y termina [ESTADO FINAL DEL PLANO]. Tono [TONO], ritmo [RITMO] y objetivo narrativo [OBJETIVO].

[REFERENCE ASSET ROLES]

@[IDENTIFICADOR REAL]: primer fotograma; controla exclusivamente el estado visual inicial, la composición y la posición inicial.
@[IDENTIFICADOR REAL]: blueprint del personaje; controla identidad, edad, cuerpo, piel, cabello, barba y marcas permanentes.
@[IDENTIFICADOR REAL]: blueprint de [OBJETO O VEHÍCULO]; controla diseño, escala, materiales, estado y orientación.
@[IDENTIFICADOR REAL]: referencia del escenario; controla arquitectura, distribución y elementos permanentes.
@[IDENTIFICADOR REAL]: último fotograma; controla exclusivamente el estado final. [ELIMINAR ESTA LÍNEA Y TODO EL BLOQUE FINAL FRAME SI NO ES NECESARIO].

Incluir únicamente las referencias imprescindibles. No asignar dos funciones incompatibles a la misma referencia.

[REFERENCE PRIORITY AND QUALITY CHECK]

Antes de generar, comprobar visualmente que las referencias no contienen identidad degradada, piel plástica, anatomía incorrecta, sangre o heridas no deseadas, objetos deformados, arquitectura incorrecta ni reflejos accidentales.

Prioridad obligatoria: blueprint de identidad > blueprint de vestuario u objeto > referencia del escenario > fotograma de composición > primer y último fotograma para sus estados temporales. Si un fotograma contiene defectos, conservar únicamente su cámara, postura, perspectiva y distribución; recuperar identidad, piel, cuerpo y vestuario de los blueprints limpios.

[SUBJECTS AND RELATIONSHIPS]

Elementos que pueden moverse: [SUJETOS U OBJETOS].
Elementos completamente inmóviles: [SUJETOS, VEHÍCULOS Y ELEMENTOS DEL FONDO].
Posición inicial: [DESCRIPCIÓN].
Trayectoria: [INICIO, RECORRIDO Y FINAL].
Mano derecha anatómica: [OBJETO O ACCIÓN].
Mano izquierda anatómica: [OBJETO O ACCIÓN].
Relación espacial entre personajes, vehículos y escenario: [DESCRIPCIÓN].
Elementos que no pueden aparecer: [DESCRIPCIÓN].

[EVENT SCRIPT]

0.0–[T1] s — Inicio y estabilización: [UNA ÚNICA ACCIÓN DOMINANTE].
[T1]–[T2] s — Acción principal: [UNA ÚNICA ACCIÓN DOMINANTE].
[T2]–[FINAL] s — Reacción o cierre: [UNA ÚNICA ACCIÓN DOMINANTE Y ESTADO FINAL].

Utilizar un máximo de tres intervalos. No repetir una acción en varios apartados ni acumular más acontecimientos de los que caben físicamente en la duración.

[CONTINUITY LOCK]

Mantener exactamente identidad, edad, cuerpo, piel, cabello, barba, vestuario, accesorios, marcas permanentes, lateralidad anatómica, objeto asignado a cada mano, arquitectura, perspectiva, iluminación, sombras, reflejos, clima y estado de los vehículos y del fondo.

El primer fotograma debe coincidir exactamente con @[IDENTIFICADOR INICIAL]. No rediseñar, embellecer, rejuvenecer ni reinterpretar ningún elemento bloqueado.

[CAMERA]

La cámara realiza un único movimiento motivado: [MOVIMIENTO, TRAYECTORIA Y FINAL]. La cámara acompaña la acción, pero su movimiento es físicamente independiente del movimiento del sujeto. El personaje o vehículo mantiene una velocidad natural y no la modifica para conservar una distancia constante con la cámara.

Sin zoom digital, vibraciones aleatorias, cambios de lente, cortes ni reencuadres innecesarios. Si la cámara es fija, el escenario también permanece completamente fijo y no se desplaza para simular movimiento.

[MOVEMENT, ANATOMY AND PHYSICS]

[PARA PERSONAS, INCLUIR SOLO SI CORRESPONDE]
Movimiento con peso, equilibrio, gravedad, contacto correcto con el suelo y coordinación natural. Manos y dedos mantienen anatomía, agarre y asignación correctos. Ropa y cabello reaccionan únicamente al movimiento, viento y gravedad descritos.

[PARA VEHÍCULOS, INCLUIR SOLO SI CORRESPONDE]
Ruedas con rotación proporcional a la velocidad y dirección; neumáticos en contacto con la superficie; suspensión, transferencia de peso e inercia físicamente coherentes; trayectoria estable y velocidad compatible con la distancia recorrida.

Eliminar el bloque que no corresponda. No añadir reglas de vehículos a una escena sin vehículos.

[SKIN AND MATERIALS]

Piel humana fotografiada, con poros sutiles, irregulares y moderados, líneas de expresión propias de la edad, variaciones cromáticas naturales, brillo controlado y transición natural entre barba y piel. Sin filtro de belleza, HDR facial, textura excesiva ni microdetalle artificial.

Materiales de ropa, objetos, vehículos y arquitectura con grosor, reflejos, desgaste y respuesta a la luz físicamente plausibles.

[ENVIRONMENT LOCK]

Mantener fija la arquitectura, la distribución, la perspectiva y todos los elementos permanentes del escenario.

[SI EL ESCENARIO ESTÁ ABANDONADO, INCLUIR]
No aparecen personas nuevas, animales ni vehículos nuevos. No hay tráfico. Los vehículos estacionados permanecen apagados, vacíos e inmóviles: las ruedas no giran, las luces no se encienden, las puertas no se abren y no emiten humo. El fondo no se mueve, no se desliza y no inventa nuevos edificios, calles u objetos cuando avanza el sujeto.

[AUDIO]

Generar únicamente sonidos diegéticos con una fuente física visible o justificable.
Ambiente: [VIENTO, LLUVIA, REVERBERACIÓN REAL DEL LUGAR U OTRO].
Acciones: [MOTOR, NEUMÁTICOS, PASOS, RESPIRACIÓN, ROPA, PUERTAS U OBJETOS].

Sin música, instrumentos, melodías, percusión, drones, risers, pulsaciones, impactos cinematográficos, efectos artificiales de terror ni sonidos sin fuente física real.

[SI NO HAY DIÁLOGO]
Sin voces, palabras ni murmullos. La boca permanece relajada y cerrada.

[SI HAY DIÁLOGO]
@[IDENTIFICADOR DEL PERSONAJE] dice exactamente: «[FRASE]». Idioma: [IDIOMA Y VARIANTE]. Acento: [ACENTO]. Intención y tono: [DESCRIPCIÓN]. [HABLA SOLO / HABLA CON PERSONAJE IDENTIFICADO]. La boca se mueve únicamente mientras pronuncia la frase. No inventar, repetir, traducir ni modificar palabras.

Eliminar una de las dos opciones de diálogo antes de entregar el prompt.

[TEXT CONTROL]

Sin subtítulos, rótulos, créditos, interfaces, letras añadidas, logotipos ni marcas de agua. Conservar únicamente el texto físico ya existente en el escenario cuando esté definido por una referencia y sea narrativamente necesario.

[FINAL FRAME]

Terminar coincidiendo físicamente con @[IDENTIFICADOR FINAL]. Este recurso controla exclusivamente el estado final. La acción y el movimiento de cámara deben llegar de forma continua y plausible a esa posición, postura, encuadre y distribución.

Sin morphing, transformación del escenario, teletransporte, aparición repentina ni desaparición de elementos. [ELIMINAR COMPLETAMENTE ESTE BLOQUE SI NO SE UTILIZA UNA REFERENCIA FINAL].

[NEGATIVE CONSTRAINTS]

Errores específicos más probables de este plano: [ENUMERAR SOLO LOS PERTINENTES].
Evitar además, únicamente cuando sea relevante: cambio de identidad o vestuario, lateralidad incorrecta, objeto en la mano equivocada, extremidades deformes, elementos duplicados o ausentes, morphing, cámara errática, fondo deslizante, iluminación cambiante, piel plástica, patrones grabados, exceso de enfoque, texto accidental, subtítulos, logotipos y marcas de agua.
```

## Comprobación antes de entregar el prompt de Grok

- El objetivo cabe en 6, 10 o 15 segundos y contiene una sola acción dominante.
- Cada referencia tiene una única función y utiliza su identificador real con `@`.
- No se ha inventado ningún identificador.
- Se han eliminado referencias y bloques opcionales innecesarios.
- La cámara y el sujeto se mueven de forma independiente y físicamente plausible.
- El escenario conserva su geometría; si está abandonado, no aparecen elementos vivos o móviles no solicitados.
- El audio es exclusivamente diegético y cada sonido tiene una fuente real.
- Si no existe frame final, no queda ninguna mención a él.
- Si existe, la acción llega físicamente a ese estado sin morphing.
- Las restricciones negativas empiezan por los fallos específicos del plano y no repiten prohibiciones innecesariamente.

## Continuació d'un vídeo

Descriu primer l'estat exacte de l'últim fotograma i després només l'acció següent. No repeteixis tota la història ni el prompt original.

```text
Continuar directamente desde el último fotograma del vídeo anterior. En el primer fotograma, [ESTADO EXACTO DEL PERSONAJE, OBJETOS, CÁMARA Y ESCENARIO].

[TIMELINE]
0–[A] segundos: [ACCIÓN].
[A]–[FINAL] segundos: [ACCIÓN Y POSICIÓN FINAL].

Mantener exactamente los mismos personajes, rostros, ropa, objetos, iluminación, escenario, dirección de movimiento y estilo de cámara. Transición continua y natural, sin salto, morphing ni reinicio de la acción.
```

Cuando la continuación se genere en Grok, no utilizar este bloque aislado: integrarlo dentro de la plantilla maestra de Grok y tratar el último fotograma aprobado del clip anterior como `@[IDENTIFICADOR REAL]: primer fotograma`.
