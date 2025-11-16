# conflict-exercise
Conflicto resuelto


# Sistema de Gestión Vehicular

## Descripción del Dominio
Sistema CRUD completo para gestión de vehículos y sus seguros asociados. Desarrollado en Java con arquitectura en capas (Models, DAO, Service, Config) y MySQL como base de datos relacional.

## Funcionalidades principales:
- Gestión de vehículos (alta, baja, modificación, consulta)
- Administración de pólizas de seguro
- Relación opcional vehículo-seguro
- Eliminación lógica de registros
- Búsqueda por dominio y marca

## Requisitos Técnicos
**Requisitos mínimos:**
- Java JDK 8 o superior
- MySQL 5.7 o superior
- MySQL Connector/J 8.0.33

## Configuración de Base de Datos

### 1. Crear base de datos y tablas
Ejecutar en MySQL Workbench o línea de comandos:
```sql
-- Crear estructura
SOURCE database/database_schema.sql

-- Insertar datos de prueba
SOURCE database/sample_data.sql
