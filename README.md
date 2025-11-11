🧩 Proyecto Formativo – Ingeniería de Software I
📌 Información General
Nombre del Proyecto:
OrderUp
Equipo de Desarrollo:
ing Juan David Villarreal y ing Frank Josswar Vente

Programa: Ingeniería de Software I
Institución: UNAD – Instituto Técnico Profesional
Grupo: S441B-2
Versión del Documento: v2 (Sesión 11)
Fecha de actualización:  28/10/2025

🎯 1. Descripción General del Proyecto
El proyecto busca desarrollar un sistema de gestión de pedidos que permita a los restaurantes registrar y controlar los pedidos de sus clientes de manera eficiente, automatizando el proceso de toma de pedidos, cálculo de totales y generación de recibos de caja, promoviendo una experiencia más ágil e intuitiva tanto para el personal como para la administración del negocio.

🧠 2. Contexto y Justificación
El sistema responde a la necesidad de modernizar la gestión de pedidos en restaurantes mediante herramientas digitales, reduciendo errores manuales en la toma de pedidos, agilizando el proceso de facturación y mejorando el control administrativo de las ventas diarias. Esto permite optimizar tiempos de atención al cliente y facilitar la generación de reportes para la toma de decisiones.


🧩 3. Requisitos del Sistema
3.1 Requisitos Funcionales
Código	Descripción	Estado
RF-01	 El sistema deberá permitir que los usuarios registren pedidos capturando datos del
cliente (nombre, teléfono, dirección), detalles del producto y método de pago de forma
estructurada.	🔄 En desarrollo

RF-02	El sistema deberá permitir que los empleados actualicen el estado del pedido
(recibido/en preparación/listo/entregado) en tiempo real para mayor control operativo.
	🔄 En desarrollo
  
RF-03	El sistema deberá registrar un historial completo de pedidos por cliente para facilitar
la gestión de clientes frecuentes y análisis de patrones de consumo		🔄 En desarrollo

3.2 Requisitos No Funcionales
Código	Descripción	Tipo

RNF-01	Disponibilidad (99.9% uptime)	Usabilidad

RNF-02	La base de datos debe soportar al menos 1000 registros.	Rendimiento

RNF-03	Rendimiento y tiempo de respuesta.	Rendimiento

🧭 4. Modelos del Sistema
4.1 Diagrama de Casos de Uso
<img width="703" height="469" alt="image" src="https://github.com/user-attachments/assets/e0dcfe07-1299-4b4c-b74e-cb942d2455af" />

4.2 Diagrama de Clases
<!-- Inserta aquí una imagen o enlace -->
<img width="1245" height="794" alt="image" src="https://github.com/user-attachments/assets/c84fd55e-8a8b-419c-9699-1c79ee721989" />


4.3 Arquitectura del Software

Tipo de arquitectura: Por capas (Presentación, Lógica de Negocio, Datos)

- Capa de presentación: interfaz Cliente, interfaz Admin,interfaz Reportes.
- Capa lógica de negocio: Gestor usuarios,gestor pedidos, gestor inventarios, gestor clientes, gestor facturacion, gestor reportes.
- Capa de datos:  base de datos,sistema de archivos, servidor del cache.

Diagrama de Arquitectura: Arquitectura del Sistema

⚙️ 5. Componentes Principales
Componente	Función	Interacción	Estado
GestorUsuarios	Registrar, autenticar y administrar usuarios	Base de datos, interfaz	✅
GestorPedidos	Crear, modificar y eliminar pedidos 	🔄
GestorInventarios	Controlar stock de productos, Base de datos⏳
gestor clientes Administrar,Base de datos, interfaz de gestión,Validación de datos ✅
gestor facturacion Generar recibos de caja y facturas,GestorPedidos, Base de datos ✅
gestor reportes Generar informes y estadísticas del sistema,Base de datos, todos los gestores,álculo de estadísticas ✅

🧰 6. Tecnologías y Herramientas
Herramientas de Uso dentro del proyecto
Git	Control de versiones local
GitHub	Repositorio remoto y trabajo colaborativo
 StarUML	Diagramas UML
Lucidchart / Canva	Esquematización visual
Unity / Python / HTML-CSS-JS (según caso)	Desarrollo técnico
Trello / Notion / Excel	Planificación y seguimiento

📅 7. Planificación y Control
7.1 Cronograma de avance
Semana	Actividad	Estado
1-2 | Análisis de requisitos y diseño de BD | ✅
3-4 | Desarrollo gestión de usuarios y clientes | 🔄
5-6 | Desarrollo gestión de platos y pedidos | ⏳
7-8 | Desarrollo facturación y reportes | ⏳
9-10 | Pruebas y correcciones | ⏳
11-12 | Despliegue y documentación | ⏳


6	Modelado de casos de uso	✅
7	Diagramas de clases	✅
8	Arquitectura del software	✅
9	Gestión de versiones (Git/GitHub)	✅
10	Documentación técnica inicial	✅
11	Avance del proyecto final	🔄 En revisión
7.2 Control de versiones
Rama principal: main
Ramas secundarias: feat/, fix/, docs/
Último commit:
```bash git log -1
