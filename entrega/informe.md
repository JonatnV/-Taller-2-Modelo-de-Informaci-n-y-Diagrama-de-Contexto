# 📄 Informe Técnico del Taller

## 🔖 Nombre del Taller
_Taller 2 - Modelo de Información y Diagrama de Contexto_

## 👥 Integrantes del equipo
- Jonatan David Vergara Suárez (github.com/JonatnV)
- Carlos David Bello Ortiz
- Jhojan Camilo Jiménez Amaya

## 🧠 Descripción general del trabajo
Describa brevemente el objetivo del taller y cómo se desarrolló la actividad.

## 🔧 Proceso de desarrollo
Explique cómo realizaron el trabajo: qué decisiones tomaron, qué herramientas utilizaron, qué aspectos modelaron primero y cómo lo fueron ajustando.

## 🧩 Análisis del modelo propuesto
Incluya un análisis sobre:
- Cómo se estructura el modelo entregado
- Cómo representa las necesidades del cliente
- Qué supuestos se tomaron

## 📈 Diagrama final entregado
> (Inserte aquí una imagen o enlace al modelo-final.drawio / .asta / PDF)

## 📋 Tabla de actores, entidades o componentes (si aplica)

| Nombre del elemento | Tipo | Descripción | Responsable |
|---------------------|------|-------------|-------------|
| Ej: Paciente        | Actor | Usuario que agenda una cita médica | Cliente |

## 🔍 Investigación complementaria
### Tema investigado:
ERD y contexto en casos reales de la industria.

### Resumen:

Los diagramas entidad-relación (ERD) son fundamentales en la ingeniería de software como modelo conceptual para bases de datos relacionales.

#### - Beneficios en Industria
Mejoran la claridad del modelo de datos, facilitan la comunicación entre equipos y detectan problemas como redundancia o fallos de normalización antes de la implementación, reduciendo costos y tiempos. En proyectos backend, se recomienda iniciar con un ERD definido para análisis y diseño.

#### - Casos en Banca
En sistemas bancarios, los ERD modelan entidades como Customer, Account, Transaction, Loan y Branch, con relaciones uno-a-muchos (ej. cliente a cuentas, cuentas a transacciones). Esto asegura trazabilidad, consistencia regulatoria y eficiencia en operaciones como préstamos o transacciones.

#### - Casos en E-commerce
Para plataformas de comercio electrónico, se usan entidades como Product, User, Order, Payment, Cart y Shipment, enfocadas en escalabilidad y consultas críticas como tracking de envíos. Estos modelos se convierten en scripts SQL para SGBD como MySQL, generando claves foráneas automáticamente.

#### - Relación con Taller
Derivar entidades de eventos de negocio (event-driven) en talleres reproduce prácticas industriales, integrando ERD con DFD o BPMN para soportar procesos escalables y mantenibles.

## 📚 Referencias
- [1] Ali, Aijaz. Why Entity‑Relationship Diagrams (ERDs) are important for software development? 2023. https://www.hyper-leap.com/2023/10/09/why-entity-relationship-diagrams-erds-are-important-for-software-development/
- [2] Institute of Data. Understanding Entity‑Relationship Diagram – ERD in Software Engineering. 2024. https://www.institutedata.com/blog/erd-in-software-engineering/ [geeksforgeeks](https://www.geeksforgeeks.org/dbms/er-diagram-of-bank-management-system/)
- [3] Creately. ER Diagram for Banking System – Design Guide. 2025. https://creately.com/guides/er-diagram-for-banking-system/ [linkedin](https://www.linkedin.com/pulse/day-5-how-formulate-er-diagram-banking-system-model-ijaz-khan-f7h4f)
- [4] GeeksforGeeks. How to Design ER Diagrams for E‑commerce Website. 2025. https://www.geeksforgeeks.org/dbms/how-to-design-er-diagrams-for-e-commerce-website/ [geeksforgeeks](https://www.geeksforgeeks.org/dbms/er-diagram-of-bank-management-system/)
- [5] Redgate. Ecommerce Database Design: ER Diagram for Online Shop. 2026. https://www.red-gate.com/blog/er-diagram-for-online-shop/
- [6] Nugroho, H., et al. Strukturisasi Entity Relationship Diagram dan Data Flow Diagram Berbasis Business Event‑Driven. 2014. https://journal.binus.ac.id/index.php/comtech/article/download/2577/1983

---

_Este documento hace parte de la entrega del taller X del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._