# RBAC Auth Backend

Backend de un sistema de autenticación y autorización basado en JWT, desarrollado con NestJS y PostgreSQL.

La API proporciona una estructura escalable y reutilizable para aplicaciones SaaS, dashboards administrativos y sistemas multiusuario con control avanzado de roles y permisos.

---

## ✨ Características Principales

### 🔐 Autenticación y Seguridad
- JWT Authentication
- Protección de rutas
- Guards personalizados
- Middleware de autenticación
- Validación segura de tokens

### 👥 Gestión de Usuarios
- CRUD de usuarios
- Administración centralizada
- Gestión multiusuario

### 🛡️ Sistema RBAC
- Roles dinámicos
- Permisos configurables
- Control granular de accesos
- Arquitectura desacoplada

### 🏢 Arquitectura Multi-tenant
- SuperAdmin global
- Administración por entidad
- Escalable para SaaS

### ⚙️ Arquitectura Escalable
- Módulos desacoplados
- API REST
- Servicios reutilizables
- Preparado para futuras integraciones

---

## 🖼️ Funcionalidades de la API

- Authentication
- User Management
- Role Management
- Permission Management
- Protected Routes
- RBAC Authorization

---

## 🛠️ Stack Tecnológico

- NestJS
- Node.js
- TypeScript
- PostgreSQL
- TypeORM
- JWT
- Passport.js
- RBAC

---

## 🚀 Instalación

### Clonar el repositorio

```bash
git clone https://github.com/yourusername/rbac-auth-backend.git
```

### Instalar dependencias

```bash
npm install
```

---

## ⚙️ Variables de entorno

Crear un archivo `.env`:

```env
PORT=3000

DATABASE_HOST=localhost
DATABASE_PORT=5432
DATABASE_USER=postgres
DATABASE_PASSWORD=password
DATABASE_NAME=rbac_db

JWT_SECRET=your_jwt_secret
```

---

## ▶️ Ejecutar el proyecto

```bash
npm run start:dev
```

---

## 🧠 Arquitectura Backend

El backend fue diseñado bajo una arquitectura modular utilizando NestJS:

- Guards personalizados
- Sistema RBAC desacoplado
- Middleware reutilizable
- Organización por módulos
- API REST escalable
- Integración sencilla con frontend

---

## 📌 Casos de Uso

- Sistemas SaaS
- APIs administrativas
- Plataformas multiusuario
- Dashboards empresariales
- Sistemas con control de accesos

---

## 📌 Funcionalidades Futuras

- OAuth
- Two-Factor Authentication (2FA)
- Logs de actividad
- Auditoría de accesos
- Rate limiting avanzado
- WebSockets

---

## 👨‍💻 Autor

Desarrollado por Mauricio Lores

---

## 📄 Licencia

Este proyecto está licenciado bajo la licencia MIT.