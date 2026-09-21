# Unixam

Plataforma de estudio pensada para estudiantes de universidad y PAU: un espacio donde compartir apuntes y exámenes para estudiar de forma más eficiente.

> ⚠️ Este repositorio es un **showcase** del proyecto. El código fuente es privado (producto comercial en fase de lanzamiento) — aquí explico qué hace, cómo está construido y cuál fue mi rol.

🔗 **Web:** (https://unixam-mauve.vercel.app/)

## Qué es

Unixam nace como alternativa a plataformas como Wuolah, centrada en estudiantes de universidad y PAU. Permite subir, buscar y compartir apuntes y exámenes de forma organizada por asignatura y centro.

## Capturas
Página principal: 
<img width="3413" height="1270" alt="image" src="https://github.com/user-attachments/assets/934da001-fd08-444e-8221-e6fd50469348" />
Perfil:
<img width="3404" height="1226" alt="image" src="https://github.com/user-attachments/assets/37a59a4a-658f-4984-9e6e-6d42dc1ee183" />
Buscador:
<img width="3414" height="1241" alt="image" src="https://github.com/user-attachments/assets/fd66ba28-c457-4766-a796-acd8d0619827" />
Mochila:
<img width="3395" height="1296" alt="image" src="https://github.com/user-attachments/assets/1be6cf83-5a0a-4c4b-8836-dfbbecf6606f" />



## Stack técnico

- **Frontend:** React, Vite, Tailwind CSS
- **Backend / datos:** Supabase (PostgreSQL) — esquema de 13 tablas
- **IA (en desarrollo):** generador de exámenes a partir de PDFs y chat sobre documentos (RAG) vía pgvector + Supabase Edge Functions
- **Despliegue:** Vercel

## Funcionalidades

- Registro y autenticación de usuarios
- Landing page con tema claro/oscuro
- Subida y búsqueda de apuntes/exámenes
- Roadmap: funciones Pro con IA (generación de exámenes, chat con documentos)

## Mi rol

Co-fundador y desarrollador — responsable del frontend (React/Vite, sistema de autenticación, landing page) y del diseño del esquema de base de datos en Supabase, trabajando en equipo con el resto de fundadores.

## Estado

Producto en fase final de lanzamiento: integración de pagos (Stripe) y carga de contenido inicial. Candidato al XXIV Certamen Innova-Emprende de la UMH (septiembre 2026).
