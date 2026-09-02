# Resultados de validación del prototipo

> Este entregable debe referenciar la versión ajustada del prototipo en Figma, mejorada después de la validación de la semana 4 y usada en una nueva ronda de pruebas con usuarios.

## Información del equipo

**Nombre del equipo: Grupo 4**

**Integrantes: Juan Bolívar, Claudia Elías, Juan Rojas, Carlos Ruidíaz**

---

## Pruebas realizadas

**Cantidad de personas participantes: 9 personas**

**Tipo de usuarios consultados: estudiantes de distintas ingenierías, 2 de Diseño Gráfico y 1 de Relaciones Internacionales.** A diferencia de la semana 4, donde 4 de 5 participantes eran de ingeniería, esta ronda incluyó programas de fuera de ingeniería.

**Fecha o fechas de las pruebas:** Semana 5   

---

## Qué se probó

Describan brevemente la versión del prototipo que mostraron en esta nueva validación.

Se mostró el prototipo integrado "Innovation Hub" (33 pantallas), que ya incluye onboarding, exploración de proyectos con dos vistas ("Para tus habilidades" y "Explorar proyectos"), creación de idea por secciones, postulación y gestión de equipo, espacio de trabajo (workspace) con avances/tareas/galería, y un módulo de validación social (encuestas y vitrina de prototipos con retroalimentación).

**Enlace al prototipo en Figma:** https://www.figma.com/proto/WffkIQ3gkDkkGvudgIFaSE/Semana-5-prototipo?node-id=8-1514&p=f&t=96qhywj7QGBmfssB-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=6%3A22

¿Qué cambios importantes incorporaron desde la semana 4?

- El formulario de crear idea se dividió en 3 secciones (Lo esencial, El equipo que buscas, Dale contexto) con barra de progreso, y se fusionaron los campos "objetivo del proyecto" y "público objetivo" en un solo campo de "Descripción".

- El botón "Aplicar" se renombró a "Postularme" y se separó visualmente del botón "Seguir". Con la versión de "Aplicar" nos indicaron que no era claro la función del botón.

- Se agregó una pantalla de confirmación tras publicar una idea con acceso directo a "Ver mi idea publicada", y una barra de navegación inferior fija con la pestaña "Mis proyectos".

- Las pantallas de detalle de proyecto ahora muestran los tags/categorías del proyecto de forma visible.

- Se agregó un onboarding de bienvenida que explica en 3 puntos para qué sirve la app antes de mostrar proyectos. En la semana 4 notamos que no era fácil para los usuarios identificar el propósito de la aplicación y por eso esta vez, se agregó onboarding.
- Quedaron diseñados los estados que no son el camino ideal —lista vacía, error de carga y contenido guardado sin conexión— que exigen los requisitos no funcionales.
- Se corrigió un problema de fondo en el avance del proyecto: antes la barra de progreso mostraba un porcentaje que la persona escribía a mano al publicar un avance, así que no significaba nada y podía retroceder. Ahora el porcentaje se calcula sobre los hitos cumplidos del proyecto (3 de 5 = 60%), y los avances son bitácora que puede marcar un hito como cumplido.


---

## Hallazgos principales

Resuman los 3 aprendizajes más importantes de esta nueva ronda de validación.

### Hallazgo 1

**¿Qué ocurrió?**

- Los participantes coincidieron en que el nuevo formulario de crear idea ya no se siente repetitivo. El estudiante de Sistemas comentó que ahora entiende qué información va en cada campo; el de Diseño Gráfico dijo que dividir el formulario en tres secciones ayuda a no sentir que hay que llenar todo de golpe.

**¿Qué significa?**

- La reestructuración de contenido (fusionar campos y dividir en secciones), y no solo un cambio visual, fue lo que resolvió la queja de redundancia detectada en la semana 4.

### Hallazgo 2

**¿Qué ocurrió?**

- El cambio de "Aplicar" a "Postularme", junto con la separación clara respecto al botón "Seguir", eliminó la confusión que tuvieron varios usuarios en la semana 4 sobre si ese botón postulaba a un proyecto o aplicaba una configuración. Ninguno dudó esta vez sobre qué hacía cada botón. Una participante describió por anticipado el comportamiento exacto: "esperaba que mi solicitud se enviara al líder del proyecto y que apareciera una confirmación", y confirmó que eso fue lo que pasó. Otra participante, en cambio, esperaba algo distinto: que "Postularme" abriera una especie de encuesta para recolectar datos y confirmar que de verdad podía aportar al proyecto; no reportó confusión al usar el flujo real, pero muestra que no todos anticipan el mismo mecanismo.

