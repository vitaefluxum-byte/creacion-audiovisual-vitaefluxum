# PROMPTS MAESTROS — PERSONAJES REALISTAS Y CONSISTENTES

Versión optimizada para evitar personajes excesivamente perfectos, piel plástica, estética publicitaria y apariencia de render. Sustituye los campos entre corchetes antes de generar.

## USO OBLIGATORIO DE LOS BLOQUES

Cuando una petición coincida con uno de estos flujos, utilizar el bloque correspondiente como base real, completar sus campos y conservar su lógica, prioridades y validación. Se pueden eliminar apartados opcionales que no correspondan y añadir restricciones específicas, pero no sustituir el bloque por un prompt improvisado. Seleccionar únicamente un flujo por generación: blueprint, personaje integrado, escenario, storyboard, reconstrucción o reparación.

Todas las reglas universales, jerarquías, controles y validaciones de este documento son **obligatorias y no interpretables como sugerencias**. Deben aplicarse tanto al preparar el prompt como al revisar el resultado. No pueden omitirse por brevedad ni porque la imagen parezca atractiva. Si un requisito no puede verificarse visualmente, el resultado no se aprueba.

## REGLA UNIVERSAL DE LATERALIDAD Y CONTINUIDAD

En todos los prompts de este documento, las palabras **derecha** e **izquierda** se refieren siempre al lado anatómico del personaje, nunca al lado del espectador ni al lado de la imagen.

Antes de generar, fijar internamente una tabla de continuidad con:

- marcas corporales y lado anatómico exacto;
- mano asignada a cada arma, herramienta u objeto;
- lado del cuerpo donde se lleva cada funda, bolsa, correa, prótesis, joya o accesorio;
- elementos asimétricos del rostro, cabello, cuerpo y vestuario;
- estado, orientación y posición inicial de cada elemento.

Aplicar esa tabla en todas las vistas y fotogramas. No reflejar, duplicar, trasladar, intercambiar ni hacer desaparecer ningún elemento lateral. Un cambio de mano o de lado solo está permitido cuando el usuario lo solicite expresamente o cuando la acción narrativa muestre claramente el traslado.

Correspondencia anatómica obligatoria en hojas de vistas:

- vista frontal: el lado derecho del personaje aparece a la izquierda del espectador;
- perfil anatómico izquierdo: la cámara observa el lado izquierdo; brazo, marcas y objetos izquierdos quedan en primer término y los derechos al lado opuesto;
- perfil anatómico derecho: la cámara observa el lado derecho; brazo, marcas y objetos derechos quedan en primer término y los izquierdos al lado opuesto;
- vista posterior: el lado derecho del personaje aparece a la derecha del espectador.

Nunca deducir el lado por la posición aparente dentro de la imagen. Verificarlo anatómicamente antes de generar siguiendo la orientación del cuerpo y, cuando corresponda, la continuidad física desde hombro, brazo, codo, antebrazo y muñeca hasta la mano, o desde cadera, pierna y tobillo hasta el pie.

Esta regla no se limita a las manos. Se aplica a cualquier elemento lateral del personaje: ojos, cejas, orejas, mejillas, cicatrices, tatuajes, lunares, heridas, zonas del cabello, brazos, piernas, manos, pies, ropa asimétrica, relojes, pulseras, pendientes, anillos, fundas, bolsas, armas, accesorios y objetos.

Si una extremidad asignada a un objeto queda fuera de plano u oculta por el cuerpo, el objeto debe quedar igualmente fuera de plano u oculto total o parcialmente. No cambiarlo de lado ni inventar una mano o extremidad para mantenerlo visible.

Esta comprobación es una obligación interna del plugin tanto al generar como al revisar y también cuando el usuario solicita únicamente un prompt para utilizar fuera de VitaeFluxum. En el prompt entregado basta con expresar las asignaciones laterales concretas necesarias; no es obligatorio copiar toda esta regla interna.

## CONTROL DE COHERENCIA OBLIGATORIO ANTES DE ENTREGAR

Esta regla se aplica a **todos los prompts** del documento.

La primera generación se considera un borrador interno, no un resultado final. Antes de mostrar o entregar una imagen, revisar visualmente todos los personajes, vistas, paneles y fotogramas mediante esta lista:

1. misma identidad facial, edad y proporciones;
2. mismo cabello, peinado y longitud;
3. lateralidad anatómica correcta;
4. tatuajes, cicatrices, lunares y marcas en el lado exacto;
5. armas, herramientas y objetos en la mano y lado asignados;
6. vestuario, correas, bolsillos, fundas, accesorios, materiales, desgaste y colores sin cambios;
7. manos, dedos, brazos, piernas y pies anatómicamente válidos, conectados y con continuidad física hasta el cuerpo;
8. número, orden y orientación correctos de las vistas o paneles;
9. escenario, iluminación, perspectiva y elementos permanentes coherentes;
10. ausencia de duplicaciones, desapariciones, reflejos horizontales o intercambios accidentales.
11. ausencia de patrones artificiales repetitivos en piel, pavimento, paredes, ropa, vegetación, agua, suciedad, escombros y demás superficies.

Seguir visualmente cada extremidad completa en lugar de confiar en lo que decía el prompt. Rechazar cualquier mano o extremidad flotante, desconectada, duplicada, fusionada, amputada accidentalmente o añadida para mostrar un objeto. Si la conexión anatómica o el lado no pueden verificarse con seguridad porque quedan ocultos, marcar el resultado como ambiguo y no aprobarlo como correcto.

Comparar también los colores del resultado con las referencias bajo una iluminación equivalente: piel, ojos, cabello, prendas, calzado, materiales, objetos y accesorios. No aceptar como coherente un color simplemente parecido si la referencia ya lo define.

Las superficies naturales deben presentar variaciones no periódicas de forma, tamaño, orientación, separación e intensidad. Rechazar motivos circulares, geométricos, grabados, clonados o procedurales repetidos, aunque solo resulten visibles al ampliar la imagen o después de aplicar nitidez.

Si falla un solo punto, **no aprobar la imagen como resultado final**. Identificar el elemento afectado y conservar intacto todo lo que ya sea correcto. Antes de consumir otra generación, informar al usuario del fallo y obtener autorización para corregirlo, salvo que ya haya autorizado expresamente un proceso iterativo. Después de la corrección, repetir la revisión completa.

Entregar la imagen únicamente cuando sea coherente. Si después de varios intentos no puede corregirse sin provocar nuevos errores, explicar qué incoherencia persiste y no presentarla como versión aprobada.

