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
Fecha de actualización:  1/12/2025


Resumen del Proyecto OrderUp


📋 Información General
Proyecto: Sistema de Gestión de Pedidos OrderUp
Autores: Frank Josswar Vente Canchimbo y Juan David Villarreal Cortes
Institución: Universidad Antonio José Camacho - Ingeniería de Sistemas
Fecha: 1 de diciembre 2025


🎯 Objetivo del Sistema
OrderUp es una solución tecnológica integral diseñada para optimizar el proceso completo de recepción, procesamiento y entrega de pedidos en establecimientos de restauración. El sistema busca eliminar problemas críticos del sector gastronómico como errores de transcripción manual, falta de confirmación automática, ausencia de seguimiento en tiempo real y dificultades en la gestión de inventario.


🔑 Características Principales
Módulos del Sistema:
Gestión de Usuarios - Manejo de clientes, empleados, repartidores y administradores
Gestión de Pedidos - Seguimiento en tiempo real desde la recepción hasta la entrega
Gestión de Inventario - Control automático con alertas de stock bajo
Facturación y Pagos - Procesamiento de transacciones y generación de facturas
Asignación de Entregas - Coordinación de repartidores y rutas
Generación de Reportes - Análisis de ventas y desempeño

Funcionalidades Clave:

✅ Registro digital estructurado de pedidos

✅ Confirmación automática vía WhatsApp, email y notificaciones push

✅ Seguimiento en tiempo real del estado de pedidos

✅ Personalización de productos e ingredientes

✅ Alertas automáticas de inventario bajo

✅ Integración con pasarelas de pago externas

✅ Interfaz web responsive y aplicación móvil para repartidores


💻 Tecnologías Utilizadas

Frontend: HTML5, CSS3, JavaScript (React.js/Vue.js), Material-UI/Bootstrap

Backend: Java (Spring Boot) o PHP (Laravel), API REST, JWT

Base de Datos: PostgreSQL, Redis (caché), AWS S3

Móvil: Flutter o React Native

DevOps: Git/GitHub, Docker, AWS EC2/Heroku


📊 Requisitos No Funcionales

Rendimiento: Registro de pedidos < 2 segundos, actualización de estado < 1 segundo

Seguridad: Encriptación bcrypt, autenticación 2FA, prevención SQL injection/XSS

Escalabilidad: Soporte para mínimo 50 usuarios simultáneos, arquitectura para microservicios

Disponibilidad: 99.5% de uptime, backup automático diario


🧪 Resultados de Pruebas
El proyecto fue sometido a 5 casos de prueba que validaron los requisitos funcionales principales:

Métrica 1: 
Casos ejecutados

Resultado: 5

Métrica 2:
Casos exitosos	         

Resultado: 5 (100%) ✅

Métrica 3: Requisitos validados	

Resultado: 7 de 8 (87.5%)

Cumplimiento de tiempos	 100% ✅

Tiempos de Respuesta Alcanzados:

Registro de pedido: 1.8s (objetivo: <2s)

Actualización de estado: 0.7s (objetivo: <1s)

Procesamiento de pago: 4.2s (objetivo: <5s)


⚠️ Áreas de Mejora Identificadas

Críticas:

Sistema de reportes sin modelo completo (RF-07 pendiente)

Sistema de calificaciones incompleto

Mejoras Propuestas:

Implementar validaciones robustas frontend/backend

Agregar casos de prueba para escenarios de error

Implementar caché Redis para optimización

Dashboard de métricas en tiempo real


🎉 Logros del Proyecto

✅ 100% de éxito en casos de prueba ejecutados

✅ 87.5% de trazabilidad entre requisitos funcionales y diseño

✅ Arquitectura sólida cliente-servidor en tres capas

✅ Tiempos de respuesta que cumplen los estándares esperados

✅ Sistema modular escalable y preparado para crecimiento



👥 Usuarios del Sistema

Clientes: Realizar y rastrear pedidos, ver historial

Empleados: Procesar pedidos, gestionar inventario

Repartidores: Recibir asignaciones, actualizar entregas

Administradores: Generar reportes, gestionar usuarios

El proyecto OrderUp representa una solución integral y moderna para la gestión de pedidos en el sector de restauración, con una arquitectura sólida, tecnologías actuales y resultados de validación exitosos. El sistema está diseñado para mejorar significativamente la eficiencia operativa y la satisfacción del cliente mediante la automatización y digitalización de procesos críticos.
