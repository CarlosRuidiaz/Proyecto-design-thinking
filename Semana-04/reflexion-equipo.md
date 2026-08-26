# Reflexión del equipo

## Información del equipo

**Nombre del equipo:** Grupo 4

**Integrantes:** Juan Bolívar, Claudia Elías, Juan Rojas, Carlos Ruidíaz

---

## Decisiones tomadas

¿Qué decisiones importantes tomaron al construir el prototipo?

- Fusionar las pantallas de Inicio y Explorar proyectos en una sola pantalla tipo feed, con pestañas y un botón flotante para crear una idea, en vez del diseño original de dos botones separados. Les pareció un patrón más intuitivo y moderno, similar al de las redes sociales más usadas hoy en día como Instagram o TikTok.

- Que la conexión desde la confirmación de "Crear idea" aterrice específicamente en la pestaña "Explorar proyectos" y no en "Proyectos sugeridos", ya que es la que tiene búsqueda y filtros, más cercana a lo que el usuario probablemente quiere hacer justo después de publicar su propia idea.

- Mantener la barra inferior simple, con un único botón flotante "+", en lugar de agregar más íconos de navegación, para no aumentar la complejidad visual del prototipo en esta etapa. Es la decisión que la prueba dejó más en duda, aunque solo una de las cinco personas la señaló de forma explícita.

- Sostener el alcance recortado que se definió al inicio de la semana: sin onboarding, sin login y sin pantallas de perfil de usuario. Fue una decisión consciente para concentrar la validación en la navegación entre los dos flujos, pero es la que más consecuencias trajo en la prueba: cuatro de las cinco personas no lograron volver a su propia idea, y ninguna de las cinco entendió por sí sola qué es la aplicación.

---

## Lo más difícil de representar

¿Qué parte de la idea fue más difícil convertir en prototipo?

Más que una pantalla en particular, lo más difícil fue adaptarse al manejo de Figma Design sobre la marcha. Algunas pantallas resultaron relativamente sencillas de armar mientras el equipo iba aprendiendo la herramienta, pero otras, como la de creación de la idea, se volvieron más frustrantes de construir por la cantidad de elementos que había que organizar en una sola vista (campos, ayuda contextual, barra de progreso, validación de campos faltantes) sin tener todavía suficiente dominio de Figma para resolverlo con agilidad.

También costó representar la fusión de Inicio y Explorar sin perder el requisito original de que crear una idea y explorar proyectos tuvieran el mismo peso visual. Al final la pantalla quedó dominada por la lista de proyectos y la acción de crear se redujo a un botón "+" sin etiqueta, lo cual resolvió el problema visual pero desbalanceó los dos flujos.

---

## Lo que todavía no sabemos

¿Qué dudas esperan resolver en la prueba con usuarios?

Estas eran las tres dudas con las que el equipo entró a la validación, y lo que la prueba respondió de cada una:

- **¿La conexión entre "Crear idea" y "Explorar proyectos" se entiende sola o necesita ayuda?** Se entiende sola. Las cinco personas pasaron de la confirmación a explorar proyectos sin que se les indicara. Pero apareció con fuerza algo que no habíamos anticipado: cuatro de las cinco no supieron después cómo volver a su propia idea, y los dos estudiantes de Civil llegaron a ella presionando "Volver" varias veces hasta encontrarla por casualidad. El botón "Ver mi idea publicada" existe en la pantalla de confirmación, y es la única puerta hacia la idea propia en todo el prototipo; una vez el usuario sale de esa pantalla no hay ruta de regreso, porque el perfil de usuario quedó fuera de alcance. La conexión que sí diseñamos funcionó; la que hizo falta es una que no diseñamos.

