# Informe entrega 1

## Repositorio Git

#### Comandos utilizados

git clone - lo utilizamos para clonar el repositorio y poder empezar a trabajar sobre el mismo a nivel local

git status - para ver los cambios hechos pero no prontos para commitear.

git add - para pasar los cambios a staging

git commit - para realizar el commit de los cambios que se encuentran en staging

git push - para subir los cambios al repositorio

git pull - para actualizar el repositorio local y trabajar sobre la última versión del proyecto.

#### 1. Roles y Contribuciones

- **Carola**: Se sera la principal responsable de supervisar y gestionar los "merge" hacia las ramas principales. Esta responsabilidad implica garantizar la integridad y coherencia del código antes de la unión final.
- **Joaquín y Nicolas**: Ambos desempeñaron roles cruciales en el desarrollo, asegurándose de sincronizar regularmente sus entornos locales con los cambios más recientes que Carola integraba en las ramas principales.

#### 2. Procedimientos Utilizados

- Cada miembro del equipo trabajaba en ramas individuales, permitiendo un desarrollo paralelo y eficiente de características y correcciones.
- Al finalizar una tarea, se generaba una solicitud de revisión (comúnmente conocida como "pull request"). Carola, como revisor, evaluaba y validaba estos cambios, asegurando su calidad y funcionalidad.
- Una vez validados, los cambios se integraban en las ramas principales. Joaquín y Nicolas, en su compromiso con la actualización , descargaban estos cambios para mantener sus versiones locales al día, mediante "pulls".

#### 3. Buenas Prácticas

- Se promovió una cultura de no hacer "push" directamente a las ramas principales sin una revisión previa, garantizando así la calidad del código.
- La comunicación constante y la sincronización fueron esenciales para evitar conflictos y asegurar una integración fluida de las contribuciones de todos.

## Versionado

En nuestro proceso de versionado, hemos adoptado la práctica de trabajar con dos ramas principales: "master" y "develop". La elección de estas ramas se basa en una estructura de desarrollo eficiente y colaborativa. Para entender cuándo y por qué usar estas ramas, es importante conocer nuestra Convención de commit, que está inspirada en la Convención de Commit de Angular. A continuación brindamos una descripción de dicha convención.

#### Nombres de ramas:

- feature/… : Esta etiqueta se emplea para introducir nuevas características o funcionalidades en proceso de desarrollo. Por ejemplo, una rama titulada feature/user-authentication podría estar vinculada a la implementación de la autenticación de usuarios.

- fix-... : La etiqueta fix se reserva para la corrección de errores o la solución de problemas identificados en el código. Por ejemplo, una rama llamada fix/login-bug podría estar asociada con la eliminación de un error en el proceso de inicio de sesión.

- refactor/… : La etiqueta refactor se utiliza cuando se efectúan modificaciones en el código con el objetivo de mejorar su estructura o legibilidad, sin añadir nuevas funcionalidades ni resolver errores directamente. Por ejemplo, una rama llamada refactor/reorganize-code podría estar relacionada con la reorganización del código existente

#### Mensajes de commits:

Los mensajes de commit también siguen una convención específica que se divide en un encabezado y un cuerpo. Los encabezados más utilizados son los siguientes.

- feat: … Utilizado para agregar nuevas características o funcionalidades. A modo de ejemplo, feat: user authentication added.

- fix:... Utilizado para correcciones de errores.

- refactor:... Utilizado para cambios de refactorización en el código.

Elegimos utilizar la convención de angular para poder facilitar la revisión de cambios y la introducción de nuevas características o funcionalidades. Además ayuda a mantener un registro detallado y ordenado de los tipos de cambios que se han realizado en el proyecto.

## Elicitación

Para desempeñar la sección de elicitación del trabajo, optamos por utilizar las siguientes técnicas vistas en clase, para las cuales daremos su propósito y motivo de uso:

