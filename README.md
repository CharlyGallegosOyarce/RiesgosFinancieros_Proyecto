# Sistema de Información para Evaluación de Riesgos Financieros

## Descripción
Sistema completo para la evaluación y monitoreo de riesgos financieros, implementado en SQL Server con integración Power BI.

## Características Principales
✅ Base de datos normalizada y optimizada  
✅ Procedimientos almacenados T-SQL  
✅ Dashboard interactivo Power BI  
✅ Automatización de procesos ETL  
✅ API REST (próxima versión)  

## Instalación Rápida

### 1. Requisitos
- SQL Server 2019+
- Power BI Desktop
- Python 3.8+ (opcional)

### 2. Configuración de Base de Datos
```sql
-- Ejecutar en orden:
sqlcmd -S localhost -i database/01_create_database.sql
sqlcmd -S localhost -i database/02_create_tables.sql
