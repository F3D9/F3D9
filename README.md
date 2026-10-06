<div align="center">

# Hola, soy Federico 👋

Mi objetivo es unirme a un equipo en el que pueda aprender y enriquecer mi carrera profesional, mejorando tanto mis habilidades técnicas como las blandas, y sumando valor.
Trabajo con **Node.js, TypeScript, React y PostgreSQL**, y estoy cursando el tercer año de **Ingeniería Informática en la UBA**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/federico-salgado/)
[![Portfolio](https://img.shields.io/badge/Portafolio-000000?style=for-the-badge&logo=github&logoColor=white)](https://f3d9.github.io/Portafolio)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:federico.salgado2109@gmail.com)

</div>

---

## Sobre mí

- 🎓 Cursando **Ingeniería Informática** en la UBA (2023 – presente)
- 🔧 Foco en **backend**: APIs REST, arquitectura modular, autenticación JWT, bases de datos relacionales
- ⚛️ En frontend trabajo con **React + Vite + TypeScript**
- 🤖 Experiencia integrando **IA generativa** (Google Gemini API) y uso de agentes de IA como Claude y Gemma 4
- 🚀 Proyectos en producción con **Docker, Render, Railway y GitHub Actions**
- ☁️ Certificación **AWS Certified Cloud Practitioner** en proceso
- 📍 Buenos Aires — disponible para modalidad presencial, híbrida o remota en CABA

### Formación

- **Ingeniería Informática** — Universidad de Buenos Aires (2023 – presente)
- **Java para Principiantes** — TodoCode Academy (Octubre 2026)
- **AWS Certified Cloud Practitioner** — en proceso

---

## Tech Stack

### Backend
![NodeJS](https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Bases de Datos
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)

### DevOps & Testing
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=fff)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)

### Lenguajes
![JavaScript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)

---

## Proyectos Destacados

### 🏋️ GymTracker — App de Seguimiento de Entrenamientos
Aplicación full-stack para armar rutinas de gimnasio y registrar entrenamientos.

- API REST en **NestJS + TypeScript** con más de 30 endpoints, organizada en módulos (autenticación, usuarios, ejercicios, rutinas, entrenamientos e historial por ejercicio)
- Modelado en **PostgreSQL + Prisma**: usuarios, ejercicios, rutinas y entrenamientos, con migraciones y un seed para cargar el catálogo de ejercicios
- Autenticación con **JWT en cookies httpOnly** (el token no queda expuesto al JavaScript del cliente), con CORS configurado para frontend y backend en dominios distintos; validación de entrada con **class-validator**
- Frontend en **React + TypeScript + Vite + React Router**, con precarga del peso y las repeticiones del último entrenamiento
- Deploy: backend en **Render**, frontend en **GitHub Pages** con deploy automático vía **GitHub Actions**; **Docker Compose** para PostgreSQL en desarrollo
### 🤖 Chatbot Web con IA — Node.js + Gemini
Backend completo para un chatbot con IA integrada.

- API REST con **Node.js, Express y TypeScript**: registro, inicio de sesión y autorización por roles
- Integración con **Google Gemini API**, con contexto multiturno (recuerda los mensajes anteriores de la conversación)
- Historial de chat persistente por usuario en **PostgreSQL (Neon)**
- **JWT, bcrypt y Zod**: autenticación, hash seguro de contraseñas y validación de los datos que recibe la API
- Tests unitarios y de integración con **Vitest y Supertest**
- Contenerizado con **Docker** y deployado en **Railway** con CI/CD en cada push
### 🏎️ Fierrero — Career Mode de Fórmula 1
Juego de gestión de carrera jugable en el navegador: manejás el recorrido de un piloto de F1, elegís equipo y tomás decisiones que definen tu historia temporada a temporada.

- Sistema de decisiones que impactan la carrera (fichajes, continuidad en el equipo, eventos de riesgo)
- Sistema de trofeos con animaciones, historial por temporada y dos modos de juego (Normal e Intenso)
- **React + TypeScript + Vite**, con foco en performance y experiencia mobile-first
- Deploy automático a **GitHub Pages** con **GitHub Actions** en cada push a `main`
