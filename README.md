# Examen Parcial - Proyecto Big Data  - Caso Yape (Semana 04)

**Autor:** Armando Jheferson Carbajal Campomanes  
**Código:** 2231896838  

### Este repositorio contiene la resolución técnica y el desarrollo del examen parcial, enfocado en el diseño de arquitectura y la implementación de un ecosistema de datos utilizando herramientas en la nube y entornos locales.
---
🔗 **[Enlace al video de demostración en OBS]**
#### https://drive.google.com/file/d/1rqCYVaNxoA5EAbGr4lcZ3xMLZo9O-Fub/view?usp=drive_link  

🔗 **[Link del Repositorio Github]**
#### https://github.com/acarbajalCode/yape-carbajal-armando.git  
---

## 🛠️ Tecnologías y Metodologías Implementadas
1. **Diseño de Arquitectura y Teorema CAP:**
   - Selección fundamentada de stack tecnológico (CockroachDB, Redis, MongoDB, Neo4j).
   - Equilibrio entre consistencia y disponibilidad para transacciones financieras críticas.
2. **Procesamiento de Datos con Databricks (PySpark):**
   - Implementación de **Arquitectura Medallion** (Bronze, Silver, Gold).
   - Limpieza de datos, aplicación de reglas de negocio y agregación gerencial.
   - Visualización de datos a través de un Dashboard automatizado con `matplotlib`.
3. **Almacenamiento NoSQL con MongoDB Atlas:**
   - Aprovechamiento de esquemas flexibles para modelado de comercios heterogéneos (farmacias, taxis, bodegas).
   - Implementación de un `Aggregation Pipeline` para el reporte de facturación.
4. **Contenerización con Docker Desktop:**
   - Despliegue de un entorno de MongoDB local aislado para pruebas (CI/CD).
   - Solución de conflictos de puertos y persistencia de volúmenes en Windows.