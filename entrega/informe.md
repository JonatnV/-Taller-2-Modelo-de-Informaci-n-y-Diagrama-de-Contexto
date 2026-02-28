# 📄 Informe Técnico del Taller

## 🔖 Nombre del Taller
_Taller 2 - Modelo de Información y Diagrama de Contexto_

## 👥 Integrantes del equipo
- Jonatan David Vergara Suárez (github.com/JonatnV)
- Carlos David Bello Ortiz
- Jhojan Camilo Jiménez Amaya

## 🧠 Descripción general del trabajo
El objetivo era en base a la información del funcionamiento de la empresa y la operación que se esta trabajando, realizar el modelado y diagrama de entiedad-relación, esto se hizo usando el BPMN realizado anteriormente junto a la información que nos fue provista.

## 🔧 Proceso de desarrollo
Se tomo del proceso, las entidades que identificamos que participan en el proceso las cuales fueron, Cotizaciones, Clientes, Ventas, Despachos y Facturas,
posteriormente en el modelado se fue trazando las relaciones en el diagrama entidad y relación y se encontro una relación de muchos a muchos entre Cotizaciónes y productos, debido a la naturaleza de estas, por ello se definio la entidad Detalles_Cotizaciones, para tener todos los productos que hacen parte de una cotización junto su cantidad y otros detalles necesarios. Posteriormente se uso de base el BPMN y el ERD, para realizar el modelo entidad relación, con el cual se valido efectivamente las relaciones entre las entidades identificadas, quedando como se ve en el modelo y diagrama final

## 🧩 Análisis del modelo propuesto
El modelo entregado son dos, uno corresponde al diagrama y otro al modelo entidad relación, los cuales muestran la información que requiere el proceso de la cotización, junto a un par de supuestos como lo son parcialmente las estrucutras de los datos de cada entidad debido a que puede estar de una forma similar o diferente o algunos datos contenidos por separado, pero funcionalmente se identifico de esta forma.

## 📈 Diagrama final entregado

![WhatsApp Image 2026-02-27 at 8 32 53 PM](https://github.com/user-attachments/assets/798d680a-508c-4de3-a381-711a169a9f53)

![WhatsApp Image 2026-02-27 at 9 28 12 PM](https://github.com/user-attachments/assets/78a2646f-a6fd-409a-b3ff-003dc2f7f91b)


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