- **¿Se mantiene la preferencia por la versión B de cada flujo ahora que están integrados?** Sí en lo esencial. Nadie se atascó en un campo obligatorio del formulario de una sola vista y la claridad del recorrido se calificó 4, 4, 4.5, 4.5 y 5 sobre 5. Pero aparecieron dos matices que antes no teníamos. El primero es sobre el formulario: un estudiante de Civil lo sintió "más largo de lo que esperaba" para una primera vez, aunque no identificó ningún campo sobrante, mientras que el otro destacó justamente que se sintiera "claro" y "sin muchas vueltas". Las dos reacciones apuntan a la misma propiedad de la versión B, que todos los campos estén visibles a la vez: eso es lo que la hizo ganar en la semana 3 y también lo que hace que la tarea se vea larga de entrada. El segundo matiz es sobre los filtros, que dejaron de tener respaldo unánime: cuatro de las cinco personas los percibieron útiles y con resultados relevantes, pero no quedó registrado quién discrepó ni por qué.

- **¿El patrón de pestañas se entiende de inmediato?** No hubo confusión reportada sobre las pestañas en sí. Sin embargo, la parte de la duda sobre cuál pestaña esperaría el usuario ver activa al abrir la app quedó sin responder, porque el guion no incluyó ninguna tarea ni pregunta que lo indagara.

Lo que sigue sin estar claro después de esta validación:

- **Por qué se malinterpretó "Aplicar", y si renombrarlo alcanza.** Tres de las cinco personas no entendieron a primera vista que el botón se refiere a postularse. El prototipo usa el mismo verbo para dos acciones distintas: "Aplicar" (postularse a un proyecto) en el detalle, y "Aplicar filtros" (confirmar una selección) en la pantalla de filtros. Como el recorrido del guion pasa primero por los filtros, el usuario llega al detalle con el otro significado ya aprendido. No sabemos todavía si cambiarlo por "Postularme" resuelve del todo la confusión o si hace falta además una confirmación que explique a qué se está postulando.

- **Cuánto texto hace falta para que se entienda qué es la aplicación.** Ninguna de las cinco personas entendió a primera vista de qué se trata la app, algo esperable porque el prototipo no tiene onboarding ni ningún texto explicativo: el encabezado dice solo "Proyectos colaborativos". Es el único hallazgo unánime de la prueba. No sabemos si basta con un párrafo introductorio en la pantalla principal o si se necesita una pantalla de bienvenida completa.

- **Si el botón de crear es realmente difícil de encontrar o fue una impresión individual.** Solo la estudiante de Diseño Gráfico lo señaló; las otras cuatro personas no lo mencionaron. La señal es más débil de lo que parecía con la muestra inicial, pero coincide con algo que sabemos del diseño: la fusión de la pantalla principal rompió a propósito la paridad entre crear y explorar. A eso se suma un desfase de vocabulario, ya que la participante buscaba "crear proyecto", la aplicación llama a eso "crear idea" y el botón flotante no dice ninguna de las dos cosas. Falta decidir si el sistema habla de ideas, de proyectos, o de ambos en momentos distintos del ciclo.

- **Dónde deben aparecer las categorías de un proyecto.** También lo mencionó una sola persona, pero en este caso es verificable en el propio diseño: se especificaron etiquetas de categoría o programa académico en las tarjetas de la lista y no en la pantalla de detalle, así que la categoría se pierde justo cuando el usuario entra a evaluar el proyecto. Falta definir qué otra información del proyecto debería viajar de la tarjeta al detalle.

- **Hasta dónde se puede acortar el formulario sin volver al esquema por pasos.** La versión A con wizard se descartó en la semana 3 porque hacía repetir información, así que reducir la sensación de longitud no puede pasar por volver a ese camino. Queda por explorar si se resuelve agrupando campos, marcando cuáles son opcionales, o dejando publicar con lo mínimo y completar después.

---

## Riesgos del prototipo actual

¿Qué podría hacer que los resultados de la prueba sean confusos o poco útiles?