1. **Lluvia de ideas:** La lluvia de idea fue el primer instinto del equipo, utilizando este técnica para para pensar las preguntas de la entrevista llevada a cabo con el cliente respecto a las especificaciones del sistema a crear para ellos. También utilizamos esta técnica para realizar los bocetos de UI que fue presentado al cliente.

2. **Entrevista:** Utilizando la técnica de elicitación mencionada previamente, el equipo resolvió utilizar la siguiente guía de preguntas para llevar acabo la entrevista, sin embargo, no quisimos que la entrevista sea 100% estructurada, permitiendo que el cliente pueda explayar en sus necesidades, objetivos y requisitos para la aplicación a crear:

**Necesidades Básicas:**

¿Cuáles son las funcionalidades básicas que te gustaría que tuviera la aplicación para ordenar las viandas de tus hijos?

**Personalización del Menú:**

¿Te gustaría tener la opción de personalizar las viandas de tus hijos según sus preferencias y necesidades alimenticias?

**Información Nutricional:**

¿Consideras importante tener acceso a la información nutricional de cada plato disponible en el menú?

**Métodos de Pago:**

¿Qué métodos de pago te parecerían más convenientes para utilizar en la aplicación?

**Programación de Pedidos:**

¿Te gustaría poder programar los pedidos con antelación, por ejemplo, para toda la semana o el mes?

**Notificaciones y Recordatorios:**

¿Te gustaría recibir notificaciones y recordatorios para realizar los pedidos o para informarte sobre promociones y nuevos ítems en el menú?

**Precio y Promociones:**

¿Qué tan importante es para ti tener acceso a promociones, descuentos o programas de lealtad a través de la app?

**Feedback y Calificaciones:**

¿Te gustaría poder dejar comentarios y calificaciones sobre la calidad de las viandas y el servicio recibido?

**Interfaz y Usabilidad:**

¿Tienes alguna preferencia en cuanto al diseño y la usabilidad de la aplicación?

**Soporte y Ayuda:**

¿Qué tipo de soporte al cliente te gustaría que estuviera disponible en caso de tener problemas o dudas con tus pedidos?

**Información sobre Alergias y Restricciones:**

¿Cómo te gustaría que la app maneje la información sobre alergias alimentarias o restricciones dietéticas?

**Comunicación con la Cantina:**

¿Te gustaría tener la posibilidad de comunicarte directamente con el personal de la cantina a través de la aplicación para realizar consultas o solicitudes especiales?

3. **Ingeniera Inversa:** La ingeniera inversa es un gran recurso para complementar los ideas propuestas por el grupo, ya que proporciona un marco sobre el cual trabajar con prácticas ya probadas por otros, sin descartar las ideas originales de los integrantes del equipo.

En este caso, realizamos una búsqueda de aplicaciones ya existentes que estén en línea con nuestro objetivo de aplicación. Durante esta búsqueda, encontramos la aplicación de NutriSlice, la cual es utilizada por colegios y escuelas de los Estados Unidos, permitiendo la búsqueda de menues predeterminados, incluyendo los valores nutricionales de dichas comidas y la opción de hacer pedidos adelantados de las misma.

El objetivo primario de descargar esta aplicación fue analizar la interfaz para el usuario y determinar qué tan amable es para ellos. Llevando a cabo este análisis, llegamos a la conclusión de que la interfaz de la aplicación no es la más ‘user friendly’, ya que proporciona pocas visuales guías para usuarios. Como principiantes utilizando la aplicación, sentimos que hubo una curva de aprendizaje para su utilización. Sin embargo, esto se explica con el hecho de que NutriSlice es una aplicación masiva usada a través de todos los Estados Unidos por lo cual deben adaptarse a muchas presiones externas, lo nos permitió identificar una gran diferencia entre nuestras aplicaciones, siendo que nuestra aplicación seria mas localizada y enfocada a nuestro cliente.