Si una corrección deteriora una zona que antes era correcta o introduce patrones repetitivos, rechazar la imagen completa aunque el defecto principal se haya corregido. No encadenar otra reparación sobre ese resultado: volver a la mejor referencia original y a los blueprints limpios para realizar una generación nueva. Reservar la reparación localizada para defectos puntuales cuando todo lo demás permanezca verdaderamente intacto.

## PRIORIDAD DE LAS REFERENCIAS Y REGLA DE NO INVENTAR

Antes de generar, revisar visualmente todas las referencias y clasificar cada una según su función: identidad y cuerpo, vestuario, escenario, composición o postura, primer fotograma, último fotograma, objeto u objetivo de edición.

Aplicar obligatoriamente esta jerarquía:

1. El blueprint de identidad controla rostro, edad, cuerpo, piel, cabello, barba y marcas permanentes.
2. El blueprint de vestuario controla ropa, calzado, accesorios, materiales y desgaste.
3. La referencia del escenario controla arquitectura, distribución y elementos permanentes.
4. El fotograma o storyboard controla composición, cámara, postura y acción.
5. El primer y el último fotograma controlan exclusivamente los estados inicial y final del vídeo.

Si dos referencias se contradicen, no mezclar automáticamente sus rasgos. Aplicar esta jerarquía o advertir del conflicto cuando el usuario haya pedido una excepción.

Rechazar como fuente de identidad cualquier defecto visible: piel plástica, patrones artificiales o repetitivos, identidad degradada, anatomía incorrecta, sangre accidental, heridas no deseadas, objetos deformados o arquitectura incorrecta.

> Si una imagen de composición contiene defectos visuales, utilizarla únicamente para recuperar cámara, postura, perspectiva y distribución espacial. La identidad, el rostro, la piel, el cuerpo, el vestuario y las marcas permanentes deben proceder de blueprints limpios. Nunca reproducir un defecto solamente porque aparece en una imagen anterior.

Si una imagen aprobada ya muestra el rostro, cuerpo, cabello, ropa, calzado, accesorios, objetos o escenario, esos elementos quedan bloqueados y deben conservarse exactamente. No inventar, rediseñar, modernizar, embellecer, sustituir ni añadir elementos que ya estén definidos.

Inventar únicamente la información que no aparece en las referencias y que sea imprescindible para completar el resultado. Toda invención debe ser conservadora, compatible con lo visible y mantenerse después como parte de la continuidad.

En particular, un blueprint de vestuario creado a partir de un personaje existente debe reproducir la ropa que lleva ese personaje. Solo diseñar ropa nueva cuando el usuario lo solicite expresamente.

---

## EJEMPLOS VISUALES DISPONIBLES

Los nombres, la numeración, las explicaciones y las imágenes de ejemplo se mantienen exclusivamente en [catalogo-blueprints.md](catalogo-blueprints.md). Cuando el usuario pida verlos o compararlos, utiliza ese documento y no reconstruyas el catálogo desde este archivo.

---

## 1. BLUEPRINT MAESTRO DE IDENTIDAD FACIAL REALISTA

```text
[OBJETIVO]

Crear una hoja horizontal profesional de identidad facial para preproducción cinematográfica. Debe mostrar una única persona real y reconocible desde diferentes ángulos. La prioridad absoluta es conservar la identidad, la geometría del rostro y las marcas distintivas; no embellecer ni idealizar al personaje.

[DATOS DEL PERSONAJE]

Nombre: [NOMBRE]
Género: [GÉNERO]
Edad aparente exacta: [EDAD]
Origen o rasgos físicos: [DESCRIPCIÓN]
Color y forma de los ojos: [DESCRIPCIÓN]
Cabello: [COLOR, CORTE, DENSIDAD, CANAS, ENTRADAS]
Vello facial: [DESCRIPCIÓN O NINGUNO]
Tono y textura de piel: [DESCRIPCIÓN]

[ANCLAS DE IDENTIDAD — OBLIGATORIAS]

Mantener en todas las vistas exactamente las mismas características reconocibles:

- forma general del cráneo y del rostro;
- distancia entre los ojos;
- forma de párpados y cejas;
- longitud y forma de la nariz;
- labios, mandíbula, mentón, pómulos y orejas;
- línea de nacimiento del cabello;
- edad aparente;
- marcas identificativas permanentes.

Marcas distintivas del personaje: [EJ.: OJO DERECHO LIGERAMENTE MÁS CERRADO, PEQUEÑA CICATRIZ EN LA CEJA IZQUIERDA, NARIZ LEVEMENTE DESVIADA, LUNAR EN LA MEJILLA, CANAS EN LAS SIENES].

Registrar cada marca con su lado anatómico exacto. En todas las vistas, derecha e izquierda pertenecen al personaje. No reflejar una cicatriz, lunar, piercing, tatuaje, mechón o asimetría al girar la cabeza; tampoco duplicarlo en ambos lados.

Las asimetrías deben ser sutiles, naturales y anatómicamente plausibles. No corregirlas ni cambiarlas entre vistas.

[APARIENCIA HUMANA NATURAL]

Mostrar piel propia de una persona de [EDAD] años: variación natural del tono, poros visibles de forma moderada, líneas de expresión coherentes con la edad, pequeñas irregularidades y ojeras suaves si corresponden. Dientes naturales, no perfectamente uniformes ni artificialmente blancos. Cabello con densidad realista, pequeños cabellos sueltos y separación irregular de mechones.

No aplicar filtros de belleza. No rejuvenecer. No adelgazar el rostro. No agrandar los ojos. No perfeccionar la mandíbula, la nariz, los labios, los dientes ni la simetría facial.

[COMPOSICIÓN]

Fondo gris claro uniforme, sin interfaz sci-fi y sin decoración innecesaria. Iluminación de estudio neutra, suave y difusa, con balance de blancos natural. Cámara ortográfica o perspectiva mínima, lente aproximada de 85 mm para reducir distorsión facial.

Fila superior, seis vistas de la misma cabeza, a igual escala:

1. frontal;
2. tres cuartos izquierda;
3. perfil izquierdo exacto;
4. vista posterior;
5. perfil derecho exacto;
6. tres cuartos derecha.

Expresión neutra y relajada. Boca cerrada sin tensión. La vista frontal mira a cámara; las demás respetan el ángulo correspondiente.

Fila inferior:

- un primer plano frontal de identidad;
- cinco expresiones moderadas: neutra, concentración, preocupación contenida, determinación y sonrisa leve natural;
- pequeños detalles de las marcas distintivas permanentes.

[CALIDAD VISUAL]

Fotografía humana natural de alta resolución, detalle facial realista, textura de piel no retocada, exposición equilibrada, sombras suaves, color neutro y materiales físicamente creíbles. Nitidez concentrada en ojos y rostro, con caída óptica natural. Debe parecer una sesión real de casting y continuidad para cine, no una ilustración, un anuncio de belleza, un videojuego ni un render 3D.

[TEXTO]

Si el modelo genera texto correctamente, permitir únicamente:

NOMBRE: [NOMBRE]
EDAD: [EDAD]
OJOS: [COLOR]
PELO: [COLOR]

Si no puede reproducir texto con precisión, omitir todo el texto antes que generar letras incorrectas.

[EVITAR]

identidad diferente entre vistas, cambio de edad, cambio de marcas faciales, simetría facial perfecta, asimetría extrema o anatómicamente incorrecta, piel plástica, piel de porcelana, piel encerada, maquillaje glamur, retoque de belleza, ojos de muñeca, iris luminosos, pestañas exageradas, labios aumentados, dientes perfectos, sonrisa publicitaria, mandíbula heroica, cuerpo o rostro de modelo, iluminación glamur, HDR agresivo, halos, exceso de enfoque, textura de piel exagerada, CGI, render 3D, estética de videojuego, anime, caricatura, deformaciones, texto corrupto, marcas de agua.

[VALIDACIÓN ANTES DE ENTREGAR]

Aplicar el CONTROL DE COHERENCIA OBLIGATORIO del inicio del documento. No entregar la hoja si una vista cambia la identidad, la edad, una marca o su lado anatómico.

Formato horizontal 16:9. Resolución máxima disponible.
```

