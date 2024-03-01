# EmailDev-SB3-Template-SMTPTest

¡Bienvenido a EmailDev-SB3-Template-SMTPTest! Este proyecto sirve como plantilla para implementar funcionalidades de correo electrónico en aplicaciones Spring Boot 3, incluyendo pruebas SMTP. Ya sea que seas nuevo en Spring Boot o estés buscando una configuración rápida para enviar correos electrónicos, este repositorio te ayudará a comenzar.

## Características

- **Spring Boot 3:** Utiliza la última versión de Spring Boot para construir aplicaciones web robustas.
- **Envío de Correos Electrónicos:** Implementa la funcionalidad de envío de correos electrónicos usando el soporte incorporado de Spring Boot para JavaMailSender.
- **Pruebas SMTP:** Configura y prueba la configuración del servidor SMTP directamente desde tu aplicación Spring Boot.

## Configuración

Sigue estos pasos para configurar y ejecutar el proyecto localmente:

1. **Clonar el Repositorio:**
   ```bash
   git clone <repository_url>
   cd EmailDev-SB3-Template-SMTPTest
   ```

2. **Configurar la Configuración SMTP:**
   Actualiza el archivo `application.yml` con los detalles de tu servidor SMTP:
   ```yaml
   spring:
     mail:
       host: smtp.example.com
       port: 587
       username: tu_usuario
       password: tu_contraseña
       protocol: smtp
       properties.mail.smtp:
         auth: true
         starttls.enable: true
   
3. **Ejecutar la Aplicación:**
   Ejecuta el siguiente comando para ejecutar la aplicación Spring Boot:
   ```bash
   ./mvnw spring-boot:run
   ```

4. **Probar la Configuración SMTP:**
   Visita `http://localhost:8080/test-smtp` en tu navegador web para probar la conectividad con el servidor SMTP.

## Uso

- **Envío de Correos Electrónicos:** Utiliza la interfaz JavaMailSender proporcionada para componer y enviar correos electrónicos programáticamente.
- **Personalización:** Personaliza las plantillas de correo electrónico y el contenido según los requisitos de tu aplicación.
- **Depuración:** Monitorea los registros de la aplicación en busca de errores o excepciones al enviar correos electrónicos.

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes alguna sugerencia, mejora o corrección de errores, no dudes en abrir un problema o enviar una solicitud de extracción.

## Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE).

## Recursos

- [Documentación de Spring Boot](https://docs.spring.io/spring-boot/docs/current/reference/html/)
- [Documentación de JavaMail API](https://javaee.github.io/javamail/)
- [Documentación de Thymeleaf](https://www.thymeleaf.org/documentation.html)

## Contacto

Si tienes alguna pregunta o necesitas ayuda adicional, no dudes en ponerte en contacto con el mantenimiento del proyecto:

[Arland Michelena](mailto:arlandmichelenav@gmail.com)   
