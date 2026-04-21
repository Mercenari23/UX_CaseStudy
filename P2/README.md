## Paso 2. UX Design  



### 2.a Reframing / IDEACION: Feedback Capture Grid / EMpathy map 
![Método UX](img/feedback-capture-grid.png) 
----

A partir del análisis de la práctica anterior detectamos una oportunidad clara en el mercado de restauración temática. La competencia ofrece experiencias visualmente atractivas, pero presenta varias limitaciones desde el punto de vista de la experiencia de usuario: menús poco flexibles, escasa ayuda durante el proceso de elección, navegación mejorable, poca personalización, falta de herramientas de búsqueda y una propuesta temática que en muchos casos se queda solo en lo decorativo. Estas debilidades nos permiten replantear el problema no como “hacer otro restaurante anime”, sino como diseñar una experiencia gastronómica temática que sea inmersiva, comprensible, personalizada y fácil de usar.

Nuestro usuario busca algo más que comer: quiere una experiencia divertida, compartible y con identidad propia. Sin embargo, también necesita claridad a la hora de elegir, entender bien los ingredientes, recibir ayuda en el proceso y completar el pedido sin fricción. Esto es especialmente importante en un concepto como el nuestro, donde la personalización del plato forma parte central de la experiencia.

Problema de diseño: los restaurantes temáticos existentes generan interés por su estética, pero no siempre convierten esa atracción inicial en una experiencia digital y presencial clara, personalizada y memorable. La falta de orientación, personalización bien guiada y continuidad entre el concepto temático y la interacción real hace que el valor percibido disminuya.

Hipótesis: si diseñamos una experiencia de pedido basada en una metáfora reconocible para el público objetivo —un “PC Pokémon” desde el que crear tu equipo de 6 ingredientes—, con navegación simple, ayudas visuales, opciones claras y recompensas mediante un sistema de medallas, entonces aumentará la satisfacción del usuario, la sensación de inmersión y la probabilidad de repetición.

Propuesta de valor: PokéBowl League combina restauración temática e interfaz guiada para que el usuario no solo consuma comida, sino que “forme su equipo”, descubra platos inspirados en entrenadores y gimnasios, y reciba recompensas por volver. El valor diferencial no está solo en la ambientación, sino en transformar el pedido en una experiencia jugable, comprensible y socialmente compartible.

A continuación hemos hecho un Empathy Map para destacar los puntos más importantes para esas personas que están de algún modo interesadas con nuestro producto. Nos sirve para saber que es lo bueno y malo de nuestro producto y cómo se sienten nuestros clientes respecto a ello.

<img width="729" height="660" alt="image" src="https://github.com/user-attachments/assets/3198ef1d-34cc-4455-a277-a3f115c3f5f1" />


### 2.b ScopeCanvas
![Método UX](img/ScopeCanvas.png)
----

Se ha elaborado un ScopeCanvas para definir el alcance funcional y estratégico de POGO RAMEN. En él se recoge como idea principal el diseño de una experiencia digital de pedido para un restaurante temático Pokémon orientado a jóvenes y adultos fans del anime, la cultura pop y la comida japonesa.

Los objetivos del producto son:

facilitar un proceso de pedido claro y entretenido;
permitir la personalización del plato de forma guiada;
reforzar la inmersión temática mediante metáforas del universo Pokémon;
fomentar la repetición con un sistema de fidelización basado en medallas;
mejorar la visibilidad social del restaurante gracias a una experiencia visualmente compartible.

Las funcionalidades prioritarias definidas en el ScopeCanvas son: exploración de la carta, creación de plato personalizado “equipo de 6”, selección de menús temáticos, visualización de ingredientes y alérgenos, reserva de mesa, consulta del estado del pedido y acceso al sistema de medallas o recompensas. Como funcionalidades secundarias se contemplan compartir platos en redes, guardar combinaciones favoritas y repetir pedidos anteriores.

Con este canvas delimitamos el MVP del producto en torno a la experiencia de pedido y reserva, dejando para fases posteriores funciones de comunidad y personalización avanzada.

![](img/ScopeCanvas.png)

### 2.b User Flow (task) analysis 
![Método UX](img/Sitemap.png) 
-----

Se ha definido un User Flow centrado en la tarea principal del sistema: realizar un pedido personalizado en el restaurante. Esta tarea representa el núcleo de la propuesta de valor, ya que convierte la elección de comida en una experiencia temática inspirada en la construcción de un “equipo Pokémon”.

