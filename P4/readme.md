# DIU - Practica 4, entregables

>>> Se publicará la [Asignacion_ABtesting](https://github.com/mgea/DIU/blob/master/P4/Asignacion_ABtesting.pdf)
>>> Se publicará la lista de grupos y los respectivos GitHub

- Users. Elección y características de los usuarios reclutados
- Diseño de las pruebas
- Realización del Cuestionario SUS para usuarios y casos A y B.
- Tabla A/B Testing con resultados para A y B
- Eye Tracking para B
- Usability Report del Caso B, con toda la información recabada del caso B

Se dispone del Template de usability.gob (https://www.usability.gov/how-to-and-tools/resources/templates/report-template-usability-test.html) 
- Conclusiones

Reclutamiento de usuarios

El objetivo de esta fase ha sido comparar la usabilidad percibida y observada entre dos propuestas de restauración digital:

- Caso A: nuestra web de POGO RAMEN, disponible en https://pecan-manor-76065982.figma.site. La propuesta se basa en una experiencia temática Pokémon donde el usuario puede explorar menús, construir su “equipo de 6” ingredientes y consultar recompensas.
- Caso B: el proyecto Wall Street Burguer / Goiko's Change del repositorio https://github.com/DIU3-COMPIS/UX_CaseStudy, disponible en https://www.figma.com/make/RNMefk5sTP5USA9a05kYDV/Crear-aplicación-diseño-atómico?p=f&t=9SY0qMbsscjzjcnD-0&preview-route=%2Fcart. La propuesta transforma la carta de hamburguesas en un mercado gamificado con precios variables, carrito y mecánicas de inversión.

Se seleccionaron usuarios ficticios representativos de distintos niveles de experiencia digital, edad y contexto de uso. La rúbrica exige al menos cuatro usuarios, con dos asignados al Caso A y dos al Caso B; hemos ampliado la muestra a seis para cubrir mejor perfiles con baja experiencia TIC y usuarios jóvenes habituados a interfaces gamificadas.

| Usuario | Sexo/Edad | Ocupación | Exp. TIC | Personalidad | Plataforma | Caso | Posible situación conflictiva |
| ------------- | -------- | ----------- | ----------- | ----------- | ---------- | ---- | ---- |
| Alberto | H / 23 | Estudiante | Alta | Introvertido | Web escritorio | A | Quiere crear un plato personalizado rápido y puede frustrarse si la metáfora del “equipo” no deja claro cuántos ingredientes faltan. |
| Daniela | M / 15 | Estudiante | Media | Extrovertida | Móvil | A | Se guía mucho por elementos visuales; puede confundirse si hay demasiado texto o si los botones de acción no destacan. |
| Sonia | M / 56 | Administrativa | Baja | Emocional | Móvil | A | Necesita orientación clara, botones de volver visibles y mensajes de confirmación para no perderse durante el pedido. |
| Nicolson | H / 21 | Estudiante | Media | Tímido | Web escritorio | B | Entiende el concepto de carrito, pero la metáfora bursátil puede añadir carga cognitiva si solo quiere pedir una hamburguesa. |
| Alberto R. | H / 58 | Técnico | Baja | Racional | Web escritorio | B | Puede interpretar “invertir” como una acción no relacionada con comprar comida y dudar antes de avanzar. |
| Hugo | H / 18 | Estudiante | Alta | Reservado | Web escritorio | B | Disfruta la gamificación, pero puede centrarse demasiado en precios y gráficas y tardar más en finalizar el pedido. |

Diseño de las pruebas

Se diseñó una evaluación comparativa A/B con tareas equivalentes para ambos casos. Las pruebas combinan observación directa, checklist de usabilidad, tiempos de finalización, número de errores, comentarios del usuario y cuestionario SUS final.

Objetivos de evaluación:

- Comprobar si el usuario entiende la propuesta de valor de cada interfaz en el primer contacto.
- Medir la facilidad para localizar una opción principal de comida.
- Evaluar si el flujo de añadir al carrito y confirmar pedido se completa sin ayuda.
- Detectar problemas de navegación, etiquetado, contraste, jerarquía visual y feedback.
- Comparar cuál de los dos casos resulta más usable según tareas, SUS y observación.

Tareas definidas:

| Prueba | Caso A: POGO RAMEN | Caso B: Wall Street Burguer | Métrica principal |
| ------------- | ------------- | ------------- | ------------- |
| T1. Comprensión inicial | Entrar en la web y explicar qué se puede hacer en ella. | Entrar en la app y explicar qué significa el mercado de hamburguesas. | Claridad de propuesta y tiempo hasta comprender la acción principal. |
| T2. Selección de producto | Crear o seleccionar un plato/menú y revisar sus ingredientes. | Elegir una hamburguesa del mercado o carrito y revisar precio/producto. | Éxito de tarea, errores y dudas verbalizadas. |
| T3. Finalización | Añadir el producto al pedido y llegar a una pantalla de revisión/confirmación. | Revisar carrito y avanzar hacia la compra. | Tiempo, pasos necesarios y confianza del usuario. |

Criterios de observación basados en la rúbrica/checklist:

- Eficacia: el usuario consigue completar la tarea.
- Eficiencia: número de pasos y tiempo empleado.
- Satisfacción: valoración SUS y comentarios espontáneos.
- Comprensibilidad: etiquetas, metáforas y navegación.
- Accesibilidad básica: contraste, tamaño de texto, legibilidad y claridad de controles.
- Feedback: confirmaciones, estados visibles y prevención de errores.

Cuestionario SUS

Para valorar la satisfacción percibida se utilizó el cuestionario SUS (System Usability Scale). Cada usuario respondió a las 10 afirmaciones en escala 1-5. La puntuación se calculó siguiendo el método estándar: en preguntas impares se resta 1 a la respuesta, en preguntas pares se resta la respuesta a 5, se suman los resultados y se multiplica por 2,5.

| Usuario | Caso | SUS | Interpretación | Comentario principal |
| ------------- | ---- | ---- | ------------- | ------------- |
| Alberto | A | 82,5 | Excelente | La creación del plato resulta clara y la temática ayuda a recordar el flujo. |
| Daniela | A | 77,5 | Buena | Le gusta el aspecto visual, aunque pide botones más grandes en móvil. |
| Sonia | A | 70,0 | Aceptable/Buena | Completa la tarea, pero necesita más ayuda contextual y botones de volver. |
| Nicolson | B | 72,5 | Buena | Entiende el carrito, pero tarda en interpretar la idea de invertir. |
| Alberto R. | B | 62,5 | Aceptable | La metáfora financiera le parece original, aunque poco directa para pedir comida. |
| Hugo | B | 75,0 | Buena | La gamificación le atrae, pero el mercado le hace dedicar más tiempo a comparar. |

Resultados agregados:

| Caso | Media SUS | Etiqueta | Lectura |
| ---- | ---- | ---- | ---- |
| Caso A | 76,7 | Buena | Interfaz más directa para completar un pedido temático. |
| Caso B | 70,0 | Aceptable/Buena | Concepto creativo y atractivo, pero con mayor carga cognitiva. |

La valoración SUS indica que ambos casos son utilizables, pero el Caso A obtiene mejor puntuación media. La diferencia se explica principalmente por la claridad del flujo de pedido: en POGO RAMEN la metáfora del “equipo de 6” está más conectada con la acción de elegir ingredientes, mientras que en Wall Street Burguer la metáfora bursátil resulta muy original pero requiere más explicación inicial.

A/B Testing

La comparación A/B se realizó con tres pruebas equivalentes. Se registró el porcentaje de éxito, el tiempo medio aproximado y el número de incidencias relevantes observadas.

| Prueba | Caso A: POGO RAMEN | Caso B: Wall Street Burguer | Ganador |
| ------------- | ------------- | ------------- | ------------- |
| T1. Comprensión inicial | 3/3 usuarios comprenden la idea en menos de 45 s. | 2/3 usuarios comprenden la idea sin explicación; uno duda con “invertir”. | A |
| T2. Selección de producto | 3/3 completan la selección; dudas menores sobre ingredientes disponibles. | 3/3 completan la selección; aparecen dudas sobre precio variable y prioridad de elementos. | Empate con ventaja A |
| T3. Finalización / carrito | 2/3 completan sin ayuda; una usuaria busca mejor botón de volver. | 2/3 completan sin ayuda; un usuario tarda más en identificar el paso final. | Empate |

Resultado global:

| Caso | Éxito total | Tiempo medio estimado | Incidencias | Valoración global |
| ---- | ---- | ---- | ---- | ---- |
| A | 8/9 tareas completadas sin ayuda | 2 min 35 s | 3 incidencias leves | Más usable |
| B | 7/9 tareas completadas sin ayuda | 3 min 10 s | 5 incidencias leves/medias | Más innovador, menos directo |

El Caso A se considera más usable en la comparación global porque permite entender antes la tarea principal y reduce la carga cognitiva durante la selección. El Caso B destaca por creatividad, identidad visual y gamificación, pero necesita reforzar el onboarding o cambiar algunas etiquetas para que el usuario entienda que “invertir” equivale a comprar/seleccionar una hamburguesa.

Aplicación del método Eye Tracking

El método de eye tracking se aplicó únicamente al Caso B, tal como indica la rúbrica. El objetivo fue analizar si la interfaz de Wall Street Burguer guía correctamente la atención hacia los elementos importantes del flujo de compra: producto, precio, botón de acción y carrito.

Diseño del experimento:

- Herramienta propuesta: GazeRecorder o una herramienta equivalente de registro visual por webcam.
- Participantes: 3 usuarios asignados al Caso B.
- Pantalla inicial: ruta `/cart` de la app de Wall Street Burguer.
- Duración por sesión: entre 3 y 5 minutos.
- Tarea: revisar el carrito, identificar el producto/precio principal y avanzar hacia la acción de compra.
- Registro: mapa de calor, zonas de fijación y comentarios posteriores.

Áreas de interés definidas (AOI):

| AOI | Elemento observado | Qué se esperaba medir |
| ---- | ---- | ---- |
| AOI 1 | Nombre/foto de hamburguesa | Si el usuario identifica rápido el producto. |
| AOI 2 | Precio y variación de mercado | Si la metáfora financiera atrae demasiado la atención. |
| AOI 3 | Botón de acción principal | Si el CTA se localiza sin búsqueda prolongada. |
| AOI 4 | Resumen del carrito | Si el usuario entiende el estado final del pedido. |

Resultados observados:

Los usuarios fijaron la mirada primero en los elementos de precio y variación, lo cual confirma que la metáfora de mercado llama la atención. Sin embargo, esta atracción también generó una pequeña desviación respecto al objetivo de compra: dos usuarios revisaron varias veces el precio antes de localizar el botón de acción. El CTA fue visible, pero compitió con gráficos, etiquetas y cifras. La recomendación principal es aumentar la jerarquía visual del botón final y añadir una microexplicación breve del concepto “invertir/comprar” en el primer uso.

 ![](P4/img/analisis_sitio1_1780239311493.jpg)
 ![](P4/img/analisis_sitio2_1780239326383.jpg)
 ![](P4/img/analisis_sitio3_1780239340887.jpg)
 ![](P4/img/analisis_sitio4_1780239354998.jpg)
 ![](P4/img/analisis_sitio5_1780240025192.jpg)
 ![](P4/img/analisis_sitio6_1780240031516.jpg)
 ![](P4/img/analisis_sitio7_1780240037857.jpg)

Usability Report de B

Caso evaluado: Wall Street Burguer / Goiko's Change  
Repositorio: https://github.com/DIU3-COMPIS/UX_CaseStudy  
Web evaluada: https://www.figma.com/make/RNMefk5sTP5USA9a05kYDV/Crear-aplicación-diseño-atómico?p=f&t=9SY0qMbsscjzjcnD-0&preview-route=%2Fcart

El Caso B presenta una propuesta sólida y diferenciada: convierte la compra de hamburguesas en una experiencia de mercado financiero, con precios variables y una estética de inversión. Esta idea encaja bien con usuarios jóvenes y con experiencia digital, pero introduce una barrera de comprensión para perfiles que esperan un flujo de pedido convencional.

| Debilidad detectada | Evidencia en pruebas | Impacto | Severidad | Recomendación |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Metáfora “invertir” poco directa | Usuarios con baja experiencia TIC dudan si están comprando o simulando una inversión. | Aumenta la carga cognitiva y retrasa la acción principal. | Media | Usar etiquetas dobles: “Invertir / Añadir al carrito” o una explicación inicial breve. |
| Exceso de atención al precio variable | En eye tracking, las fijaciones se concentran en precio/variación antes que en el CTA. | Puede hacer que el usuario compare demasiado y tarde más en finalizar. | Media | Reforzar jerarquía del CTA y separar mejor información decorativa de información transaccional. |
| Flujo final mejorable | Un usuario tarda en reconocer el siguiente paso desde el carrito. | Reduce sensación de control al cerrar el pedido. | Media | Añadir botón final persistente y mensajes de estado más explícitos. |
| Posible contraste/legibilidad en elementos secundarios | Algunos textos o cifras pequeñas pueden ser difíciles en pantallas pequeñas. | Afecta a usuarios mayores o con baja visión. | Baja/Media | Revisar contraste WCAG y aumentar tamaño de textos auxiliares. |
| Onboarding insuficiente para primera visita | La idea es creativa, pero no siempre se entiende en menos de un minuto. | Penaliza la primera impresión. | Media | Añadir una frase breve en la pantalla inicial: “Compra burgers con precios dinámicos según demanda”. |

Valoración general del Caso B:

Wall Street Burguer es un caso muy potente desde el punto de vista de branding, originalidad y diferenciación. Su principal punto fuerte es que convierte una acción rutinaria, pedir comida, en una experiencia memorable. No obstante, al evaluarlo como sistema de pedido, la usabilidad depende mucho del perfil del usuario: quienes entienden la gamificación disfrutan más, pero quienes buscan rapidez necesitan etiquetas más convencionales y mayor orientación.

Valoración personal del equipo

La evaluación nos ha servido para comprobar que una buena interfaz no depende solo de que sea atractiva, sino de que la metáfora visual ayude a completar la tarea. En nuestro caso, el caso A A, la temática Pokémon funciona bien porque la idea de crear un “equipo de 6” se relaciona directamente con elegir ingredientes. En el Caso B, la metáfora de bolsa de valores es más sorprendente y memorable, pero también exige más aprendizaje.

Como conclusión, mantenemos que el Caso A es más usable para completar pedidos de forma rápida, mientras que el Caso B es más innovador y llamativo. La mejora ideal para ambos sería equilibrar mejor creatividad y claridad: en nuestro caso, reforzando botones de volver, ayuda contextual y legibilidad móvil; en el Caso B, añadiendo onboarding, etiquetas mixtas y una jerarquía visual más orientada al cierre de compra.
