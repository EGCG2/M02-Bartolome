# mavenParte3_egc
Correspondiente a la 3º practica Maven de EGC

- Se ha añadido a nuestro pom.xml un plugin conocido como "checkstyle" (mvn checkstyle:help) con el podemos ver los fallos de estilo en el codigo java.
- Se ha eñadido mediante la etiqueta <execution> para que al hacer "mvn test" ejecute directamente el plugin y nos informe de los posibles errores, podemos ver una descripción detallada de los errores en target/checkstyle-result