---

## 2. BLUEPRINT LIMPIO DE ROSTRO — CUATRO PERFILES

```text
[OBJETIVO]

Crear una hoja horizontal limpia con exactamente cuatro vistas de la misma cabeza humana: frontal, perfil izquierdo puro, perfil derecho puro y posterior. Debe funcionar como referencia de identidad para generar imágenes y vídeos consistentes.

[REFERENCIA DE IDENTIDAD]

Utilizar la imagen o descripción proporcionada como fuente principal. Conservar edad, geometría del cráneo, rasgos faciales, orejas, cuello, línea del cabello, peinado, vello facial, tono de piel y marcas distintivas.

Personaje: [DESCRIPCIÓN COMPLETA]
Marcas permanentes: [DESCRIPCIÓN]

[LATERALIDAD ANATÓMICA]

Asignar cada marca al lado anatómico exacto del personaje. En el perfil izquierdo solo deben quedar en primer término las marcas del lado izquierdo; en el perfil derecho, las del lado derecho. Las marcas del lado opuesto pueden quedar ocultas por el volumen de la cabeza, pero nunca deben trasladarse, reflejarse ni duplicarse.

[COMPOSICIÓN]

- exactamente cuatro cabezas completas;
- misma escala y altura;
- separación uniforme;
- fondo gris claro uniforme;
- iluminación neutra, frontal-difusa y constante;
- lente aproximada de 85 mm;
- expresión neutra;
- sin perspectiva dramática;
- sin vistas tres cuartos;
- sin paneles secundarios, macros, flechas, escalas ni decoración.

Los perfiles deben estar girados exactamente 90 grados. La vista posterior debe mostrar coronilla, forma posterior del cráneo, implantación del cabello, nuca y ambas orejas.

[REALISMO]

Persona cotidiana y creíble. Conservar asimetrías faciales sutiles y naturales, poros moderados, textura propia de la edad, cabello irregular y marcas identificativas. No embellecer, rejuvenecer ni corregir rasgos.

[EVITAR]

persona diferente entre vistas, rostro idealizado, simetría perfecta, cambio de nariz, orejas, mandíbula, peinado o edad, piel plástica, ojos artificialmente brillantes, iluminación cinematográfica, pose de modelo, deformación, cabeza recortada, vistas adicionales, texto, números, símbolos, logotipos, marcas de agua, CGI, anime, ilustración.

[VALIDACIÓN ANTES DE ENTREGAR]

Aplicar el CONTROL DE COHERENCIA OBLIGATORIO. No entregar hasta comprobar que ambos perfiles corresponden al lado anatómico correcto y que ninguna marca ha sido reflejada o duplicada.

Formato horizontal 16:9. Resolución máxima disponible.
```

---

## 2B. BLUEPRINT LIMPIO DE PERSONAJE COMPLETO — CUATRO VISTAS

