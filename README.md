# 🚀 WebApp Headers - Jakarta EE

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Jakarta EE](https://img.shields.io/badge/Jakarta_EE-2C2255?style=for-the-badge&logo=jakartaee&logoColor=white)
![Maven](https://img.shields.io/badge/Apache_Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)

Este es un proyecto educativo desarrollado con **Jakarta EE (Servlets)** que demuestra el manejo de cabeceras HTTP, gestión de sesiones y control de productos.

---

## 🛠️ Funcionalidades Principales

* **Gestión de Cabeceras:** Análisis detallado de los `headers` enviados por el cliente.
* **Búsqueda Dinámica:** Localización de productos mediante filtros.
* **Seguridad:** Implementación de un sistema de Login con manejo de sesiones HTTP.
* **Exportación de Datos:** Capacidad para generar salidas en formato JSON y XLS.
* **Redireccionamiento:** Uso de `RequestDispatcher` y `sendRedirect` para control de flujo.

## 🏗️ Arquitectura
El proyecto utiliza el patrón **MVC (Modelo-Vista-Controlador)**:
- **Modelos:** POJOs para representar la lógica de datos (`Producto.java`).
- **Controladores:** Servlets especializados para cada tarea.
- **Servicios:** Abstracción de la lógica de negocio.

## 🚀 Cómo ejecutarlo

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/TU_USUARIO/webapp-headers.git](https://github.com/TU_USUARIO/webapp-headers.git)
