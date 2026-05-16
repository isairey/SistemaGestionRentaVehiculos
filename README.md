<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/744/744465.png" />

# 🚗 Car Rental Management System

### Sistema de gestión y administración de renta de vehículos 🚀

<p align="center">
  <b>Car Rental Management System</b> es una aplicación desarrollada en JavaFX orientada a la administración de alquiler de automóviles, permitiendo gestionar clientes, vehículos, reservas y operaciones administrativas desde una interfaz moderna y dinámica.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CarRental-ManagementSystem-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/JavaFX-DesktopApp-orange?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-Academic-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Car Rental Management System** es un sistema de escritorio desarrollado con JavaFX para administrar procesos de renta de vehículos de manera eficiente y automatizada.

La plataforma fue diseñada para:

- 🚗 Gestionar vehículos
- 👥 Administrar clientes
- 📅 Controlar reservas
- 💳 Gestionar pagos
- 📊 Supervisar operaciones
- 🔐 Gestionar accesos
- 🧾 Administrar contratos
- ⚡ Optimizar procesos de renta

---

# ✨ Características

## 🚘 Gestión de vehículos

- 🚗 Registro de automóviles
- 📋 Información detallada
- ⚙️ Gestión de disponibilidad
- 🛠️ Control de mantenimiento
- 🖼️ Gestión de imágenes

---

## 👥 Gestión de clientes

- 👤 Registro de clientes
- 🔐 Inicio de sesión
- 📄 Gestión de perfiles
- 📊 Historial de alquileres
- ⚡ Administración centralizada

---

## 📅 Sistema de reservas

- 📆 Reservación de vehículos
- ⏱️ Gestión de fechas
- 💳 Administración de pagos
- 📋 Contratos de alquiler
- ⚡ Confirmaciones rápidas

---

## 📊 Panel administrativo

- 📈 Dashboard administrativo
- 🚘 Gestión de automóviles
- 👥 Administración de clientes
- 📅 Supervisión de reservas
- 🔐 Gestión de permisos

---

# 👨‍💼 Módulos del sistema

## 🚘 Vehicle Module

Este módulo administra todos los vehículos registrados dentro del sistema.

### Funcionalidades:

- ➕ Registro de vehículos
- 📋 Gestión de información
- ⚙️ Administración de disponibilidad
- 🛠️ Control de mantenimiento
- 🖼️ Gestión multimedia

---

## 👤 Customer Module

Este módulo es utilizado por clientes que desean rentar vehículos.

### Funcionalidades:

- 🔐 Inicio de sesión
- 🚗 Reservar automóviles
- 📅 Consultar reservas
- 💳 Gestión de pagos
- 📄 Historial de alquileres

---

## 🛠️ Admin Module

Este módulo funciona como administrador principal del sistema.

### Funcionalidades:

- 👥 Gestión de clientes
- 🚘 Supervisar vehículos
- 📊 Dashboard del sistema
- 📅 Administración de reservas
- 🔐 Gestión administrativa

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend / UI

<p>
  <img src="https://skillicons.dev/icons?i=java" />
</p>

- JavaFX
- CSS para JavaFX
- Interfaces dinámicas
- Diseño de escritorio moderno

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=java" />
</p>

- Java
- Programación orientada a objetos
- Arquitectura MVC
- Gestión de sesiones

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Relaciones SQL
- Persistencia de datos
- Gestión de alquileres

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,idea" />
</p>

- Git
- GitHub
- IntelliJ IDEA
- Visual Studio Code
- Scene Builder

---

# 📂 Estructura del proyecto

```bash
SistemaGestionRentaVehiculos/
│
├── src/                      # Código fuente Java
├── controllers/              # Controladores JavaFX
├── models/                   # Modelos del sistema
├── views/                    # Interfaces FXML
├── assets/                   # Recursos multimedia
├── database/                 # Scripts SQL
├── styles/                   # Archivos CSS
├── Main.java                 # Punto de entrada
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- Java JDK 8+
- JavaFX SDK
- MySQL
- IntelliJ IDEA / NetBeans
- Scene Builder

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/SistemaGestionRentaVehiculos.git
```

---

## 2️⃣ Configurar JavaFX

Agregar librerías JavaFX al proyecto:

```bash
javafx-sdk/lib
```

---

## 3️⃣ Crear base de datos

Crear base:

```bash
car_rental_management
```

---

## 4️⃣ Importar SQL

Importar:

```bash
database/car_rental_management.sql
```

---

## 5️⃣ Configurar conexión

Editar archivo:

```bash
DatabaseConnection.java
```

Agregar:

```java
String url = "jdbc:mysql://localhost:3306/car_rental_management";
String user = "root";
String password = "";
```

---

## 6️⃣ Ejecutar proyecto

Iniciar aplicación desde:

```bash
Main.java
```

---

# 📊 Funcionalidades principales

## 🚘 Gestión de vehículos

- Registro de automóviles
- Administración de disponibilidad
- Gestión de mantenimiento
- Información detallada

---

## 👥 Administración de clientes

- Registro y autenticación
- Gestión de perfiles
- Historial de alquileres
- Roles administrativos

---

## 📅 Gestión de reservas

- Reservas en tiempo real
- Contratos de alquiler
- Gestión de pagos
- Confirmaciones automáticas

---



# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo de aplicaciones JavaFX
- Arquitectura MVC
- Bases de datos relacionales
- Gestión de vehículos
- CRUD administrativos
- Sistemas de autenticación
- Automatización de alquileres

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- ☁️ Integración cloud
- 📱 Aplicación móvil
- 💳 Pasarela de pagos
- 📍 Geolocalización GPS
- 🤖 Recomendaciones inteligentes
- 🌐 API REST moderna
- 🔔 Notificaciones en tiempo real

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por aplicaciones Java, sistemas administrativos y plataformas inteligentes 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source bajo licencia MIT orientado al aprendizaje y administración de sistemas de renta de vehículos.

---

<div align="center">

### 🚗 Car Rental Management System — administración inteligente de alquiler de vehículos 🚀

</div>
