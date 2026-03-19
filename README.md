# Springboot-OpenFeign
Este proyecto implementa una arquitectura de microservicios utilizando Spring Boot y Spring Cloud OpenFeign para la comunicación síncrona entre el servicio de Reservas (Port 8082) y el servicio de Canchas (Port 8081).

1. Configuración de Dependencias (pom.xml)
Se añadió el manejador de versiones de Spring Cloud y el starter de OpenFeign:
    org.springframework.cloud
    spring-cloud-starter-openfeign

En la clase principal (o de configuración) del Servicio de Reservas, se habilitó la detección de clientes Feign:

@EnableFeignClients // Habilita la infraestructura de OpenFeign

