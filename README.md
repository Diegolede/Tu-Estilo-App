<div align="center">
  <img src="src/Logo.png" alt="Tu Estilo App Logo" width="180" />
  <h1>Tu Estilo App</h1>
  <p>
    <strong>Tu app de ficheros para clientes de peluquería.</strong>
  </p>

  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/badge/Versión-1.0.0-blue?style=for-the-badge" alt="Version" />
    <img src="https://img.shields.io/badge/Hecho%20en-Argentina-74ACDF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iOTAwIiBoZWlnaHQ9IjYwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjYwMCIgZmlsbD0iIzc0YWNkZiIvPjxyZWN0IHk9IjIwMCIgd2lkdGg9IjkwMCIgaGVpZ2h0PSIyMDAiIGZpbGw9IiNmZmYiLz48L3N2Zz4=&logoColor=white" alt="Argentina" />
    <img src="https://img.shields.io/badge/Hecho%20con-Arch%20Linux-1793d1?style=for-the-badge&logo=archlinux&logoColor=white" alt="Arch Linux" />
    <img src="https://img.shields.io/badge/Editor-VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code" />
    <img src="https://img.shields.io/badge/IA-Gemini-8E75B2?style=for-the-badge&logo=googlebard&logoColor=white" alt="Gemini" />
  </p>
  <p>
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
    <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
    <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" alt="Electron" />
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
    <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  </p>
</div>

---

## Descripción 

**Tu Estilo App** es una aplicación de escritorio diseñada específicamente para peluquerías y salones de belleza que desean gestionar sus clientes de manera profesional y moderna. Ofrece un sistema completo de ficheros de clientes con programa de fidelización mediante puntos, permitiendo registrar servicios, acumular puntos por cada atención y canjear recompensas. Su interfaz minimalista y moderna garantiza una experiencia de usuario fluida, con búsqueda rápida, notificaciones de cumpleaños y persistencia de datos local mediante SQLite.

<br>
<div align="center">
  <img src="src/captura.gif" alt="Captura de pantalla de Tu Estilo App" width="1000" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
  <p><em>Vista general del dashboard de clientes</em></p>
</div>
<br>

## ✨ Funcionalidades

### Gestión de Clientes
*   **Registro Completo**: Creación de fichas de clientes con nombre, apellido, ID único, fecha de nacimiento, teléfono y correo electrónico.
*   **Búsqueda Inteligente**: Sistema de búsqueda en tiempo real por nombre o ID de cliente con resultados instantáneos.
*   **Historial de Visitas**: Registro automático de la última visita de cada cliente para seguimiento personalizado.
*   **Notificaciones de Cumpleaños**: Sistema de alertas que muestra los clientes que cumplen años el día actual.

### Sistema de Puntos de Lealtad
*   **Acumulación de Puntos**: Tabla de puntos por servicio (Corte: 100pts, Nutrición: 140pts, Células madres: 170pts, Tintura: 190pts, Mechitas: 320pts, Mechitas con gorro: 360pts).
*   **Gestión de Puntos**: Suma y resta de puntos desde el perfil de cada cliente con registro de transacciones.
*   **Sistema de Canjes**: Recompensas configuradas (Corte gratis: 1000pts, Nutrición gratis: 1600pts, Tintura gratis: 2500pts, Voucher $5.000: 600pts, Voucher $15.000: 2200pts).
*   **Historial de Transacciones**: Visualización completa del historial de puntos ganados y canjeados por cliente.

### Interfaz y Experiencia
*   **Dashboard Moderno**: Vista principal con últimos clientes atendidos, tabla de puntos por servicio y recompensas disponibles.
*   **Diseño Minimalista**: Interfaz limpia en blanco y negro con acentos de color, optimizada para uso diario en salones.
*   **Animaciones Fluidas**: Transiciones suaves y micro-interacciones que mejoran la experiencia de usuario.
*   **Persistencia Local**: Guardado automático de todos los datos en base de datos SQLite sin necesidad de conexión a internet.

---

## 🎯 Flujo de Trabajo

Optimiza la atención a tus clientes con este flujo simple:

| Acción | Descripción |
| :--- | :--- |
| **Búsqueda de Cliente** | Utiliza la barra de búsqueda para encontrar al cliente por nombre o ID |
| **Registro de Servicio** | Selecciona el servicio realizado y suma los puntos correspondientes |
| **Canje de Recompensas** | Cuando el cliente tenga puntos suficientes, canjea premios desde su perfil |
| **Nuevo Cliente** | Accede a "Agregar Cliente" desde el menú lateral para registrar nuevos clientes |
| **Cumpleaños** | Revisa el ícono de notificación para ver clientes que cumplen años hoy |

---

<div align="center">
  <p>Desarrollado por <strong>Diego Ledesma</strong></p>
  <p><em>Versión 1.0.0 - Enero 2026</em></p>
</div>
