# PostgreSQL ETL Logging & Auditing Framework (Free Base Tables)

Un esquema ligero y optimizado en PostgreSQL DDL para la auditoría de procesos de cargas de datos y pipelines ETL.

## 📁 Contenido de este repositorio
- `01_DDL_Create_Tables_Postgres.sql`: Tablas optimizadas (`etl_process_execution_log`, `etl_error_log`) con columnas de identidad y restricciones para control de excepciones.

---

## 🚀 ¿Necesitas las Funciones y Procedimientos PL/pgSQL listos para producción?
Las tablas por sí solas son el punto de partida, pero si quieres la lógica completa con funciones de inicio, cierre de éxito y captura de errores con contexto para desplegarlo en minutos en tu base de datos PostgreSQL:

👉 **[Consigue el Enterprise ETL Logging Framework para PostgreSQL completo en Gumroad (https://carlodomi4.gumroad.com/l/wfcws)**

### ¿Qué incluye la versión completa?
- Funciones y procedimientos almacenados en PL/pgSQL (`fn_etl_start_execution`, `sp_etl_end_execution`, `sp_etl_log_error`) listos para usar.
- Documentación detallada y bloques de ejemplo (`DO $$ ... $$`) para integrar directamente en tus scripts y orquestadores.