Uno de los puntos fuertes de NutriSlice es su diseño del valor nutricional de la comida, al igual que un sistema de puntaje para cada ítem de comida, lo cual no fue pensado por nosotros.

**Análisis de documentación:**  Mediante una investigación de documentación existente a cerca de proyectos similares llevados a cabo en el pasado fuimos capaces de encontrar el siguiente informe: 202207221212165_1183.pdf (upm.edu.my) el cual trata nuestro tema específicamente.

Dicho informe desglosa varias de las necesidades de alumnos que almuerzan en una cafetería, lo cual ayuda a tomar en cuenta otro tipo de perfil de usuario el cual no tuvimos en cuenta para nuestra entrevista. De los requerimientos y necesidades mencionadas en el estudio, creemos que los siguientes comparten nuestro enfoque: lista de comidas y bebidas, la posibilidad de agregar al carrito, poder enviar pedidos, una recomendación de comida, verificar pedido, rastrear pedido, notificación de pedido, sin efectivo (pago a través de QR), retroalimentación, ahorro de tiempo y facilidad de uso. 

**User Personas:** Identificamos 3 perfiles usuarios en nuestra aplicación: 

![Alt text](image-2.png)
![Alt text](image-3.png)


## Especificación

Ultilizaremos el método **MOSCOW**, es una técnica utilizada para priorizar requisitos en un proyecto. Las categorías son:

#### M (Must have)

Requisitos esenciales sin los cuales el sistema no funcionará.

#### S (Should have)

Requisitos importantes pero no vitales.

#### C (Could have)

Requisitos deseables pero no necesarios.

#### W (Won't have this time)

Requisitos que no se implementarán en esta versión pero podrían considerarse en el futuro.

### Requerimientos Funcionales:

##### M (Must have)

- **Título**: Mostrar Menú
- **Descripción**: La aplicación debe mostrar el menú diario disponible en la cantina.
- **Prioridad**: Alta

- - **Título**: Información Nutricional
  - **Descripción**: Cada ítem del menú debe mostrar su tabla nutricional, enfocándose en la cantidad de proteína.
  - **Prioridad**: Alta

  - **Título**: Indicador para Celiacos y Alergias
  - **Descripción**: La aplicación debe indicar claramente qué alimentos son aptos para celiacos o personas con alergias específicas.
  - **Prioridad**: Alta

  - **Título**: Métodos de Pago
  - **Descripción**: La aplicación debe aceptar todos los métodos de pago disponibles.
  - **Prioridad**: Alta

##### S (Should have)

- **Título**: Elección de Menú Semanal
- **Descripción**: La aplicación debe permitir a los usuarios seleccionar su menú para toda la semana o mes.
- **Prioridad**: Media

- **Título**: Promociones
- **Descripción**: La aplicación debe mostrar promociones especiales o descuentos disponibles.
- **Prioridad**: Media

- **Título**: Contacto Directo
- **Descripción**: La aplicación debe proporcionar un método para que los usuarios se comuniquen directamente con una persona de la cantina.
- **Prioridad**: Media

### Requerimientos No Funcionales:

##### M (Must have)

- **Título**: Consistencia
- **Descripción**: La aplicación debe ofrecer una experiencia de usuario consistente en todas las secciones.
- **Prioridad**: Alta

##### S (Should have)

- **Título**: Tiempo de Respuesta
- **Descripción**: La aplicación debe tener un tiempo de respuesta rápido para todas las acciones del usuario.
- **Prioridad**: Media

##### C (Could have)

- **Título**: Personalización de Interfaz
- **Descripción**: La aplicación podría ofrecer opciones de personalización de interfaz para los usuarios.
- **Prioridad**: Baja

##### W (Won't have this time)

- **Título**: Integración con Redes Sociales
- **Descripción**: En versiones futuras, la aplicación podría integrarse con redes sociales para compartir promociones o menús.
- **Prioridad**: Futura

## Validación y verificación

## Reflexión
