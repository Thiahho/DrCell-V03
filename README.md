🔹 README – Sistema E-commerce DrCell
1. Nombre del Proyecto

DrCell – Sistema de E-commerce y Reparaciones de Celulares

Breve descripción:

Sistema web completo para venta de productos y gestión de reparaciones de celulares, con catálogo de productos, carrito de compras, calculadora de presupuestos y panel administrativo con dashboard analítico.

2. Funcionalidades Principales
E-commerce Core

Catálogo de productos con categorías y variantes (RAM, almacenamiento, color)

Carrito de compras con gestión de sesiones

Checkout integrado con MercadoPago

Gestión de stock en tiempo real con reservas temporales

Flujo completo de ventas hasta la confirmación

Módulo de Reparaciones

Calculadora de presupuestos por marca y modelo

Base de datos de componentes (módulos, baterías, pines)

Cotización dinámica y sistema de consultas para servicios técnicos

Panel Administrativo

Dashboard con métricas de ventas y ganancias

Gestión de productos, variantes y categorías

Control de inventario con alertas automáticas

Exportación de datos a Excel

Sistema de Autenticación

JWT con cookies HTTP-only

Roles de usuario (admin / cliente)

Rutas protegidas en frontend y backend

Gestión segura de sesiones

3. Stack Tecnológico

Backend:

.NET Core 8, Entity Framework Core, PostgreSQL

Arquitectura Clean + Repository/Service pattern

Middleware personalizado para JWT, logging avanzado (Serilog), rate limiting

Frontend:

React 18 + TypeScript

TailwindCSS, Radix UI, UI responsive mobile-first

Zustand para estado global, Axios para consumo de APIs

DevOps / Deployment:

Docker Compose para orquestación

Nginx como reverse proxy

Health Checks y monitoreo

Configuración por ambientes (dev/prod)

4. Logros Técnicos Destacados

Sistema de stock inteligente con reservas temporales y control de concurrencia

Arquitectura escalable y segura con caching y validaciones en todas las capas

Interfaz moderna y responsive con feedback inmediato

Flujo completo de checkout con MercadoPago y webhooks automáticos

Panel analítico con métricas en tiempo real y alertas de stock bajo

Calculadora de presupuestos de reparaciones inteligente y base de datos especializada

5. Instalación y Deployment
Requisitos

Docker y Docker Compose

Node.js + npm/yarn

.NET Core 8 SDK

PostgreSQL
