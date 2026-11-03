# ICN292 - Laboratorio 4 - Base de datos en SQL (Austral Editores)

**Nombre:** Trinidad Salinas

**Fecha de entrega:** 02/11/2026

## Contenido de este repositorio

- `ICN292-Lab4-Salinas-Trinidad.sql`: script con la creación de la base `austral`, la carga oficial y las diez consultas
- `ICN292-Lab4-Salinas-Trinidad.pdf`: informe con el código y la captura de cada consulta
- `ICN292-Lab4-Salinas-Trinidad.docx`: informe en Word
- `ICN292-Lab4-Salinas-Trinidad.png`: modelo entidad-relación de la base `austral`

## Cómo reproducir

1. Abrir MySQL Workbench conectado a un servidor MySQL 8.
2. Abrir el archivo `.sql` (File → Open SQL Script...).
3. Ejecutarlo completo con el primer rayo. El script parte con `DROP DATABASE IF EXISTS austral;`, así que recrea la base desde cero y se puede correr varias veces.
4. Las consultas 1 a 6 se ejecutan sobre la carga oficial, antes de las modificaciones de las consultas 7 y 8.
5. Las consultas 9 y 10 usan filas de prueba que el propio script inserta en `colecciones` y `pagos`.
