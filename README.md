# 🛠️ Arka Config Server

**Arka Config Server** es el microservicio encargado de proveer configuración centralizada para todos los servicios de la plataforma **Arka**. Implementa **Spring Cloud Config Server**

---

## 🚀 Características principales

- 📁 **Configuración centralizada y versionada** desde un repositorio Git privado.
- 🔐 **Seguridad habilitada** con autenticación básica (`Basic Auth`) usando Spring Security.
- 🧪 **Actuator habilitado** para monitoreo y endpoints de administración.
- 🌍 Separación de puertos para tráfico público y administración (si está configurado).

---

## 🧩 Tecnologías usadas

- Java 17
- Spring Boot 3.x
- Spring Cloud Config Server
- Spring Security (Basic Auth)
- Spring Boot Actuator

---

## ⚙️ Configuración

### 🔐 Autenticación (Basic Auth)

El acceso al servidor está protegido. Se requiere autenticación básica para acceder a cualquier endpoint de configuración.

Version actual: v1.0.0
