# 🛠️ Config Server - Arka Platform

Este microservicio actúa como **servidor centralizado de configuración** para todos los microservicios de la plataforma **Arka**. Está construido con **Spring Cloud Config Server** y permite gestionar propiedades de configuración de forma remota, segura y versionada, utilizando un repositorio Git privado como fuente.

---

## 🚀 Características

- 🔗 Conecta con un **repositorio Git privado** para obtener la configuración.
- 🌀 Compatible con configuraciones centralizadas por entorno, servicio o perfil.
- 📡 Expone endpoints de monitoreo y administración con **Spring Boot Actuator**.
- 🔄 Soporte para recarga de configuración dinámica vía `/actuator/refresh`.
- 🔐 Separación de puertos para administración y acceso público.

Microservicio aún en desarrollo

Version actual: v0.1.0