**¿Qué significa?**

- Confirma que el problema de la semana 4 era principalmente de nomenclatura (nombre del botón), no de ubicación o diseño visual. La expectativa de una validación previa tipo encuesta es un dato aislado por ahora, pero vale la pena tenerlo presente si en el futuro se evalúa agregar algún filtro antes de postularse.

### Hallazgo 3

**¿Qué ocurrió?**

- El estudiante de Ingeniería Industrial notó que ahora existen tres mecanismos distintos para dar o recibir retroalimentación sobre un proyecto (encuestas, comentarios en la vitrina, y retroalimentación por criterios con barras tipo rating), y no le quedó claro cuándo debería usarse cada uno.

**¿Qué significa?**

- La solución ganó funcionalidad de validación social, pero puede haber sobrecarga de opciones; falta decidir si estos mecanismos se mantienen separados o se simplifican.

---

## Dificultades detectadas

¿En qué partes hubo dudas, errores o confusión?

- El estudiante de Sistemas no distinguió de inmediato la diferencia entre las pestañas "Para tus habilidades" y "Explorar proyectos" hasta entrar a ambas.

- El estudiante de Industrial preguntó si el cierre del reclutamiento (cuando se llena el cupo del equipo) es automático o depende de que el líder lo cierre manualmente, ya que no le quedó claro.

- Una nueva participante (estudiante de Ingeniería de Sistemas) asumió que los proyectos mostrados en la pantalla principal están personalizados según su carrera ("identifica que soy estudiante de sistemas y me da proyectos relacionados a mi carrera"), cuando el criterio real de la pestaña son las habilidades e intereses del perfil, no el programa académico. Otra participante sí lo interpretó correctamente ("parecen estar seleccionados de acuerdo con las habilidades e intereses que uno registra en el perfil"), y una tercera se acercó también al criterio correcto ("probablemente son los que se alinean con los intereses del usuario que navega en la app"), así que el criterio se adivina, y más veces bien que mal, pero no de forma unánime.

- Una participante echó de menos información del proyecto antes de decidir si unirse: "me hubiera gustado encontrar más información sobre cada proyecto, como una descripción más detallada, los objetivos y qué actividades tendría que realizar como integrante". El detalle actual muestra descripción, habilidades requeridas y equipo, pero no qué se espera concretamente de quien entra.

- Una de las participantes indicó "Tuve la necesidad de explorar un poco al inicio para ubicar todas las opciones", aunque aclaró que no fue un bloqueo real, solo para comprender como navegar.

---

## Reacciones positivas

¿Qué elementos parecieron útiles, claros o valiosos para los usuarios?

- El onboarding de bienvenida con los 3 pasos explicando el propósito de la app antes de ver proyectos (destacado por Sistemas y Diseño Gráfico). Una nueva participante, tras ver ese onboarding, describió correctamente qué es la app y para qué sirve ("propuestas de proyectos dentro de la u, que le permite a los estudiantes unirse a o crear sus propios proyectos, llevando registro del progreso, responsables de actividades, etc."), justo el problema detectado en la semana 4. Otra participante más, antes de recibir ninguna instrucción, también describió el propósito correctamente ("una app en donde se exponen proyectos de cualquier tipo, sirve para encontrar qué proyecto se alinea más a mis intereses y participar en él").

- La barra de navegación inferior con acceso directo a "Mis proyectos" y el botón central de "Crear", que resuelve el problema de no poder volver a encontrar la idea propia publicada.

- Que el detalle del proyecto ahora sí muestre los tags y categorías del proyecto.

- El sistema de hitos y tareas pendientes dentro del workspace, muy bien recibido por el estudiante de Industrial, quien lo comparó con una herramienta de gestión de proyectos real.

- La gestión de postulantes mostrando las habilidades que cada persona aporta antes de aceptar o rechazar, elogiada por el estudiante de Sistemas.

- El botón "Postularme" generó exactamente la reacción esperada en dos nuevas participantes, que anticiparon correctamente "un mensaje de 'ya te postulaste', así como el que sale ya en la app", confirmando de nuevo que el cambio de nombre funcionó. El estado "Pendiente" tras postularse les hizo entender que la solicitud fue enviada y está esperando revisión del líder.

- La facilidad para encontrar dónde crear una idea, que en la semana 4 fue un hallazgo: una participante señaló que "las opciones de publicar y explorar proyectos se visualizan fácilmente" y calificó el recorrido completo con 5 de 5. Otra participante también calificó el recorrido con 5 de 5 y no reportó ningún momento de confusión.

