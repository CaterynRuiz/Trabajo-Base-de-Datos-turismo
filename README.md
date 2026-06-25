Sistema de gestión basado en MySQL. Diseño, creación y administración de la base de datos mediante XAMPP, HeidiSQL y phpMyAdmin.

## 📋 Integrantes
* Ricardo Nuñez Cardoza
* Sofia Antonella Gauna
* Cateryn Ruiz
* Tomas Anchorena
* Daimary Rujano

**Docente:** Emanuel Odstrcil | **Institución:** Instituto de Formación Técnica Superior N° 18

## 🚀 Descripción del Proyecto
El principal objetivo es almacenar, organizar y administrar la información relacionada con clientes, destinos, viajes y servicios complementarios ofrecidos por una empresa de turismo. La solución busca optimizar los procesos administrativos mediante la centralización de la información, garantizando la integridad y consistencia de los datos.

### 🛠️ Herramientas Utilizadas
* **Motor de Base de Datos:** MySQL
* **Entorno de Servidor Local:** XAMPP
* **Administradores de BD:** HeidiSQL / phpMyAdmin
* **Diseño del Diagrama:** Draw.io

## 🗺️ Modelo de Negocio (Reglas)
* Cada cliente podrá realizar varios viajes, pero cada viaje corresponderá a un único cliente.
* Un destino podrá ser asociado a muchos viajes, mientras que cada viaje tendrá un solo destino.
* Un viaje podrá incluir varios servicios y un mismo servicio podrá ser contratado en distintos viajes.

## 📊 Diagrama Entidad-Relación
Podés ver el diseño de la estructura del modelo relacional en la imagen adjunta:

![Diagrama de Tablas](TP%20TURISMO.drawio.png)

## 🗄️ Estructura de la Base de Datos
La base de datos `empresa_de_turismo` está compuesta por las siguientes tablas:
1. **clientes**: Registro de datos personales y de contacto de los pasajeros.
2. **destinos**: Información sobre los lugares de viaje y sus costos base.
3. **servicios**: Servicios adicionales que se pueden contratar (Hotel, Excursión, Traslado, etc.).
4. **viajes**: Vinculación de los clientes con sus destinos y fechas programadas.
5. **viajes_servicios**: Tabla intermedia que asocia los servicios contratados para cada viaje específico.

## ⚙️ Cómo Ejecutar el Proyecto
1. Descargá el archivo de la base de datos disponible en este repositorio.
2. Iniciá los módulos **Apache** y **MySQL** desde el panel de control de **XAMPP**.
3. Abrí tu gestor preferido (**phpMyAdmin** o **HeidiSQL**).
4. Creá una nueva base de datos llamada `empresa_de_turismo`.
5. Seleccioná la base de datos e importá el script SQL para generar las tablas y los datos de prueba.