- La muestra creció a 5 personas frente a las 3 de la semana 3, así que la ampliación que pedía la consigna sí se cumplió, pero sigue siendo pequeña frente al total de estudiantes de la universidad. Más importante que el tamaño es su composición: cuatro de las cinco personas vienen de ingeniería (Mecánica, Sistemas y dos de Civil) y una de Diseño Gráfico, sin ninguna de ciencias humanas o sociales. Justamente el sesgo entre áreas STEM y no STEM fue una de las preocupaciones que dio origen a este proyecto en la semana 1, así que probar casi solo con ingenierías es un riesgo directo sobre la validez de lo que estamos concluyendo.

- Cuatro de los hallazgos se sostienen en una sola voz: el botón de crear difícil de encontrar, las categorías ausentes en el detalle, la sensación de formulario largo y la persona que no percibió útiles los filtros. Conviene tratarlos como pistas por confirmar y no como conclusiones, salvo cuando el problema es verificable en el diseño mismo, como pasa con las categorías.

- El cambio de diseño (pantalla principal tipo feed con pestañas) no fue validado por separado antes de integrarse, a diferencia de los flujos de crear idea y explorar proyectos que sí pasaron por la validación exploratoria de la semana 3.

- El guion le indicaba al usuario qué tarea realizar en cada momento, lo que enmascaró el problema de comprensión general. Las cinco personas siguieron las instrucciones sin dificultad y aun así ninguna entendió por sí sola qué es la aplicación. Es decir, la prueba midió bien la navegabilidad pero midió poco la comprensión de la propuesta, y ese sesgo hay que corregirlo en el guion de la semana 5.

- El prototipo se construyó en dos momentos y con dos herramientas: primero las pantallas se armaron manualmente en Figma Design, por un equipo que todavía estaba aprendiendo a usarlo, y solo después se recurrió a Figma Make para generar una versión interactiva a partir de ese diseño. Eso abría dos riesgos, que quedaran diferencias entre la versión hecha a mano y la generada, y que Make devolviera pantallas más pulidas de lo que pide una validación de baja o media fidelidad, desviando la atención del usuario hacia la estética. Ninguno de los dos llegó a materializarse: ninguna de las cinco personas hizo comentarios sobre la apariencia, y las observaciones se concentraron en la navegación y en los nombres de los botones, que era justamente el objetivo de la prueba.

---

## Conclusión del equipo

Escriban un párrafo corto explicando si sienten que el prototipo es suficiente para aprender algo valioso de los usuarios.

Sí, el prototipo fue suficiente, y lo más útil es que dejó de responder únicamente lo que le preguntamos. Las tres dudas con las que entramos se resolvieron rápido y a favor del diseño, las cinco personas recorrieron ambos flujos sin ayuda y calificaron la claridad entre 4 y 5, pero el valor real estuvo en lo que no habíamos previsto. Dos hallazgos aparecieron con fuerza suficiente para actuar sobre ellos de inmediato: que ninguna de las cinco personas entendió por sí sola qué es la aplicación, y que cuatro de cinco no lograron volver a su propia idea después de publicarla. Ambos tienen la misma causa, que es el alcance que recortamos a propósito al dejar fuera el onboarding y el perfil de usuario, así que no son fallas de la herramienta ni de la muestra sino consecuencias de nuestras decisiones. Otros hallazgos, como el nombre del botón "Aplicar" o la ausencia de categorías en el detalle, se explican por el vocabulario y por lo que dejamos de especificar, y eso los vuelve corregibles sin rediseñar nada de fondo. Lo que sí reconocemos como límite es la composición de la muestra: crecimos de 3 a 5 personas, pero cuatro de ellas son de ingeniería y ninguna de ciencias humanas, que es precisamente el sesgo que este proyecto quería evitar reforzar. Corregir eso en la semana 5, junto con un guion que no le vaya diciendo al usuario qué hacer, es tan importante como resolver los hallazgos de esta semana.