---

## Citas o comentarios clave

Registren frases importantes de los usuarios.

> "Ya no siento que la app me pregunte lo mismo dos veces, ahora cada sección tiene su propósito claro" Estudiante de Ingenieria de Sistemas

> "El espacio de trabajo se siente como una herramienta pequeña de gestión de proyectos metida dentro de la app, eso ayuda mucho a no perder el hilo." Estudiante de Ingeniería Industrial

> "Creo que la app es para propuestas de proyectos dentro de la u, que le permite a los estudiantes unirse a o crear sus propios proyectos, llevando registro del progreso, responsables de actividades, etc." Estudiante de Ingeniería de Sistemas

> "Creo que es una plataforma para publicar ideas de proyectos y encontrar estudiantes de otras carreras que tengan las habilidades necesarias para formar un equipo o que estén realizando proyectos de interés." Respuesta a la primera pregunta, antes de recibir ninguna instrucción

> "Me hubiera gustado encontrar más información sobre cada proyecto, como una descripción más detallada, los objetivos y qué actividades tendría que realizar como integrante."

> "A primera vista pienso que es una app en donde se exponen proyectos de cualquier tipo, sirve para encontrar qué proyecto se alinea más a mis intereses y participar en él." Respuesta a la primera pregunta, antes de recibir ninguna instrucción

---

## Hipótesis confirmadas y no confirmadas

### Confirmadas

- Fusionar los campos de "objetivo" y "público objetivo" en una sola pregunta de "Descripción" reduce la sensación de redundancia detectada en la semana 4.

- Renombrar "Aplicar" a "Postularme" y separarlo visualmente de "Seguir" elimina la confusión de nomenclatura.
 
- Ofrecer un acceso directo a la idea recién publicada resuelve el problema de no poder encontrarla después.

- El onboarding de bienvenida ayuda a que los usuarios entiendan qué es la aplicación y para qué sirve, algo que en la semana 4 ningún participante lograba identificar a primera vista.

### No confirmadas

- No está confirmado que los usuarios entiendan de forma natural, sin ayuda, la diferencia entre "Para tus habilidades" y "Explorar proyectos". La evidencia quedó dividida: dos participantes se acercaron al criterio correcto (habilidades e intereses del perfil), una lo atribuyó al programa académico y otra no distinguió las dos pestañas hasta entrar a ambas.

- No está confirmado si tener tres mecanismos de retroalimentación en paralelo (encuestas, comentarios, vitrina con calificación) resulta útil o redundante para el usuario final.

- No está confirmado si la información que hoy muestra el detalle de un proyecto basta para decidir si unirse. Una participante pidió objetivos y actividades concretas del rol, que el prototipo no ofrece.

- No está confirmado que el modelo actual de "Postularme" (solicitud + confirmación) sea suficiente para todos los perfiles; una participante esperaba algún tipo de validación previa (tipo encuesta) antes de confirmar la postulación, aunque esto no le generó confusión al usar el prototipo.

---

## Comparación con la semana 4

¿Qué mejoró frente a la validación anterior?

- Se resolvió la redundancia de campos en el formulario de crear idea.

- Se resolvió la confusión con el botón "Aplicar" / "Postularme".

- Se resolvió el problema de no encontrar la idea propia después de publicarla.

- Se resolvió que las categorías/tags no se reflejaran en el detalle del proyecto.

- La mayoría de participantes logró explicar correctamente qué es la aplicación y para qué sirve tras ver el onboarding, algo que ninguno de los participantes de la semana 4 pudo hacer a primera vista. Es el hallazgo unánime de la semana anterior y el que más pesaba.
  
- Se resolvió que no se encontrara el botón de crear una idea: nadie preguntó dónde se publica, y una participante lo mencionó espontáneamente como algo que se ve con facilidad.

¿Qué problemas siguen presentes?

- Aparece un riesgo nuevo: posible sobrecarga de mecanismos de retroalimentación (encuestas + comentarios + vitrina).

- Sigue sin estar clara para algunos participantes la distinción entre las dos formas de explorar proyectos ("Para tus habilidades" vs "Explorar proyectos"), esta vez porque la funcionalidad es nueva.

- No es claro por qué aparecen ciertos proyectos y no otros en la pantalla principal. El criterio existe y está escrito en la pantalla, pero se lee como una suposición de cada quien y no como una regla del sistema.

- El detalle del proyecto no dice qué se espera de quien se une. Es la misma necesidad de "información transparente antes de unirse" que el equipo detectó en la semana 2 y dejó fuera del alcance, y que ahora un usuario volvió a pedir.