```text
[OBJETIVO]

Crear una hoja horizontal profesional y minimalista con exactamente cuatro vistas de cuerpo completo del mismo personaje humano: frontal, perfil izquierdo puro, perfil derecho puro y posterior. La hoja debe servir como referencia precisa de identidad facial, anatomía, proporciones corporales, postura, cabello y vestuario para generar imágenes y vídeos consistentes.

[DATOS DEL PERSONAJE]

Nombre: [NOMBRE]
Género: [GÉNERO]
Edad aparente exacta: [EDAD]
Altura: [ALTURA]
Constitución física: [MEDIA / DELGADA NO ATLÉTICA / ATLÉTICA NATURAL / ROBUSTA / LIGERO SOBREPESO / OTRA]
Proporciones corporales: [DESCRIPCIÓN]
Rostro: [DESCRIPCIÓN]
Ojos: [DESCRIPCIÓN]
Cabello: [DESCRIPCIÓN]
Vello facial: [DESCRIPCIÓN O NINGUNO]
Piel: [DESCRIPCIÓN]
Marcas distintivas permanentes: [DESCRIPCIÓN]
Vestuario: [DESCRIPCIÓN EXACTA]
Calzado: [DESCRIPCIÓN EXACTA]
Accesorios: [DESCRIPCIÓN O NINGUNO]

Mapa de lateralidad obligatorio:

- marcas del lado derecho: [DESCRIPCIÓN O NINGUNA];
- marcas del lado izquierdo: [DESCRIPCIÓN O NINGUNA];
- objeto o accesorio de la mano derecha: [DESCRIPCIÓN O NINGUNO];
- objeto o accesorio de la mano izquierda: [DESCRIPCIÓN O NINGUNO];
- accesorios fijados al lado derecho del cuerpo: [DESCRIPCIÓN O NINGUNO];
- accesorios fijados al lado izquierdo del cuerpo: [DESCRIPCIÓN O NINGUNO].

[ANCLAS DE IDENTIDAD]

Las cuatro vistas deben representar exactamente a la misma persona observada desde distintos ángulos. Mantener sin reinterpretar:

- geometría del cráneo y del rostro;
- forma, tamaño y posición de ojos, cejas, nariz, labios, mandíbula, mentón, pómulos y orejas;
- edad aparente y textura natural de la piel;
- línea de implantación, longitud, densidad y peinado;
- marcas faciales y corporales permanentes;
- altura y longitud relativa de torso, brazos y piernas;
- anchura de hombros, cintura y caderas;
- volumen corporal y distribución natural del peso;
- tamaño de manos y pies;
- todas las prendas, colores, materiales, costuras, bolsillos, cierres, calzado y accesorios.

Las asimetrías naturales del personaje deben mantenerse de forma coherente. No corregir, embellecer, rejuvenecer ni modificar el cuerpo entre vistas.

Antes de generar, comprobar anatómicamente cada vista. La vista frontal invierte visualmente derecha e izquierda respecto al espectador; la posterior no. En el perfil izquierdo, el lado izquierdo es el visible y queda en primer término. En el perfil derecho, el lado derecho es el visible y queda en primer término. No intercambiar armas, escudos, fundas, tatuajes, prótesis ni accesorios al cambiar de vista.

[COMPOSICIÓN OBLIGATORIA]

Mostrar exclusivamente cuatro figuras de cuerpo completo, perfectamente alineadas y con el mismo tamaño:

1. Vista frontal exacta.
2. Perfil izquierdo exacto, cuerpo y cabeza girados 90 grados.
3. Perfil derecho exacto, cuerpo y cabeza girados 90 grados.
4. Vista posterior exacta.

Las cuatro figuras deben aparecer completas desde la coronilla hasta la suela del calzado. No cortar cabeza, cabello, hombros, manos, piernas ni pies.

Utilizar:

- misma distancia de cámara;
- misma altura de cámara;
- misma focal aproximada de 70 mm para reducir distorsión corporal;
- misma escala;
- misma iluminación;
- mismo fondo;
- misma postura neutra;
- misma expresión facial neutra en las vistas donde el rostro es visible.

En la vista frontal, mirada directa a cámara. En los perfiles, mirada recta hacia el lado correspondiente, sin girar los ojos hacia la cámara. En la vista posterior, mostrar claramente la parte trasera del cráneo, cabello, nuca, hombros, espalda, brazos, ropa, piernas y calzado.

[POSTURA]

Postura anatómica natural y relajada. Cabeza recta, columna neutral, hombros relajados, brazos ligeramente separados del torso para permitir ver la silueta, manos abiertas y relajadas, dedos naturales, piernas rectas sin rigidez y pies paralelos separados a una distancia normal.

No utilizar pose militar rígida, pose de moda, pose heroica, contrapposto exagerado ni gestos dinámicos.

[REALISMO HUMANO]

El personaje debe parecer una persona real fotografiada para continuidad cinematográfica. Conservar edad real, pequeñas asimetrías plausibles, poros moderados, variación natural del tono de piel, líneas de expresión coherentes, cabello con algunos mechones sueltos y cuerpo cotidiano sin idealización automática.

La ropa debe mostrar grosor, caída, pliegues y puntos de tensión naturales. Los pliegues pueden variar únicamente cuando el cambio de ángulo físico lo exija, pero el diseño y las prendas deben ser exactamente los mismos.

[FONDO E ILUMINACIÓN]

Fondo gris claro uniforme. Suelo neutro visible con sombras de contacto suaves bajo los pies. Iluminación de estudio funcional, difusa y simétrica, balance de blancos natural, sin dramatización cinematográfica, sin contraluz y sin sombras duras.

[TEXTO]

No incluir títulos, nombres de vistas, letras, números, medidas, flechas, líneas técnicas, logotipos ni marcas de agua. La hoja debe contener exclusivamente las cuatro vistas del personaje.

[CALIDAD]

Fotografía realista de cuerpo completo, alta resolución, detalle natural en rostro, manos, cabello, ropa y calzado. Nitidez óptica realista y uniforme solo en lo necesario para documentar el personaje, sin enfoque excesivo, HDR agresivo ni textura artificial.

[EVITAR]

persona diferente entre vistas, cambio de rostro, edad, altura, cuerpo, peso, postura, peinado, marcas, ropa o accesorios; rostro idealizado; simetría facial perfecta; asimetría extrema o anatómicamente incorrecta; cuerpo de modelo; músculos añadidos; cintura imposible; pecho exagerado; piernas alargadas; manos escondidas; dedos deformes; pies recortados; perfil tres cuartos; cabeza girada hacia cámara en los perfiles; perspectivas diferentes; gran angular; pose heroica; pose de catálogo; piel plástica; maquillaje glamur; ojos artificialmente brillantes; dientes perfectos; iluminación cinematográfica; fondo decorado; paneles secundarios; primeros planos; macros; vistas adicionales; personas adicionales; texto; símbolos; logotipos; marcas de agua; CGI; render 3D; estética de videojuego; anime; ilustración.

[VALIDACIÓN ANTES DE ENTREGAR]

Aplicar el CONTROL DE COHERENCIA OBLIGATORIO. Comparar frontal, perfil izquierdo, perfil derecho y posterior; no entregar si una marca, arma, objeto, correa o accesorio cambia de lado, mano, diseño o estado.

Formato horizontal 16:9. Resolución máxima disponible.
```

---

## 3. BLUEPRINT MAESTRO DE PERSONAJE COMPLETO REALISTA

