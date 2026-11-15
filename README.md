# 🚀 Ejercicio Facturación API - Spring Boot

API REST desarrollada en **Spring Boot** aplicando arquitectura limpia por capas (Controller, Service, DTO) para el cálculo de facturación e impuestos (IVA 13% - Costa Rica).

## 🏛️ Arquitectura del Proyecto

El proyecto está estructurado separando responsabilidades de manera lógica:

* **`controller/` (El Mesero):** Recibe las solicitudes HTTP del cliente mediante endpoints REST (`@RestController`, `@PostMapping`).
* **`service/` (El Chef):** Contiene la lógica de negocio pura y los cálculos matemáticos (cálculo del IVA del 13%).
* **`dto/` (El Plato):** Objetos de transferencia de datos (`Data Transfer Object`) para estructurar los JSON de entrada y salida de forma limpia y segura.

---

## 🛠️ Tecnologías Utilizadas

* **Java** 
* **Spring Boot** (Web, Tomcat embebido)
* **Maven** (Gestión de dependencias)
* **REST Client / Postman** (Pruebas de endpoints)

---

## ⚙️ Cómo Ejecutar el Proyecto

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/TU_USUARIO/ejercicio-facturacion-api.git](https://github.com/TU_USUARIO/ejercicio-facturacion-api.git)
