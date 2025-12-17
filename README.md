
# Eureka Server

Proyecto **Spring Boot** que implementa un **Eureka Server** utilizando **Spring Cloud Netflix Eureka**, para la gestión y descubrimiento de servicios en una arquitectura de microservicios.

---

## 📌 Características

- Registro de microservicios con **Eureka Server**
- Soporte para múltiples clientes Eureka
- Integración con **Spring Boot 3.4.3**
- Recarga automática en desarrollo con **Spring Boot DevTools**
- Pruebas unitarias con **Spring Boot Test**

---

## 🛠️ Tecnologías Utilizadas

- **Java:** 21  
- **Spring Boot:** 3.4.3  
- **Spring Cloud:** 2024.0.0  
- **Spring Cloud Netflix Eureka**
- **Maven**

---

## 📋 Requisitos Previos

- Java JDK 21
- Maven 3.9+
- IDE recomendado: IntelliJ IDEA, Eclipse, Spring Tool Suite

---

## ⚙️ Configuración del Eureka Server

En `application.properties` o `application.yml`, configura el puerto y otras propiedades:

```properties
server.port=8761
eureka.client.register-with-eureka=false
eureka.client.fetch-registry=false
eureka.instance.hostname=localhost
````

---

## ▶️ Ejecución del Proyecto

Desde la raíz del proyecto:

```bash
mvn spring-boot:run
```

O empaquetar y ejecutar:

```bash
mvn clean package
java -jar target/eureka-server-0.0.1-SNAPSHOT.jar
```

El Eureka Server estará disponible en:

```
http://localhost:8761
```

---

## 📁 Estructura del Proyecto

```
src
 └── main
     ├── java
     │   └── com.eureka-server
     └── resources
         └── application.properties
```

---

## 🧪 Ejecución de Pruebas

```bash
mvn test
```

---

## 🚀 Objetivo del Proyecto

* Aprender a implementar **Eureka Server**
* Gestionar el registro y descubrimiento de microservicios
* Integrar Eureka con clientes Spring Boot

---

## 📄 Licencia

Proyecto con fines educativos y de aprendizaje.
Uso libre para prácticas personales.

---

## ✍️ Autor

Proyecto desarrollado como práctica de **Spring Boot & Eureka Server**.