El flujo principal comienza cuando el usuario accede a la pantalla inicial del sistema de pedido. Desde ahí puede elegir entre consultar la carta general, reservar mesa o iniciar directamente la creación de su plato. Si selecciona la opción de creación personalizada, el sistema le guía paso a paso para elegir base, proteínas, toppings, salsas y extras, mostrando nombres, descripciones e información relevante para evitar confusión. Una vez completado el “equipo de 6”, el usuario revisa el resumen del pedido, confirma, añade posibles complementos y finaliza el proceso. Finalmente recibe una confirmación y, si está registrado, se actualiza su progreso en la tarjeta de medallas.

También se han contemplado flujos secundarios como consultar menús temáticos ya preparados, repetir un pedido anterior, revisar alérgenos o hacer una reserva. Estos recorridos secundarios ayudan a cubrir perfiles de usuario distintos: desde quien quiere experimentar y personalizar hasta quien busca rapidez y comodidad.

El análisis de tareas nos permite reducir fricciones detectadas en la competencia, sobre todo en claridad del menú, orientación del usuario y facilidad de navegación.


### 2.c IA: Sitemap + Labelling 
![Método UX](img/labelling.png) 
----

Sitemap:

<img width="945" height="472" alt="image" src="https://github.com/user-attachments/assets/b5bf64a8-1096-48c0-bb7d-5b5cce7a4958" />

Labelling:

Término | Significado     
| ------------- | -------
  Entrar  | Acceder a la página principal
  Continuar con Google | Iniciar sesión con Google
  Continuar con Facebook | Iniciar sesión con Facebook
  Volver al inicio | Volver a la página principal
  Sistema PC Pokémon | Puedes mirar tu equipo
  Menú principal | Puedes mirar el menú principal 
  Crear tu equipo | Crear tu equipo (plato)
  Menús entrenadores | Menús de platos hechos (1-1)
  Ligas regionales | Menús de varios platos con misma temática
  Tu tarjeta | Puedes ver tus "medallas"
  Añadir alimento | Añadir alimento al equipo (plato)
  Tu equipo | Puedes ver los alimentos que tienes
  Volver | Volver a la página de atrás
  Añadir | Añadir al carro
  Tu pedido | Ver lo que tienes en el pedido (alimentos/platos)
  Confirmar pedido | Confirmar el pedido
  Seguir comprando | Seguir comprando en la app
  Escanea para validar | QR para diversas ofertas
  
  


### 2.d Wireframes
![Método UX](img/Wireframes.png) 
-----

En esta fase se han desarrollado distintos wireframes en baja fidelidad con el objetivo de definir la estructura, navegación y distribución de contenidos del sistema antes de aplicar el diseño visual final. Para su elaboración se han utilizado herramientas como Figma y Balsamiq, lo que ha permitido iterar de forma rápida y centrarse en la funcionalidad y la experiencia de usuario.

Los wireframes representan las principales pantallas del sistema de pedido del restaurante temático, cubriendo tanto el flujo principal como funcionalidades secundarias clave. A través de ellos se ha buscado simplificar la interacción del usuario, mejorar la comprensión del menú y reforzar la temática del producto sin comprometer la claridad.

En conjunto, estos wireframes permiten validar la arquitectura de la información, los flujos de navegación y las decisiones de diseño antes de avanzar a fases de mayor fidelidad. Además, aseguran que la experiencia propuesta sea coherente, accesible y alineada con las necesidades detectadas en fases anteriores.

## Imágenes de wireframes

Así se ve la página principal del sistema.  
![Menu PC](./img/MenuPC.png)

Así se ve la creación del equipo de 6 o menú personalizado.    
![Equipo de 6](./img/Equipo6.png)

Así se ve el menú de entrenadores.   
![Entrenadores](./img/Entrenadores.png)

Así se ve el menú de ligas.  
![Liga](./img/Ligas.png)

Así se ve el carrito de compra.   
![Carrito](./img/Compra.png)

Así se ve el sistema de inicio de sesión.   
![Login](./img/login.png)

Así se ve el sistema de fidelización. 
![Medallas](./img/medallas.png)

Así se ve la web del usuario.  
![Web usuario](./img/Web.png)

<br>
