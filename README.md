# Proyecto
Proyecto Final – SENA: Code Craft

(Cambia el nombre si tu proyecto es diferente)

## Descripción del Proyecto

Code Craft es una plataforma web diseñada para facilitar la gestión y evaluación de proyectos de desarrollo. Permite a los usuarios registrar solicitudes, gestionar tareas, hacer seguimiento al progreso y generar reportes.

Este proyecto fue desarrollado como requisito del Programa de Análisis y Desarrollo de Software (ADS) del SENA.

## Tecnologías Utilizadas
Componente	Tecnología	Descripción
Frontend	React + Vite	Interfaz gráfica desplegada en Netlify
Backend	Node.js + Express	API REST desplegada en Render
Base de Datos	PostgreSQL	Almacenamiento en Railway
Control de versiones	GitHub	Repositorio del proyecto
Autenticación	JWT	Manejo de sesiones y permisos
Estilos	Tailwind / CSS / Bootstrap	Según el diseño del equipo
 Características del Sistema

✔ Registro e inicio de sesión con roles
✔ CRUD de usuarios/proyectos/tareas (adaptar según tu sistema)
✔ Gestión de estado desde el frontend
✔ Base de datos escalable en Railway
✔ API documentada en Swagger/Postman
✔ Seguridad con HTTPS y JWT

## Estructura del Proyecto
 Backend (Node.js / Express)
/backend
├── src
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── index.js
├── .env
└── package.json

Frontend (React + Vite)
/frontend
├── src
│   ├── assets/
│   ├── components/
│   ├── hooks/
│   ├── pages/
│   ├── services/
│   └── main.jsx
├── .env
└── package.json

## Despliegues
Servicio	URL
Frontend (Netlify)

 Backend (Render)	

 Base de Datos (Railway)	Conexión privada (.env)
 Variables de Entorno

Backend (.env)

PORT=5000
DATABASE_URL=postgresql://usuario:password@host:port/dbname
JWT_SECRET=tu_clave_secreta


Frontend (.env)

VITE_API_URL=
Instalación y Ejecución Local
Backend
cd backend
npm install
npm run dev

Frontend
cd frontend
npm install
npm run dev

Documentación de la API

Puedes probar los endpoints desde:

Postman / Swagger: (agrega URL si la tienes)


