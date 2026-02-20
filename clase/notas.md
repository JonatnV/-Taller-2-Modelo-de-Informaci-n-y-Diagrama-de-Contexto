🗒️ Registro de Trabajo en Clase - Taller 2
📆 Fecha de la sesión
14/02/2026

👥 Integrantes presentes
Jonatan David Vergara Suarez
Carlos David Bello Ortiz
Jhojan Camilo Jiménez Amaya

🧠 Actividades realizadas en clase
Describa brevemente qué se hizo durante la sesión:
Durante la clase se discutio la relación que tendrian las clases y cuales estarian relacionadas entre si respectivamente

Inicialmente se defino que la entidad Paciente se relaciona con Cita de 0 o muchos, posteriormente se definio que la entidad
Factura tenia una relacion de 1 a 1 con Cita, finalmente concluimos que Cita tiene un medico y medico tiene una o varias especialidades y especialidades
tiene una o varios medicos, y que una cita tiene una especialidad pero una especialidad tiene varas citas.
Se modelo y se presento, recibiendo una correción referente al triangulo formado por la relacion circular entre medico, cita y especialidad,
posteriormente se decidio separar medico de cita, y asociar solamente cita con especialidad, pero se mantenia la relacion de muchos a muchos entre medico y especialidad
para ello se definio  la entidad debil Medico-Especialidad la cual contenia información de los medicos y sus especialidades con una relacion de Medicos con Medicos-Especialidades
de una o muchos y de Especialidades con Medicos-Especiales de uno o Muchos, posteriormente se evaluo la relevancia en la cita 
de que información deberia conocerse primero, por lo tanto se sustituyo la relacion Citas con Especialidades y se establecio con Citas Medicos de  una cita con un medico
y un medico con una o muchas citas
🧩 Boceto inicial del modelo
(Puede insertar aquí una imagen del boceto, una captura de pantalla o un diagrama preliminar si ya fue hecho en digital)
<img width="1191" height="831" alt="ERD drawio" src="https://github.com/user-attachments/assets/d46c1fb6-cc6b-44a5-abc3-09bdb20a688d" />
🔁 Tareas definidas para complementar el taller

Anote las responsabilidades acordadas entre los miembros del equipo para completar la entrega final:

Tarea asignada	Responsable	Fecha estimada
Modelado final en draw.io	Jonatan 	14/02
Redacción del informe	Carlos 	11/08
Investigación y referencias	Jhojan	18/02
Este documento resume el trabajo colaborativo realizado durante la sesión del taller X en el curso AREM - Universidad de La Sabana.
