# 🛒 Sistema Monolítico de Supermercado

## 📋 Descripción
Este proyecto es un **sistema monolítico** diseñado para la gestión integral de un supermercado.  
Permite administrar **productos, clientes, pedidos, inventario y ventas** desde una sola aplicación centralizada.  
Su arquitectura monolítica facilita el despliegue y mantenimiento, integrando todos los módulos en un único paquete.

---

## ⚙️ Tecnologías utilizadas
- **Lenguaje backend:** Java con Spring Boot
- **Base de datos:** MySQL
- **Frontend:** Thymeleaf + Bootstrap
- **Gestión de dependencias:** Maven
- **Control de versiones:** Git + GitHub

---

## 📂 Estructura del proyecto
/src
/main
/java
/com/miempresa/supermercado
├── controllers/ # Controladores web
├── services/ # Lógica de negocio
├── repositories/ # Acceso a datos
└── models/ # Entidades y modelos
/resources
├── application.properties
├── static/ # Archivos estáticos (CSS, JS, imágenes)
└── templates/ # Vistas Thymeleaf

---

## 🚀 Instalación y ejecución

### 1️⃣ Clonar el repositorio
git clone https://github.com/usuario/supermercado-monolito.git
## 2️⃣ Entrar en el directorio del proyecto
cd supermercado-monolito
3️⃣ Configurar la base de datos
Editar el archivo src/main/resources/application.properties con tus credenciales:
spring.datasource.url=jdbc:mysql://localhost:3306/supermercado
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña
spring.jpa.hibernate.ddl-auto=update

4️⃣ Ejecutar la aplicación
mvn spring-boot:run

5️⃣ Acceder a la aplicación
http://localhost:8080

📌 Funcionalidades principales

🛍 Gestión de productos: crear, editar, eliminar y listar.

👥 Gestión de clientes: registro y administración.

📦 Gestión de inventario: control de stock.

🧾 Gestión de pedidos y ventas: registro y seguimiento.

📊 Reportes básicos: resumen de ventas e inventario

💻 Desarrollado por Diego Aguilar


