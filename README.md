Eventify es un sitio web para agendar eventos con día, hora y lugar específicos. Use dos patrones de diseño:
Patrón Singleton
Esteasegura que solo haya una instancia de la clase Event en toda la aplicación. Si se intenta crear otro evento, siempre se usará la misma instancia. Esto evita que se dupliquen los eventos.
Patrón Factory
Este permite crear diferentes tipos de asistentes (por ejemplo, estudiantes o profesionales) sin especificar exactamente qué tipo. La clase AttendeeFactory se encarga de esto al generar el tipo adecuado según lo que se seleccione en el formulario.

