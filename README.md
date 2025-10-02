# 🛠️ Arka Config Server

**Arka Config Server** es el microservicio encargado de proveer configuración centralizada para todos los servicios de la plataforma **Arka**. Implementa **Spring Cloud Config Server** y se integra con el ecosistema de servicios vía **Eureka Service Discovery**.

---

## 🚀 Características principales

- 📁 **Configuración centralizada y versionada** desde un repositorio Git privado.
- 🔐 **Seguridad habilitada** con autenticación básica (`Basic Auth`) usando Spring Security.
- ☁️ **Registro automático en Eureka Server** como cliente.
- 🧭 Permite el **descubrimiento por parte de otros microservicios** si es necesario.
- 🧪 **Actuator habilitado** para monitoreo y endpoints de administración.
- 🔄 Soporte para recarga dinámica de configuración vía `/actuator/refresh`.
- 🌍 Separación de puertos para tráfico público y administración (si está configurado).

---

## 🧩 Tecnologías usadas

- Java 17
- Spring Boot 3.x
- Spring Cloud Config Server
- Spring Cloud Netflix Eureka Client
- Spring Security (Basic Auth)
- Spring Boot Actuator

---

## ⚙️ Configuración

### 🔐 Autenticación (Basic Auth)

El acceso al servidor está protegido. Se requiere autenticación básica para acceder a cualquier endpoint de configuración.

Microservicio aún en desarrollo

Version actual: v0.2.0