```text
[OBJETIVO]

Crear una hoja profesional de continuidad de un único personaje humano realista. Debe fijar identidad facial, cuerpo, postura, proporciones, edad, cabello y marcas permanentes antes de diseñar el vestuario o generar escenas.

[DATOS]

Nombre: [NOMBRE]
Género: [GÉNERO]
Edad aparente: [EDAD]
Altura: [ALTURA]
Constitución: [MEDIA / DELGADA NO ATLÉTICA / ATLÉTICA NATURAL / ROBUSTA / LIGERO SOBREPESO / OTRA]
Proporciones corporales: [DESCRIPCIÓN]
Postura habitual: [DESCRIPCIÓN]
Rostro: [DESCRIPCIÓN]
Cabello: [DESCRIPCIÓN]
Piel: [DESCRIPCIÓN]
Marcas distintivas: [DESCRIPCIÓN]

Mapa de lateralidad y propiedad: [INDICAR PARA CADA MARCA, PRENDA ASIMÉTRICA, PRÓTESIS, OBJETO O ACCESORIO EL LADO ANATÓMICO Y, SI CORRESPONDE, LA MANO EXACTA].

[PRIORIDAD DE IDENTIDAD]

Mantener la misma persona en todos los paneles. Conservar exactamente la relación entre cabeza, hombros, torso, brazos, manos, cintura, piernas y pies. No modificar altura, anchura de hombros, volumen corporal ni distribución natural del peso.

Conservar también la lateralidad anatómica: toda marca u objeto asignado a la derecha debe permanecer en la derecha del personaje y todo elemento izquierdo en la izquierda. No reflejar, duplicar ni intercambiar elementos entre las vistas frontal, lateral, posterior y tres cuartos.

[APARIENCIA COTIDIANA]

El personaje no debe parecer un modelo ni un superhéroe salvo que la historia lo requiera. Utilizar un cuerpo humano plausible, postura relajada, ligera distribución asimétrica del peso, hombros no perfectamente nivelados y manos descansando de forma natural. Mantener imperfecciones anatómicas normales sin introducir deformidades.

[ROPA TÉCNICA PROVISIONAL]

Utilizar prendas neutras ajustadas solo lo necesario para apreciar la anatomía: camiseta lisa gris de manga corta, pantalón oscuro recto y calzado sencillo. Sin logos, joyas ni accesorios. La ropa debe mostrar pliegues naturales y grosor real.

[COMPOSICIÓN]

Fondo gris claro uniforme e iluminación neutra difusa.

Panel principal:

- cuerpo entero frontal;
- cuerpo entero lateral;
- cuerpo entero posterior;
- cuerpo entero tres cuartos.

Todas las figuras a la misma escala, con pies completos y postura neutra.

Panel facial:

- primer plano frontal;
- tres cuartos;
- perfil;
- expresión neutra y sonrisa leve.

Panel de identidad:

- manos en reposo;
- marcas permanentes;
- cabello y línea de implantación;
- detalles corporales necesarios para continuidad.

[CALIDAD]

Fotografía real de casting y continuidad, alta resolución, piel y cabello naturales, iluminación funcional, color neutro, nitidez óptica realista y ausencia de retoque publicitario.

[EVITAR]

cuerpo idealizado, cintura imposible, músculos añadidos, pecho exagerado, hombros heroicos, piernas excesivamente largas, pose de moda, piel plástica, rostro perfecto, simetría perfecta, maquillaje glamur, retoque corporal, cambio de identidad o proporciones, dedos deformes, manos ocultas, pies recortados, iluminación dramática, interfaz sci-fi dominante, CGI, render, anime, texto corrupto.

[VALIDACIÓN ANTES DE ENTREGAR]

Aplicar el CONTROL DE COHERENCIA OBLIGATORIO. No entregar hasta verificar identidad, cuerpo, lateralidad, manos, marcas y proporciones en todos los paneles.

Formato horizontal 16:9. Resolución máxima disponible.
```

---

## 4. BLUEPRINT MAESTRO DE VESTUARIO REALISTA

```text
[OBJETIVO]

Crear una hoja técnica de un único vestuario cinematográfico realista. Mostrar exactamente las mismas prendas desde diferentes ángulos y detallar cómo están construidas, cómo caen y qué desgaste poseen. No mostrar un rostro humano identificable.

Si se proporciona una imagen o blueprint de personaje vestido, utilizarlo como referencia absoluta del vestuario. Reproducir exactamente las prendas, calzado y accesorios visibles. No crear un conjunto nuevo salvo petición expresa del usuario.

[DATOS DEL VESTUARIO]

Nombre: [NOMBRE]
Época o universo: [DESCRIPCIÓN]
Uso narrativo: [TRABAJO, VIAJE, COMBATE, VIDA COTIDIANA, CEREMONIA, ETC.]
Silueta: [DESCRIPCIÓN]
Paleta: [COLORES]
Estado: [NUEVO / USADO / MUY GASTADO / REPARADO]

Prenda superior: [DESCRIPCIÓN]
Prenda inferior: [DESCRIPCIÓN]
Capa exterior: [DESCRIPCIÓN]
Calzado: [DESCRIPCIÓN]
Accesorios: [DESCRIPCIÓN]
Materiales y texturas: [DESCRIPCIÓN]
Marcas de continuidad: [COSTURA, PARCHE, MANCHA, ARAÑAZO, HEBILLA, BOLSILLO, ETC.]

Elementos asimétricos y lado anatómico: [INDICAR LADO DERECHO O IZQUIERDO DE CADA CORREA, PARCHE, BOLSILLO, FUNDA, HOMBRERA, GUANTE, ADORNO O DESGASTE].

[SOPORTE]

Maniquí técnico humanoide gris mate, sin rostro, ojos, cabello ni identidad. Anatomía neutra. El soporte debe servir únicamente para mostrar caída y proporciones.

[COMPOSICIÓN]

- turnaround frontal, lateral, posterior y tres cuartos;
- vista principal del conjunto;
- prendas separadas y ordenadas;
- interior de las prendas principales;
- detalles de costuras, cierres, bolsillos, suelas, reparaciones y desgaste.

Mantener idénticos patronaje, colores, materiales, costuras, botones, cierres, bolsillos, accesorios y señales de desgaste en todas las vistas.

No tratar el vestuario como simétrico si no lo es. Mantener cada elemento asimétrico en el mismo lado anatómico del maniquí. No reflejar una correa, bolsillo, hombrera, funda, parche, mancha o reparación al girar la vista.

[REALISMO DE MATERIALES]

Tejidos con grosor real, pliegues causados por gravedad y puntos de tensión, costuras funcionales, desgaste localizado por el uso y respuesta coherente a la luz. Evitar superficies demasiado limpias o uniformes. El desgaste debe tener una causa plausible y mantenerse igual entre vistas.

[ILUMINACIÓN]

Estudio neutro, luz difusa, sombras suaves y balance de blancos natural. Sin dramatización cinematográfica.

[EVITAR]

cambio de prendas entre vistas, accesorios duplicados, bolsillos o botones que aparecen y desaparecen, materiales plásticos, cuero falso, reflejos incorrectos, pliegues imposibles, ropa flotante, desgaste aleatorio, maniquí con rostro, persona real, pose dinámica, CGI evidente, render de videojuego, texto corrupto, logos y marcas de agua.

[VALIDACIÓN ANTES DE ENTREGAR]

Aplicar el CONTROL DE COHERENCIA OBLIGATORIO. No entregar si una prenda, correa, bolsillo, cierre, funda, accesorio, señal de desgaste o elemento asimétrico cambia de lado o desaparece.

Formato horizontal 16:9. Resolución máxima disponible.
```

