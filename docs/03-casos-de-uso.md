## 1. Generación de Contenido Asistida por IA
1. El usuario accede a la creación de un mazo.
2. Selecciona la opción "Generar con IA".
3. Pega un bloque de texto sobre Farmacología.
4. El sistema procesa el texto y genera 20 tarjetas con pregunta, respuesta y explicación.
5. El usuario aprueba, edita o descarta las tarjetas antes de guardar.

## 2. Estudio con Repetición Espaciada
1. El usuario inicia una sesión de estudio.
2. El sistema recupera las tarjetas cuyo `next_review` es igual o anterior a la fecha actual.
3. El usuario visualiza la pregunta y voltea la tarjeta.
4. El usuario califica su nivel de confianza (1-4).
5. El sistema recalcula el `next_review` y actualiza la tabla `study_progress`.

## 3. Desafío entre Usuarios
1. El Usuario A envía un reto al Usuario B en el mazo.
2. Ambos responden 20 preguntas contra reloj.
3. El sistema calcula la precisión y el tiempo.
4. Se asigna la victoria, se actualizan los puntajes y se otorgan puntos de XP.