# 🗒️ Registro de Trabajo en Clase - Taller X

## 📆 Fecha de la sesión
14/02/2026

## 👥 Integrantes presentes
- Jonatan David Vergara Suárez
- Carlos David Bello Ortiz
- Jhojan Camilo Jiménez Amaya

## 🧠 Actividades realizadas en clase

Describa brevemente qué se hizo durante la sesión:

Durante la clase se discutio la relación que tendrian las clases y cuales estarian relacionadas entre si respectivamente.

Inicialmente se definió que la entidad Paciente se relaciona con Cita de 0 o muchos. Posteriormente se definió que la entidad Factura tenía una relación de 1 a 1 con Cita. Finalmente concluimos que Cita tiene un médico y médico tiene una o varias especialidades, y especialidades tiene una o varios médicos, y que una cita tiene una especialidad pero una especialidad tiene varias citas.

Se modeló y se presentó, recibiendo una corrección referente al triángulo formado por la relación circular entre médico, cita y especialidad. Posteriormente se decidió separar médico de cita, y asociar solamente cita con especialidad, pero se mantenía la relación de muchos a muchos entre médico y especialidad.

Para ello se definió la entidad débil Médico-Especialidad, la cual contenía información de los médicos y sus especialidades con una relación de Médicos con Médicos-Especialidades de una o muchos y de Especialidades con Médicos-Especialidades de uno o muchos.

Posteriormente se evaluó la relevancia en la cita de qué información debería conocerse primero. Por lo tanto se sustituyó la relación Citas con Especialidades y se estableció Citas-Médicos de una cita con un médico y un médico con una o muchas citas.

## 🧩 Boceto inicial del modelo

<img alt="ERD drawio" src="https://github.com/user-attachments/assets/d46c1fb6-cc6b-44a5-abc3-09bdb20a688d" />

## 🔁 Tareas definidas para complementar el taller

Anote las responsabilidades acordadas entre los miembros del equipo para completar la entrega final:

| Tarea asignada | Responsable | Fecha estimada |
|----------------|-------------|----------------|
| Modelado final en draw.io | Jonatan | 14/02 |
| Redacción del informe     | Carlos | 19/02 |
| Investigación y referencias | Jhojan | 18/02 |

---

_Este documento resume el trabajo colaborativo realizado durante la sesión del taller X en el curso AREM - Universidad de La Sabana._