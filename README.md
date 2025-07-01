# Diseño e Implementación de Base de Datos para Guardería Náutica

Este repositorio contiene el diseño completo y la implementación de una base de datos relacional para "Gaghiel", un sistema de gestión para una guardería náutica que incluye una escuela de actividades acuáticas.

El proyecto abarca todo el ciclo de vida del diseño de una base de datos, desde el análisis de los requerimientos de negocio hasta la creación del schema físico y la carga de datos. Fue desarrollado como parte de la evaluación de la cátedra de Bases de Datos en la Universidad Tecnológica Nacional (UTN).

## 📜 Descripción del Sistema

El sistema modelado gestiona dos áreas de negocio principales:

1.  **Guardería Náutica:** Administra socios, sus embarcaciones, los contratos de alquiler de camas/cunas en diferentes sectores, y el registro de salidas y regresos de las embarcaciones.
2.  **Escuela Náutica:** Gestiona las actividades ofrecidas, los instructores capacitados para cada una, la creación de cursos y la inscripción de socios a los mismos.

## ⚙️ Proceso de Diseño y Artefactos

El desarrollo de la base de datos siguió un proceso estructurado:

1.  **Análisis de Requerimientos:** Se partió de un enunciado narrativo que describe las reglas de negocio y las necesidades de información del sistema.
    * Puedes ver el enunciado original aquí: **[Enunciado del Problema (PDF)](Enunciado_GuarderiaNautica.pdf)**

2.  **Modelo Conceptual (Diagrama E-R):** Se diseñó un Diagrama Entidad-Relación (DER) para representar visualmente las entidades, sus atributos y las relaciones entre ellas.
    * Puedes ver el diagrama aquí: **[Diagrama Entidad-Relación (PNG)](DER_GuarderiaNautica.png)**

3.  **Modelo Lógico (Pasaje a Tablas):** El modelo E-R se transformó en un modelo relacional, definiendo cada tabla con sus columnas, claves primarias, claves foráneas y restricciones de nulidad.
    * El detalle del esquema se encuentra en el informe de resolución.

4.  **Implementación Física (SQL):** Finalmente, se creó un script `.sql` con las sentencias DDL (`CREATE TABLE`) para construir la estructura de la base de datos y sentencias DML (`INSERT INTO`) para poblarla con un conjunto completo de datos de ejemplo.
    * El script de la base de datos se puede encontrar aquí: **[guarderia_gaghiel_v1.0.sql](guarderia_gaghiel_v1.0.sql)**

## 🚀 Habilidades Demostradas

* Análisis de requerimientos de negocio.
* Modelado de Datos y Diseño de Bases de Datos Relacionales.
* Creación de Diagramas Entidad-Relación (DER).
* Normalización de Bases de Datos.
* Lenguaje de Consulta Estructurado (SQL):
    * DDL (Data Definition Language) para la creación de la estructura.
    * DML (Data Manipulation Language) para la inserción de datos.
* Álgebra Relacional para la formulación de consultas.

## 🛠️ Cómo Usar

El archivo `guarderia_gaghiel_v1.0.sql` es un dump completo que puede ser importado en un sistema de gestión de bases de datos como MySQL o MariaDB para recrear la estructura y los datos del proyecto.
