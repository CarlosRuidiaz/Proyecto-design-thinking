# Reflexión final de la primera etapa

## Información del equipo

**Nombre del equipo: Grupo 4**

**Integrantes: Juan Bolívar, Claudia Elías, Juan Rojas, Carlos Ruidíaz**

---

## Lo que aprendimos del problema

¿Cómo cambió su comprensión del problema desde la semana 1 hasta la semana 5?

- En la semana 1 entendíamos el problema como una barrera de acceso: a los estudiantes les daba miedo exponer una idea incompleta y les costaba encontrar colaboradores fuera de su círculo cercano. Con las validaciones fuimos viendo que el problema no era solo "falta de funciones" para publicar o buscar proyectos, sino cómo se comunica y organiza esa información. Pequeños detalles, como qué preguntas hacía el formulario o cómo se nombraba un botón, generaban tanta fricción como la ausencia de una función completa.
- La prueba de la semana 4 nos mostró algo que ninguna entrevista nos había dicho: cinco de cinco personas recorrieron la aplicación sin ayuda y ninguna entendió qué era. Un sistema puede ser perfectamente navegable y aun así no comunicar para qué existe; son dos problemas distintos y estábamos resolviendo solo uno. Visto desde la semana 5, el problema ya no es "los estudiantes no encuentran con quién trabajar", sino que el ciclo completo de un proyecto universitario —proponerlo, entenderlo desde afuera, sumarse, avanzar en equipo y mostrar resultados— no tiene hoy ningún lugar donde ocurrir de forma visible.

---

## Lo que aprendimos de la solución

¿Qué descubrieron sobre los flujos y la solución integrada que decidieron prototipar?

- Descubrimos que los flujos no funcionan de forma aislada: crear una idea, explorar proyectos, postularse, formar equipo y documentar avances están conectados, y una falla en uno (como no poder volver a encontrar tu propia idea) afecta la percepción de todos los demás. También aprendimos que agregar funciones nuevas (workspace, encuestas, vitrina de prototipos) resuelve unas necesidades, pero puede introducir nuevas dudas, como no saber para qué sirve cada mecanismo de retroalimentación si se agregan varios a la vez.

- Otra cosa que descubrimos es que un dato de la interfaz puede verse bien y no significar nada. La barra de "avance del proyecto" mostraba un porcentaje que la persona escribía a mano al publicar un avance: dos miembros podían moverla en direcciones opuestas y nada lo impedía. Al preguntarnos de dónde debería salir ese número nos dimos cuenta de que teníamos tres cosas mezcladas en una sola barra: la etapa, que es cualitativa; los hitos, que son finitos y se cumplen; y los avances, que son bitácora. Cuando un dato de la interfaz no tiene un origen claro, el problema casi nunca es de la interfaz: es que faltaba separar dos conceptos que parecían uno.


---

## Valor de la validación

¿Qué aportó validar primero versiones exploratorias y luego un prototipo más integrado antes de desarrollar una versión más completa?

- Las versiones exploratorias de baja resolución nos permitieron detectar y corregir errores de fondo (como preguntas redundantes o botones ambiguos) de forma rápida y barata, antes de invertir tiempo en construir el prototipo integrado completo. Luego, validar el prototipo integrado nos permitió confirmar con evidencia concreta que esos ajustes sí funcionaron, y detectar problemas nuevos que solo aparecen cuando los flujos están conectados entre sí, algo que no se hubiera visto probando cada flujo por separado.

---

## Principal decisión

¿Cuál es la decisión más importante que toma el equipo después de esta etapa?

- Mantener la estructura general del prototipo integrado y enfocar la siguiente iteración en pulir detalles de claridad (nombres de secciones, estados del sistema, cantidad de mecanismos de retroalimentación) en lugar de replantear el enfoque del producto, ya que la evidencia recogida hasta ahora respalda la dirección tomada.

- Esta decisión implica dejar de tratar el prototipo como una maqueta de dos flujos y convertirlo en la base real de la implementación en Flutter. Pasó de 5 pantallas a 33 y ahora cubre los nueve grupos de requisitos del enunciado, cuando al cerrar la semana 4 cubría dos.

---

## Conclusión final

Escriban un párrafo de 8 a 12 líneas respondiendo esta pregunta:

`¿Qué aprendió el equipo sobre diseñar una solución real antes de empezar a implementarla con más fuerza?`

- Si algo nos quedó claro en esta etapa es que diseñar no es "pensarlo bien una vez y ya", sino un ciclo de proponer, mostrar, escuchar, y volver a ajustar. Varias veces llegamos a una prueba con algo que para nosotros como equipo tenía toda la lógica del mundo, y bastaba con que alguien de afuera lo viera por primera vez para darnos cuenta de que no era tan obvio, generaba dudas, o hacía que la persona repitiera lo mismo sin querer. Eso nos enseñó a no aferrarnos tanto a nuestras primeras decisiones. También nos sorprendió que cambios pequeños, como cambiarle el nombre a un botón o juntar dos preguntas que se sentían iguales, terminaran teniendo tanto impacto como agregar una función nueva completa. Otra cosa que aprendimos es que cada persona ve la app distinto: unos se fijan en si el flujo funciona, otros en cómo se ve, otros en la lógica del proceso, y justo por eso validar con gente de carreras distintas nos ayudó a no quedarnos con una sola mirada. Y para cerrar, nos quedamos con la sensación de que uno nunca termina de validar del todo, siempre va a quedar algo por probar, pero eso más que frustrarnos nos deja con más humildad y más claridad sobre qué priorizar antes de meterle más fuerza a construir la versión final.
