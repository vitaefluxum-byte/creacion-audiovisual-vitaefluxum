# Prompt profesional de vídeo

Utiliza esta referencia cuando el usuario quiera un prompt de vídeo completo, especialmente para animar una imagen inicial o mantener continuidad entre planos.

Si la herramienta de destino es Grok, esta plantilla no es la base final. Utiliza obligatoriamente la plantilla específica de `video-timeline.md` y conserva de este documento únicamente las decisiones cinematográficas que correspondan al plano.

## Orden de construcción

1. Define la intención narrativa y una única acción principal observable.
2. Fija los elementos que no pueden cambiar: identidad, edad, anatomía, ropa, objetos, lateralidad, escenario y momento del día.
3. Describe el movimiento corporal con peso, equilibrio e inercia plausibles.
4. Elige plano, ángulo, altura, lente y un solo movimiento de cámara principal.
5. Define luz, atmósfera, color y profundidad de campo.
6. Añade sonido, voz o música únicamente cuando el modelo los admita.
7. Organiza la evolución mediante timeline.
8. Cierra con restricciones negativas breves y verificables.

## Plantilla lista para adaptar

```text
[OBJETIVO]
Vídeo cinematográfico de [DURACIÓN] segundos basado en la imagen de referencia. Mantener exactamente [IDENTIDAD, EDAD, ROPA, OBJETOS Y ESCENARIO].

[ACCIÓN]
[PERSONAJE] realiza [UNA ACCIÓN PRINCIPAL] con movimiento corporal natural. [DETALLES DE POSTURA, MIRADA, MANOS, PESO E INTERACCIÓN].

[CONTINUIDAD]
No cambiar rostro, cabello, anatomía, vestuario, colores, materiales, marcas, mano asignada a cada objeto ni orientación espacial. Derecha e izquierda son siempre anatómicas del personaje.

[CÁMARA]
[TIPO DE PLANO], cámara a [ALTURA], ángulo [ÁNGULO], lente [FOCAL] mm. [MOVIMIENTO PRINCIPAL] suave y estable. Profundidad de campo físicamente plausible, sin reenfoques arbitrarios.

[ILUMINACIÓN Y ATMÓSFERA]
[FUENTE PRINCIPAL], [DIRECCIÓN], [CALIDAD], [TEMPERATURA DE COLOR] y [CONTRASTE]. [CLIMA, VIENTO, HUMO, POLVO O PARTÍCULAS] reaccionan de forma coherente al entorno.

[SONIDO, SI ESTÁ DISPONIBLE]
Ambiente: [SONIDO DEL LUGAR]. Acción: [SONIDOS SINCRONIZADOS]. Voz: [IDIOMA, TEXTO, TONO Y TEXTURA]. Música: [ESTILO, INTENSIDAD Y FUNCIÓN NARRATIVA].

[TIMELINE]
0.0–[T1] s: establecer [SUJETO, ESPACIO Y ESTADO INICIAL].
[T1]–[T2] s: desarrollar [ACCIÓN Y MOVIMIENTO DE CÁMARA].
[T2]–[T3] s: punto de atención o cambio emocional [DESCRIPCIÓN].
[T3]–[FINAL] s: resolver la acción y terminar en [ENCUADRE O ESTADO FINAL].

[ACABADO]
[ESTILO VISUAL], textura [TEXTURA], color grading [PALETA], movimiento a velocidad natural, exposición estable y detalle realista.

[EVITAR]
Cambios de identidad o ropa, morphing facial, extremidades deformes, objetos que aparecen o desaparecen, manos intercambiadas, cámara errática, zoom digital accidental, parpadeo, iluminación inconsistente, fondo que se derrite, cámara lenta involuntaria, texto, logotipos y marcas de agua.
```

## Timeline

- Utiliza entre tres y cinco bloques temporales para vídeos cortos.
- Cada bloque debe describir un cambio visible, no repetir toda la escena.
- Mantén continuidad entre el final de un bloque y el inicio del siguiente.
- Evita ordenar simultáneamente movimientos incompatibles de cámara o del personaje.
- Si se necesita un loop, el estado final debe poder enlazar físicamente con el inicial.

## Control antes de entregar

Comprueba que el prompt especifica una sola acción dominante, que la cámara no contradice el encuadre inicial, que el timeline cabe en la duración y que las restricciones protegen los elementos visibles realmente importantes.