---

## 5. PERSONAJE REALISTA INTEGRADO EN UN ESCENARIO

```text
[REFERENCIAS]

Imagen 1: blueprint de identidad del personaje. Utilizarla únicamente para conservar identidad, edad, cuerpo, cabello y marcas distintivas.
Imagen 2: blueprint de vestuario. Utilizarla únicamente para reproducir prendas, materiales, accesorios y desgaste.
Imagen 3: referencia del escenario, si existe.

[ESCENA]

Crear un fotograma cinematográfico realista del mismo personaje físicamente presente en el escenario descrito. Debe parecer una toma realizada durante un rodaje real, no una composición promocional ni un render.

Acción concreta: [UNA SOLA ACCIÓN OBSERVABLE]
Lugar: [DESCRIPCIÓN]
Momento del día: [DESCRIPCIÓN]
Clima y atmósfera: [DESCRIPCIÓN]
Objetivo emocional del plano: [DESCRIPCIÓN]

[PERSONAJE]

Mantener las anclas de identidad del blueprint: [ENUMERAR 3-5 RASGOS]. Conservar edad real, asimetrías sutiles, textura natural de piel, cabello irregular, proporciones corporales y marcas permanentes. No embellecer ni rejuvenecer.

Expresión: [EMOCIÓN MODERADA Y CAUSADA POR LA ESCENA]
Postura: [POSTURA NATURAL]
Mirada: [HACIA QUÉ MIRA Y POR QUÉ]

[MAPA DE LATERALIDAD Y OBJETOS]

Marcas del lado derecho: [DESCRIPCIÓN O NINGUNA]
Marcas del lado izquierdo: [DESCRIPCIÓN O NINGUNA]
Mano derecha: [OBJETO O ACCIÓN]
Mano izquierda: [OBJETO O ACCIÓN]
Accesorios del lado derecho: [DESCRIPCIÓN O NINGUNO]
Accesorios del lado izquierdo: [DESCRIPCIÓN O NINGUNO]

Mantener estas asignaciones aunque la cámara cambie de lado. No confundir el lado visible de la imagen con el lado anatómico del personaje.

[CÁMARA]

Tipo de plano: [PLANO]
Altura y ángulo: [DESCRIPCIÓN]
Lente aproximada: [24 / 35 / 50 / 85 MM]
Movimiento implícito: [ESTÁTICA / CÁMARA AL HOMBRO SUAVE / TRÍPODE / DOLLY DISCRETO]
Profundidad de campo: natural y proporcional a la lente, distancia y apertura; sin bokeh exagerado.

[INTEGRACIÓN FÍSICA]

Pies apoyados correctamente en el suelo, escala humana coherente, perspectiva compartida, sombras de contacto, dirección de luz común, reflejos coherentes y oclusiones naturales. La ropa debe responder a la postura, gravedad, viento y movimiento. El personaje no debe parecer recortado, flotante ni iluminado por separado.

[REALISMO FOTOGRÁFICO]

Exposición y balance de blancos naturales, rango dinámico de una cámara real, detalle concentrado en el sujeto y caída óptica progresiva. Permitir grano fotográfico muy fino, pequeñas variaciones de textura y elementos cotidianos imperfectos. La imagen debe conservar información en luces y sombras sin HDR agresivo.

[EVITAR]

pose de modelo, belleza idealizada, piel plástica, ojos brillantes artificiales, dientes perfectos, expresión teatral, mirada vacía, luz de estudio incongruente, nitidez uniforme imposible, exceso de microdetalle, HDR, bloom, halos, reflejos falsos, manos deformes, cuerpo flotante, perspectiva incorrecta, ropa cambiante, fondo genérico, CGI, Unreal Engine, Octane Render, estética de videojuego, texto, logotipos y marcas de agua.

[VALIDACIÓN ANTES DE ENTREGAR]

Aplicar el CONTROL DE COHERENCIA OBLIGATORIO. Revisar especialmente identidad, mano de cada objeto, lado de cada marca, contacto con el suelo, sombras, escala y perspectiva compartida.

Formato: [16:9 / 9:16 / OTRO]. Resolución máxima disponible.
```

---

## 6. ESCENARIO CINEMATOGRÁFICO FOTORREALISTA

```text
[OBJETIVO]

Crear una localización cinematográfica físicamente plausible que pueda reutilizarse con continuidad en diferentes planos. Debe parecer un lugar real fotografiado, con historia material, uso humano y pequeñas irregularidades.

Esta es una imagen base del escenario. No incluir personajes. Los personajes se incorporarán posteriormente mediante el flujo de personaje integrado o storyboard utilizando sus blueprints aprobados.

Localización: [DESCRIPCIÓN]
Época: [DESCRIPCIÓN]
Función del lugar: [DESCRIPCIÓN]
Historia visible: [QUÉ HA OCURRIDO Y QUÉ HUELLAS HA DEJADO]
Arquitectura: [DESCRIPCIÓN]
Materiales dominantes: [DESCRIPCIÓN]
Elementos permanentes para continuidad: [ENUMERAR 3-6]
Momento del día: [DESCRIPCIÓN]
Clima: [DESCRIPCIÓN]

Orientación espacial fija: [DEFINIR NORTE O EJE PRINCIPAL, LADO DERECHO E IZQUIERDO DEL ESPACIO, POSICIÓN DE PUERTAS, VENTANAS, CAMINOS Y ELEMENTOS ASIMÉTRICOS].

[REALISMO DEL ENTORNO]

Geometría estructural plausible, escala coherente, materiales con envejecimiento localizado, suciedad y reparaciones causadas por el uso, vegetación diversa cuando corresponda, reflejos y agua físicamente coherentes. Evitar repetición procedural y simetría accidental.

Mantener la orientación espacial y la lateralidad del escenario entre planos. No reflejar la localización ni intercambiar elementos permanentes de un lado a otro cuando cambie la posición de cámara.

[CÁMARA]

Plano: [GRAN PLANO GENERAL / GENERAL / OTRO]
Ángulo: [DESCRIPCIÓN]
Lente: [24 / 35 / 50 MM]
Profundidad: primer término, plano medio y fondo claramente diferenciados mediante escala, atmósfera y perspectiva.

[VIDA Y ESCALA]

Incluir únicamente elementos ambientales y objetos permanentes justificados: [VEHÍCULOS INMÓVILES, MOBILIARIO, VEGETACIÓN U OBJETOS]. Deben respetar escala, perspectiva y función propia del lugar. Sin personajes, figuras humanas, animales ni siluetas antropomórficas, salvo que el usuario solicite expresamente una excepción.

[ILUMINACIÓN]

Una única fuente o sistema de iluminación comprensible, sombras consistentes, exposición natural, atmósfera moderada y color no excesivamente procesado.

[EVITAR]

personas, personajes, figuras humanas, animales, arquitectura imposible sin justificación narrativa, elementos repetidos, materiales perfectos, ciudad de neón genérica, exceso de god rays, partículas decorativas, reflejos incoherentes, escala contradictoria, texto ilegible, carteles deformados, HDR agresivo, render 3D, videojuego, Unreal Engine, Octane Render, logotipos y marcas de agua.

[VALIDACIÓN ANTES DE ENTREGAR]

Aplicar el CONTROL DE COHERENCIA OBLIGATORIO. No entregar si la orientación espacial, arquitectura, luz, escala o posición de los elementos permanentes resulta contradictoria.

Formato horizontal 16:9. Resolución máxima disponible.
```

