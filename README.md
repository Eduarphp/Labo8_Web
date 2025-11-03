# Laboratorio VIII - Programación Web  
Universidad Centroamericana José Simeón Cañas  
Estudiante: Cesar Eduardo Navarrete Chavarria 
Carnet: 00007023  
Sección: 2 

Este proyecto implementa una aplicación **Full Stack (React + Express + PostgreSQL) con autenticación JWT.

El backend permite:
- Registrar usuarios
- Iniciar sesión con JWT
- Consultar la lista de usuarios autenticados

El frontend (React) se conecta mediante fetch() a los endpoints del backend.

## Tecnologías
- Node.js / Express  
- PostgreSQL  
- React + Vite  
- JWT + bcrypt  
- Thunder Client (para pruebas)

# Ejecución
1. Iniciar backend:
   
  cd Server-BE
  node index.js

2. Iniciar Frontend:
   cd Cliente-FE
   npm run dev

3. Abrir el navegador en:
  http://localhost:5173
