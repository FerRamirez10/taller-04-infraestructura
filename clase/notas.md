# 🗒️ Registro de Trabajo en Clase - Taller 4

## 📆 Fecha de la sesión
6/09/25

## 👥 Integrantes presentes
- Diego Ramírez – diegorate@unisabana.edu.co  
- Carlos Sánchez – carlossanlo@unisabana.edu.co  
- Mateo Vanegas – mateovaco@unisabana.edu.co

## 🧠 Actividades realizadas en clase

Durante la sesión se trabajó en el caso de **RedExpress (Plataforma de Logística)**:

- Se discutieron los **componentes principales de la infraestructura híbrida** (servidores regionales, nube, BD centralizada, dispositivos móviles).  
- Se identificaron riesgos y puntos críticos:  
  - Latencia en rastreo en tiempo real.  
  - Riesgo de **punto único de falla** en el API Gateway y la Base de Datos centralizada.  
  - Limitaciones en la escalabilidad horizontal por zonas geográficas.  
- Se tomó la decisión de modelar un **mapa lógico preliminar** usando draw.io, diferenciando capa de entrada (usuarios → balanceador → API Gateway) y capa de servicios (procesamiento de rutas, tracking, autenticación, notificaciones).  
- Se usó **draw.io** como herramienta principal (además de notas en papel durante la discusión).  
- Se alcanzó a desarrollar el **borrador del mapa de infraestructura** con los componentes y sus conexiones.

## 🧩 Boceto inicial del modelo

> Se elaboró un primer borrador en **draw.io** con:  
> - Usuarios (mensajero app móvil y cliente web).  
> - Balanceador de carga y API Gateway.  
> - Servicios principales (autenticación, procesamiento de rutas, tracking, notificaciones).  
> - Base de datos centralizada.  

## 🔁 Tareas definidas para complementar el taller

Anote las responsabilidades acordadas entre los miembros del equipo para completar la entrega final:

| Tarea asignada | Responsable | Fecha estimada |
|----------------|-------------|----------------|
| Modelado final en draw.io | Diego Ramírez | 10/08 |
| Redacción del informe     | Mateo Vanegas | 11/08 |
| Investigación y referencias | Carlos Sanchez | 12/08 |

---

_Este documento resume el trabajo colaborativo realizado durante la sesión del taller 4 en el curso AREM - Universidad de La Sabana._