---

## 7. STORYBOARD CINEMATOGRÁFICO 3×3 REALISTA

```text
[OBJETIVO]

Crear una única imagen horizontal formada por una cuadrícula regular de 3 columnas y 3 filas. Debe contener exactamente nueve fotogramas del mismo personaje, con el mismo vestuario, durante la misma escena y dentro de la misma localización.

[REFERENCIAS]

Imagen 1: identidad y cuerpo del personaje.
Imagen 2: vestuario.
Imagen 3: escenario.

No mostrar las hojas de referencia dentro del resultado.

[CONTINUIDAD ABSOLUTA]

Mantener en los nueve cuadros:

- misma identidad, edad, marcas faciales y proporciones;
- mismo peinado y longitud del cabello;
- mismo vestuario, accesorios, materiales y desgaste;
- mismo lugar y distribución de elementos permanentes;
- mismo momento del día, clima y dirección de luz;
- continuidad lógica de la acción.

Crear antes de generar un mapa interno de lateralidad: marcas derechas e izquierdas, mano que sostiene cada objeto, lado de fundas y accesorios, orientación del escenario y posición de los elementos permanentes. Aplicarlo sin excepciones en los nueve cuadros. No espejar al personaje ni el escenario.

Si un objeto cambia de mano durante la secuencia, el cambio debe estar solicitado o mostrarse de forma explícita y comprensible en los fotogramas intermedios. En caso contrario, mantener siempre la mano y el lado originales.

Acción o secuencia: [DESCRIPCIÓN BREVE]
Emoción dominante: [DESCRIPCIÓN]

[LOS NUEVE FOTOGRAMAS]

1. Plano general de situación: establece lugar, personaje y objetivo.
2. Plano entero: muestra la acción corporal principal.
3. Plano americano: muestra relación con un objeto o elemento del entorno.
4. Plano medio: muestra decisión o reacción contenida.
5. Primer plano: confirma identidad y emoción sin expresión exagerada.
6. Perfil o tres cuartos: dirige la mirada hacia el elemento narrativo.
7. Contrapicado suave y físicamente plausible.
8. Picado suave que revela información espacial relevante.
9. Plano de cierre en tres cuartos que completa el pequeño arco visual.

Variar encuadre y distancia sin convertir cada cuadro en un estilo diferente. Utilizar lentes plausibles entre 24, 35, 50 y 85 mm. Mantener color, exposición y textura compartidos.

[COMPOSICIÓN]

- exactamente nueve cuadros del mismo tamaño;
- separaciones finas y uniformes;
- sin paneles adicionales;
- sin títulos ni etiquetas;
- un número limpio del 1 al 9 en la esquina superior izquierda de cada cuadro;
- numeración exacta de izquierda a derecha y de arriba abajo:

1 | 2 | 3
4 | 5 | 6
7 | 8 | 9

[REALISMO]

Movimiento corporal con peso, pies en contacto con el suelo, manos naturales, expresiones moderadas, ropa respondiendo a gravedad y postura, sombras de contacto y perspectiva coherente. Textura humana natural, sin embellecimiento y sin acabado de render.

[EVITAR]

identidad diferente, rejuvenecimiento, cambio de cuerpo, ropa o accesorios, cambio de escenario, nueve momentos del día, poses de catálogo, expresiones teatrales, personaje duplicado en un mismo cuadro, manos deformes, cuerpo flotante, perspectiva incompatible, piel plástica, HDR, CGI, Unreal Engine, Octane Render, cuadrícula irregular, paneles ausentes o adicionales, números repetidos, texto adicional, letras, subtítulos, marcas de agua.

[VALIDACIÓN ANTES DE ENTREGAR]

Aplicar el CONTROL DE COHERENCIA OBLIGATORIO comparando los nueve cuadros. No entregar el storyboard si existe cualquier cambio injustificado de identidad, lateralidad, objeto, vestuario, escenario, luz, numeración o continuidad de acción.

Formato final horizontal 16:9. Resolución objetivo 1920 × 1080.
```

---

## 8. RECONSTRUCCIÓN EXACTA DE UN FOTOGRAMA DEL STORYBOARD

