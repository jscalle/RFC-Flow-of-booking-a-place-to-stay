Fecha de inicio: 2021-03-01
Miembros: Cristian Castillo, Juan Sebastian Calle
RFC PR: 
Resumen
Flujo de la reserva de un lugar para alojarse 
El proceso de reserva comienza desde la sección de búsqueda y/o lista de resultados por defecto realizando una solicitud de habitaciones según su disponibilidad, de acuerdo con el resultado de una consulta realizada a las habitaciones disponibles el usuario realiza la reserva según sus necesidades y requerimientos, dentro de las opciones que podrá observar el usuario tendrá diferentes servicios que podrá agregar a lo que desea adquirir en su reserva, el sistema realizará diferentes validaciones que le darán al usuario la seguridad que todo los requerimientos seleccionados están disponibles y los detalles necesarios, antes de la confirmación del pago, el usuario deberá realizar un registro o un ingreso a su cuenta, esto con el objetivo de tener los datos básicos necesarios para realizar la reserva, como nombre, documento de identidad, correo electrónico de contacto y teléfono de contacto, adicionales a los otros datos posiblemente requeridos, al momento de realizar un login y de confirmar se realizará una reserva “provisional” de aproximadamente 20 minutos que tendrá el usuario para realizar los pagos necesarios, al recibir la confirmación del pago el sistema le otorgará al usuario el resumen actualizado de su reserva, con las opciones de imprimir o un QR para su posterior lectura y validación en las instalaciones, adicional se enviará un correo electrónico pasado estos 20 minutos si el sistema no recibe la confirmación del pago de parte del usuario se volverá a poner como disponible los recursos que se habían previamente seleccionado

Ejemplo básico
Flujo.JPG (1412×514) (firebasestorage.googleapis.com)
Motivación
¿Por qué lo hacemos?
Es el proceso puntual por el cual todo el sistema de reserva toma coherencia y/o sentido, la experiencia de usuario en este punto es uno de los temas que podrá ayudar a que sea utilizado el servicio y se realice una reserva
¿Cuál es el resultado esperado?
Se espera que el flujo sea lo más adecuado y agradable para un usuario que requiere de una reserva en un lugar adecuado, es necesario previamente buenos match en la consulta, pero el flujo que lleva el usuario es importante para su experiencia

Diseño detallado
Este es el grueso de la RFC. Explica el diseño con el suficiente detalle para que alguien familiarizado con React lo entienda, y para que alguien familiarizado con la implementación lo ponga en práctica. Esto debería entrar en detalles y casos de esquina, e incluir ejemplos de cómo se utiliza la característica. Cualquier terminología nueva debe ser definida aquí.

Inconvenientes
¿Por qué no deberíamos hacer esto? Hay que tener en cuenta

el coste de implementación, tanto en términos de tamaño de código como de complejidad
si la característica propuesta puede ser implementada en el espacio de usuario
el impacto en la enseñanza de React
la integración de esta función con otras funciones existentes y previstas
el coste de la migración de las aplicaciones React existentes (¿es un cambio de ruptura?)
La elección de cualquier camino tiene ventajas y desventajas. Intenta identificarlos aquí.

Alternativas
¿Qué otros diseños se han considerado? ¿Cuál es el impacto de no hacerlo?

Estrategia de adopción
Si aplicamos esta propuesta, ¿cómo la adoptarán los actuales desarrolladores del C9? ¿Se trata de un cambio radical? ¿Podemos escribir un codemod? ¿Debemos coordinarnos con otros proyectos o bibliotecas?

¿Cómo lo enseñamos?
¿Qué nombres y terminología funcionan mejor para estos conceptos y por qué? ¿Cuál es la mejor manera de presentar esta idea? ¿Como una continuación de los patrones de los proyectos C9 existentes?

¿Significa la aceptación de esta propuesta que la documentación del C9 debe ser reorganizada o alterada? ¿Cambia la forma en que se enseña el C9 a los nuevos desarrolladores a cualquier nivel?

¿Cómo debería enseñarse esta característica a los desarrolladores del C9 existentes?

Preguntas sin resolver
*
