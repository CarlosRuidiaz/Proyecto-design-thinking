# Plan de iteración

## Información del equipo

**Nombre del equipo: Grupo 4**

**Integrantes: Juan Bolívar, Claudia Elías, Juan Rojas, Carlos Ruidíaz**

---

## Qué debemos cambiar

¿Qué aspectos del prototipo integrado necesitan ajuste inmediato después de esta nueva validación?

1. Aclarar la diferencia entre las pestañas "Para tus habilidades" y "Explorar proyectos", por ejemplo con una breve descripción visible la primera vez que el usuario entra a esa pantalla.

2. Revisar el tratamiento visual de las imágenes en placeholder (tarjetas de proyecto y galería del workspace), para que no den sensación de producto incompleto.

3. Definir con claridad si el cierre del reclutamiento del equipo debe ser automático al llegar al cupo máximo, o si se mantiene manual pero con un aviso más visible para el líder del proyecto.

4. Ampliar la información del proyecto en la pantalla de detalle. Una participante pidió objetivos y, sobre todo, qué actividades tendría que realizar como integrante. Hoy el detalle muestra descripción, habilidades requeridas y equipo, pero no qué se espera de quien entra, que es justo lo que una persona necesita para decidir si se postula.

5. Definir la visibilidad del botón "Salir del proyecto". Está al final del espacio de trabajo, pero el proyecto de ejemplo es uno que la usuaria lidera, y un líder no se va de su propio proyecto: cierra el reclutamiento o transfiere el liderazgo. Es una regla de negocio que el prototipo todavía no representa.

6. Corregir dos inconsistencias en los datos de ejemplo, detectadas al revisar el prototipo: "App de movilidad sostenible" aparece con 4 de 6 miembros en "Mis proyectos" y con 3 de 5 en el perfil de estudiante; y "Directorio verificado de residencias" está en etapa Research en el listado de exploración y en Prototype en la vitrina. No son errores de diseño sino de contenido, pero un usuario en prueba puede leerlos como un fallo del sistema.
---

## Prioridades

Clasifiquen los cambios propuestos.

### Cambios urgentes

- Diferenciar mejor las pestañas "Para tus habilidades" vs "Explorar proyectos".

- Definir tratamiento de los placeholders de imagen en tarjetas y galería.

- Unificar los datos de ejemplo del mismo proyecto entre pantallas, antes de la siguiente ronda de pruebas.

### Cambios importantes

- Decidir si el cierre de reclutamiento es automático o manual, y hacerlo más visible.

- Evaluar si conviene consolidar o simplificar los tres mecanismos de retroalimentación (encuestas, comentarios, panel con calificación).

- Ampliar el detalle del proyecto con objetivos y con lo que se espera de cada integrante. Es la necesidad de "información transparente antes de unirse" que el equipo detectó en la semana 2, dejó fuera del alcance, y que un usuario volvió a pedir en esta validación.

- Cerrar la regla de "salir de un proyecto" y su equivalente para el líder, que hoy no existe en ninguna pantalla.

- Convertir en componentes la tarjeta de proyecto, el chip de habilidad y la etiqueta de etapa. El botón de volver y el de seguir ya lo son. Se dejó fuera a propósito antes de esta validación, porque las reacciones de navegación viven dentro de los frames de las tarjetas y sustituirlas obliga a volver a enlazarlas una por una.

### Ideas para más adelante

- Explorar la posibilidad mensajería directa entre líder y postulante antes de aceptar o rechazar una postulación, así como para responder dudas antes de aplicar.

- Explorar algún tipo de reconocimiento al completar hitos del proyecto.

- Revisar si el módulo de encuestas podría integrarse dentro de la vitrina de prototipos en vez de ser una sección aparte.

- Agregar un calendario o vista consolidada de tareas pendientes de todos los proyectos en los que participa el usuario, para no tener que entrar a cada proyecto por separado (sugerido por una participante en la validación de la semana 5).

---

## Decisión del equipo

Después de validar, ¿qué decisión toman?

- [x] Mantener la estructura general y mejorar detalles.
- [ ] Ajustar algunos flujos importantes.
- [ ] Replantear parte de la integración entre flujos.
- [ ] Cambiar el enfoque del problema.

La estructura se sostuvo. Los cinco hallazgos de la semana 4 quedaron resueltos: los participantes explicaron qué es la aplicación antes de recibir cualquier instrucción, encontraron la idea propia, entendieron "Postularme", identificaron las categorías en el detalle y nadie preguntó dónde se crea una idea. Los problemas que aparecieron esta vez son de otra naturaleza: no son fallas del recorrido sino preguntas sobre qué significa cada cosa —qué distingue las dos pestañas, cuándo usar cada mecanismo de retroalimentación, qué se espera de un integrante—. Son ajustes de claridad y de contenido, no de integración, y por eso no hace falta replantear los flujos.

---

## Próximo paso

¿Qué debería hacer el equipo en la siguiente iteración o etapa de desarrollo?

- Ajustar en Figma los cambios marcados como "urgentes" antes de la siguiente ronda de pruebas.

- **Definir la arquitectura antes de escribir pantallas.** El enunciado exige Clean Architecture, GetX para inyección de dependencias, ruteo y manejo de estado, y Roble como servicio de autenticación y backend. Con 33 pantallas ya definidas, el trabajo inmediato es mapear cada una a su ruta, su controlador y sus casos de uso. El prototipo deja de ser una maqueta y pasa a ser la especificación de ese mapeo.

- **Terminar el sistema de componentes.** Cada componente reutilizable de Figma se traduce en un widget de Flutter. El botón de seguir ya está modelado como lo que realmente es —un estado booleano con dos variantes, no una navegación a otra pantalla— y ese es el criterio que conviene seguir con la tarjeta, el chip y la etiqueta de etapa.

- **Modelar los datos derivados en vez de guardarlos.** El caso del porcentaje de avance dejó una lección aplicable al resto: era un campo que el usuario escribía y ahora se calcula a partir de los hitos cumplidos. Antes de implementar conviene revisar qué otros números deben calcularse, empezando por los contadores de miembros y de postulaciones pendientes.

- **Resolver el caché sin conexión desde el diseño.** La pantalla del estado sin conexión ya avisa que se está viendo contenido guardado, pero falta decidir qué se guarda localmente, cuánto, y qué se le permite hacer al usuario en ese modo.

---

## Nivel de preparación para implementación

Después de esta etapa, ¿cómo se encuentra el equipo?

- [x] Listo para pasar a una implementación inicial.
- [ ] Necesita una iteración más antes de implementar.
- [ ] Debe replantear una parte importante de la propuesta.

Expliquen brevemente por qué.

El criterio que el equipo acordó antes de probar era pasar a implementación si los cinco hallazgos de la semana 4 quedaban resueltos y el ciclo de vida del proyecto se recorría sin confusiones graves. Las dos condiciones se cumplieron, y una participante calificó el recorrido completo con 5 de 5.

Los problemas detectados en esta ronda son de claridad y de contenido —nombres de pestañas, cantidad de mecanismos de retroalimentación, profundidad de la información del proyecto— y ninguno obliga a rehacer un flujo. Se pueden resolver en Figma en paralelo al arranque de la implementación, que en esta etapa depende sobre todo de definir la arquitectura y el mapeo de pantallas a rutas y controladores.



