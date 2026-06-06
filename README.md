<div align="center">
  <h1>🏋️ Gym Leader Platform</h1>
  <p><em>Sistema Administrativo Ligero para Gimnasios y Centros de Fitness</em></p>

  [![Status](https://img.shields.io/badge/Status-Activo-success.svg)]()
  [![PHP](https://img.shields.io/badge/PHP-7.4+-blue.svg)]()
  [![MySQL](https://img.shields.io/badge/MySQL-8.0-orange.svg)]()
  [![License](https://img.shields.io/badge/License-Proprietary-red.svg)]()
</div>

---

## 🎯 El Problema

Los gimnasios pequeños y medianos en Latinoamérica suelen operar con hojas de cálculo y anotaciones manuales para llevar el control de membresías, pagos y asistencia. Esto genera errores, pérdida de datos y una pésima experiencia tanto para el administrador como para el cliente.

**Gym Leader** nació para resolver exactamente eso: un sistema completo, sin dependencias externas, desplegable en cualquier servidor con XAMPP/Laragon, y que cualquier persona pueda aprender a usar en minutos.

---

## ✨ Módulos del Sistema

| Módulo | Descripción |
|---|---|
| 👤 **Gestión de Clientes** | Alta, baja y edición de socios con historial completo |
| 💳 **Control de Membresías** | Tipos de plan, fechas de vencimiento y alertas de renovación |
| 📆 **Registro de Asistencia** | Check-in/check-out diario con historial por socio |
| 💰 **Panel de Pagos** | Registro de cobros, métodos de pago y estados de cuenta |
| 👑 **Administrador** | Panel protegido para la gestión de usuarios del sistema |
| 📊 **Reportes** | Listado de socios activos, vencidos y estadísticas de asistencia |

---

## 🛠️ Stack Tecnológico

**Por qué PHP nativo?** Velocidad de despliegue. No hay build steps, no hay dependencias de Node.js, no hay tiempo de compilación. Copiás los archivos, importás la base de datos y funciona. Perfecto para entornos con recursos limitados.

| Capa | Tecnología |
|---|---|
| **Lenguaje** | PHP 7.4+ (Nativo, sin frameworks) |
| **Frontend** | HTML5 + CSS3 Vanilla (Responsive) |
| **Base de Datos** | MySQL / MariaDB |
| **Servidor** | Apache (XAMPP / Laragon / cPanel) |

---

## 🚀 Instalación Rápida

```bash
# 1. Clonar o descargar el proyecto en la carpeta de tu servidor
#    Ejemplo con XAMPP: C:\xampp\htdocs\gym-leader\

# 2. Importar la base de datos
#    Abrir phpMyAdmin → Crear DB 'gym_db' → Importar 'database.sql'

# 3. Configurar conexión (si las credenciales son distintas a las por defecto)
#    Editar: config/db.php
```

---

## 🔐 Acceso Demo

| Rol | Usuario | Contraseña |
|---|---|---|
| **Administrador** | `admin@gymleader.com` | `123456` |
| **Cliente** | Registro libre desde el formulario | — |

---

> Desarrollado por **Gustavo Matheus** · *Full Stack Developer*
