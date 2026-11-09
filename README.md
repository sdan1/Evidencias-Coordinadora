# Sistema de Gestión y Seguimiento de Envíos - Coordinadora Mercantil

Repositorio oficial para el desarrollo del proyecto de base de datos del Sistema de Gestión y Seguimiento de Envíos, basado en las operaciones logísticas de **Coordinadora Mercantil**.

## 👥 Autoras
* **Sarah Daniela Julio Sánchez** (Código: 0192340)
* **Yuliany Michell Sánchez Becerra** (Código: 0192372)
* **Mariana Muñoz Pelaez** (Código: 0192207)

---

## 🏗️ Descripción del Proyecto
El proyecto modela y centraliza la información generada durante el ciclo de vida de un envío (desde la admisión y recogida, pasando por centros logísticos y transporte, hasta la entrega final al destinatario). El diseño relacional consta de **12 tablas normalizadas** que garantizan la trazabilidad y el cumplimiento de las normativas de auditoría logística.

---

## 🗄️ Estructura de la Base de Suministro y Datos
El modelo físico comprende las siguientes entidades principales dentro del esquema `coordinadora`:
1. `countries` (Países)
2. `states` (Departamentos)
3. `cities` (Ciudades)
4. `senders` (Remitentes)
5. `addressees` (Destinatarios)
6. `logistics_centers` (Centros Logísticos)
7. `employees` (Empleados)
8. `shipments` (Envíos)
9. `packages` (Paquetes)
10. `follow_ups` (Seguimiento del envio)
11. `novelties` (Novedades de Entrega)
12. `deliveries` (Entregas)

---

## ⚙️ Tecnologías y Herramientas Utilizadas
* **Motor de Base de Datos:** PostgreSQL
* **Entorno de Desarrollo Local:** pgAdmin
* **Entorno de Producción / Nube:** Supabase
* **Generación de Datos:** con ayuda de IA

---

## 📂 Contenido del Repositorio
* Documentacion segundo parcial
* Documento recoleccion de evidencias 
* Modelo logico
* Modelo fisico
* Modelo realizado en db visualizer
* Carpeta comprimida con los .csv para poblar las tablas.

---

## 🚀 Despliegue y Funcionamiento
1. La estructura relacional (DDL) fue diseñada y probada localmente en **pgAdmin**.
2. Los datos sintéticos fueron generados e importados masivamente respetando las dependencias jerárquicas del modelo.
3. El modelo físico definitivo fue desplegado y puesto en marcha en la nube mediante **Supabase** (`esquema coordinadora`), garantizando disponibilidad para la solución web.