```text
[SELECCIÓN]

El usuario seleccionará un número del 1 al 9. Número solicitado: [NÚMERO].

Identificar en la cuadrícula el único cuadro marcado con ese número. Reconstruir exclusivamente ese fotograma como una imagen independiente. Ignorar los otros ocho cuadros.

No combinar poses, fondos, objetos, iluminación ni composición de otros fotogramas. El número solicitado tiene prioridad absoluta.

[RECONSTRUCCIÓN]

Conservar del cuadro elegido:

- personaje e identidad;
- expresión y dirección de mirada;
- postura y acción;
- vestuario y accesorios;
- posición de cámara;
- tipo de plano y lente aparente;
- composición;
- escenario y objetos visibles;
- iluminación, atmósfera y color;
- relaciones espaciales y perspectiva.

Conservar también la lateralidad anatómica y la asignación de objetos del cuadro elegido: misma mano, mismo brazo, mismo lado corporal, mismas marcas y misma orientación espacial. No corregir la composición mediante un reflejo horizontal.

El recorte del panel puede utilizarse únicamente de forma interna para identificar el cuadro seleccionado. No recortar y ampliar el panel como resultado final.

Reconstruir el fotograma seleccionado mediante una nueva generación a resolución máxima, utilizando el panel únicamente como guía de composición, cámara, postura, mirada y acción. El blueprint controla identidad y anatomía; el blueprint de vestuario controla ropa y accesorios; la referencia del escenario controla arquitectura y distribución. Eliminar únicamente la cuadrícula, los márgenes y el número, sin inventar una composición diferente.

[REFERENCIAS DE CONTINUIDAD]

Utilizar siempre los blueprints limpios disponibles del personaje, vestuario y escenario para recuperar identidad, anatomía, piel, ropa, materiales y arquitectura. La composición del cuadro seleccionado continúa siendo la guía principal únicamente para cámara, encuadre, postura, mirada, acción y relaciones espaciales.

[REALISMO]

Mantener textura humana natural, edad real, marcas distintivas, asimetrías sutiles, materiales plausibles, sombras de contacto, profundidad óptica y exposición de cámara real. No embellecer ni convertir la escena en una imagen promocional.

[EVITAR]

seleccionar otro cuadro, recortar y ampliar el panel, mezclar fotogramas, cambiar el plano, recentrar automáticamente, reflejar la imagen, cambiar expresión o pose, alterar vestuario, sustituir el escenario, añadir elementos espectaculares, piel plástica, rostro perfecto, HDR, CGI, texto, números, bordes, cuadrícula, logotipo o marca de agua.

También evitar: imagen reflejada, tatuajes o cicatrices cambiados de lado, armas intercambiadas entre manos, accesorios duplicados, lateralidad corporal incorrecta y escenario invertido.

[VALIDACIÓN ANTES DE ENTREGAR]

Aplicar el CONTROL DE COHERENCIA OBLIGATORIO comparando la reconstrucción con el cuadro numérico solicitado y con las referencias. No entregar si se ha seleccionado otro cuadro, reflejado la imagen o alterado una mano, marca, objeto, pose, cámara o escenario.

Comprobar además que el archivo final no sea un recorte ampliado: debe tener detalle reconstruido, resolución máxima y una identidad nítida procedente del blueprint limpio.

Formato de salida: [16:9 / 9:16 / OTRO]. Resolución máxima disponible.
```

---

## 9. REPARACIÓN CONTROLADA DE UN FOTOGRAMA DEFECTUOSO

```text
[OBJETIVO DE REPARACIÓN]

Reparar únicamente [ELEMENTO DEFECTUOSO] del fotograma proporcionado. Conservar intactos cámara, encuadre, postura, acción, perspectiva, escenario, iluminación y todos los elementos que ya sean correctos.

[REFERENCIAS Y FUNCIONES]

Imagen 1: blueprint limpio de identidad y cuerpo. Fuente obligatoria para rostro, edad, anatomía, piel, cabello, barba y marcas permanentes.
Imagen 2: blueprint limpio de vestuario, si existe. Fuente obligatoria para ropa, calzado, accesorios, materiales y desgaste.
Imagen 3: mejor referencia original del escenario, si existe. Fuente obligatoria para arquitectura, distribución y elementos permanentes.
Imagen 4: fotograma defectuoso. Utilizar únicamente para conservar cámara, postura, acción, perspectiva, distribución espacial e iluminación general.

No utilizar como base de identidad una imagen que ya haya sido corregida o regenerada varias veces. Volver siempre al blueprint limpio y a la mejor referencia original disponible.

[JERARQUÍA]

El blueprint de identidad prevalece sobre el fotograma defectuoso para rostro, piel, cuerpo, edad, cabello, barba y marcas. El blueprint de vestuario prevalece para ropa y accesorios. La referencia del escenario prevalece para arquitectura. El fotograma defectuoso controla exclusivamente la composición.

[REPARACIÓN LOCALIZADA]

Defecto que debe corregirse: [DESCRIPCIÓN PRECISA].
Zona afectada: [DESCRIPCIÓN].
Elementos que deben permanecer idénticos: [ENUMERAR].

Sustituir la identidad, anatomía o piel defectuosa por la del blueprint limpio sin rediseñar el personaje. Corregir solo el elemento indicado. No alterar pose, mirada, manos correctas, objetos correctos, vestuario correcto, fondo, cámara, lente aparente, escala, sombras ni color general.

[PIEL HUMANA FOTOGRAFIADA]

Piel humana real fotografiada, con poros sutiles, irregulares y moderados; líneas de expresión propias de la edad; variaciones cromáticas naturales; brillo controlado; transición natural entre barba y piel; sin filtros de belleza, sin HDR facial y sin textura excesiva.

[LATERALIDAD Y OBJETOS]

Derecha e izquierda son anatómicas del personaje. Mantener cada marca, accesorio y objeto en el mismo lado y en la misma mano definidos por los blueprints limpios.

[EVITAR]

piel plástica, piel de cera, piel de goma, piel quemada, piel de cuero, patrón grabado, surcos repetitivos, textura geométrica, textura reptil, microdetalle artificial, exceso de poros, exceso de enfoque, tono excesivamente moreno, piel naranja, manchas rojizas, heridas o cicatrices inventadas, cambio de identidad, embellecimiento, rejuvenecimiento, anatomía alterada, regeneración global innecesaria, cambio de vestuario, cambio de escenario, recentrado, reflejo horizontal, texto, logotipos y marcas de agua.

[VALIDACIÓN ANTES DE ENTREGAR]

Comparar visualmente el resultado con el blueprint limpio, la mejor referencia original y el fotograma de composición. Rechazarlo si todavía contiene piel plástica, patrones grabados, exceso de microdetalle, cambio de identidad o cualquier modificación fuera del elemento autorizado. No encadenar nuevas reparaciones sobre este resultado si falla: volver a las referencias limpias originales.

Formato de salida: [16:9 / 9:16 / OTRO]. Resolución máxima disponible.
```

---

## ORDEN DE USO RECOMENDADO

1. Generar el blueprint facial.
2. Generar el blueprint corporal utilizando el facial como referencia.
3. Diseñar el vestuario por separado.
4. Crear el escenario estable.
5. Integrar personaje, vestuario y escenario en un fotograma de prueba.
6. Corregir identidad, escala, materiales e iluminación antes del storyboard.
7. Crear la cuadrícula 3×3.
8. Reconstruir el fotograma elegido.
9. Reparar de forma localizada cualquier defecto que impida aprobarlo, volviendo siempre a los blueprints limpios.
10. Utilizar la imagen reconstruida y aprobada como primer fotograma o referencia del vídeo.

No introducir todos los bloques en una sola generación. Cada etapa debe producir una referencia limpia para la siguiente.
