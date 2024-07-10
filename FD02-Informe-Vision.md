<center>

[comment]: <img src="./media/media/image1.png" style="width:1.088in;height:1.46256in" alt="escudo.png" />

![./media/media/image1.png](./media/logo-upt.png)

**UNIVERSIDAD PRIVADA DE TACNA**

**FACULTAD DE INGENIERIA**

**Escuela Profesional de Ingeniería de Sistemas**

**Proyecto *{Nombre de Proyecto}***

Curso: *Inteligencia de Negocios*

Docente: *Ing. Patrick Jose Cuadros Quiroga*

Integrantes:
- *Rivera Mendoza Jhonny*
- *Cano Sucso Anthony Alexander*
- *Jarro Cachi Jose Luis*
- *Valverde Zamora Jean Pier Elias*
- *Chambilla Zuñiga Josue*


**Tacna – Perú**

***2024***


</center>
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|JJCRV|JJCRV|JJCRV|25/06/2024|Versión Original|












**Sistema *Zofra Tacna***

**Documento de Visión**

**Versión *{1.0}***
**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|JJCRV|JJCRV|JJCRV|25/06/2024|Versión Original|



<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


**INDICE GENERAL**
#
[1.	Introducción](#_Toc52661346)

1.1	Propósito

1.2	Alcance

1.3	Definiciones, Siglas y Abreviaturas

1.4	Referencias

1.5	Visión General

[2.	Posicionamiento](#_Toc52661347)

2.1	Oportunidad de negocio

2.2	Definición del problema

[3.	Descripción de los interesados y usuarios](#_Toc52661348)

3.1	Resumen de los interesados

3.2	Resumen de los usuarios

3.3	Entorno de usuario

3.4	Perfiles de los interesados

3.5	Perfiles de los Usuarios

3.6	Necesidades de los interesados y usuarios

[4.	Vista General del Producto](#_Toc52661349)

4.1	Perspectiva del producto

4.2	Resumen de capacidades

4.3	Suposiciones y dependencias

4.4	Costos y precios

4.5	Licenciamiento e instalación

[5.	Características del producto](#_Toc52661350)

[6.	Restricciones](#_Toc52661351)

[7.	Rangos de calidad](#_Toc52661352)

[8.	Precedencia y Prioridad](#_Toc52661353)

[9.	Otros requerimientos del producto](#_Toc52661354)

b) Estandares legales

c) Estandares de comunicación	](#_toc394513800)37

d) Estandaraes de cumplimiento de la plataforma	](#_toc394513800)42

e) Estandaraes de calidad y seguridad	](#_toc394513800)42

[CONCLUSIONES](#_Toc52661355)

[RECOMENDACIONES](#_Toc52661356)

[BIBLIOGRAFIA](#_Toc52661357)

[WEBGRAFIA](#_Toc52661358)


## 1. Introducción

### 1.1 Propósito
El propósito de esta documentación es proporcionar una guía comprensiva sobre la creación y uso de dashboards utilizando los servicios de Amazon Web Services (AWS) para la gestión de datos de Zofratacna. Estos datos incluyen gastos, costos de telefonía, ingresos, egresos, remuneraciones, partidas salariales, inversiones y órdenes de compra. La documentación está diseñada para asegurar que todos los involucrados comprendan el proceso y los objetivos del proyecto.

### 1.2 Alcance
Esta documentación abarca todos los aspectos del proyecto de creación de dashboards, desde la recopilación de datos en archivos Excel hasta la presentación final en los dashboards de AWS. Incluye la definición de los requisitos, la descripción del entorno de usuario, las capacidades del sistema y las especificaciones técnicas.

### 1.3 Definiciones, Siglas y Abreviaturas
- **AWS**: Amazon Web Services
- **BI**: Business Intelligence
- **Excel**: Formato de archivo utilizado para hojas de cálculo
- **Dashboard**: Herramienta de visualización de datos
- **ETL**: Extract, Transform, Load (Extracción, Transformación, Carga)

### 1.4 Referencias
- Documentación de AWS: [AWS Documentation](https://aws.amazon.com/documentation/)
- Guía de mejores prácticas de BI
- Manuales de usuario de los sistemas internos de Zofratacna

### 1.5 Visión General
Esta sección proporciona una visión general del proyecto, destacando los principales objetivos y beneficios de implementar dashboards para la gestión de datos en Zofratacna.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## 2. Posicionamiento

### 2.1 Oportunidad de negocio
La implementación de dashboards proporciona a Zofratacna una oportunidad significativa para mejorar la eficiencia operativa y la toma de decisiones informadas mediante el análisis en tiempo real de los datos financieros y operativos.

### 2.2 Definición del problema
Actualmente, la gestión y análisis de datos en Zofratacna se realiza de manera manual y descentralizada, lo que lleva a ineficiencias y posibles errores en la interpretación de los datos. Este proyecto aborda estos problemas mediante la centralización y automatización del análisis de datos.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## 3. Descripción de los interesados y usuarios

### 3.1 Resumen de los interesados
- **Directivos**: Necesitan información resumida y precisa para la toma de decisiones estratégicas.
- **Gerentes de Finanzas**: Requieren detalles sobre ingresos, egresos, inversiones y costos operativos.
- **Departamento de Recursos Humanos**: Necesitan acceso a datos sobre remuneraciones y partidas salariales.

### 3.2 Resumen de los usuarios
- **Analistas de Datos**: Encargados de la creación y mantenimiento de los dashboards.
- **Gerentes de Proyecto**: Supervisan la implementación y uso del sistema.
- **Operadores**: Utilizan los dashboards para la gestión diaria de operaciones.

### 3.3 Entorno de usuario
El entorno de usuario comprende la infraestructura de AWS, donde se almacenan y procesan los datos, y las interfaces de usuario proporcionadas por las herramientas de visualización de datos.

### 3.4 Perfiles de los interesados
- **Directivos**: Alta responsabilidad, enfoque en resultados financieros y estratégicos.
- **Gerentes de Finanzas**: Enfoque en la gestión financiera detallada y análisis de costos.
- **Departamento de Recursos Humanos**: Enfoque en la administración del personal y costos asociados.

### 3.5 Perfiles de los Usuarios
- **Analistas de Datos**: Profesionales con experiencia en BI y análisis de datos.
- **Gerentes de Proyecto**: Profesionales con habilidades en gestión de proyectos y tecnología.
- **Operadores**: Usuarios con conocimiento operativo de los sistemas de Zofratacna.

### 3.6 Necesidades de los interesados y usuarios
- **Directivos**: Necesitan informes de alto nivel y análisis predictivos.
- **Gerentes de Finanzas**: Requieren acceso detallado a datos financieros y de costos.
- **Departamento de Recursos Humanos**: Necesitan visibilidad sobre los costos de remuneraciones y partidas salariales.
- **Analistas de Datos**: Requieren herramientas potentes y flexibles para el análisis de datos.
- **Operadores**: Necesitan interfaces fáciles de usar para la gestión diaria de operaciones.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## 4. Vista General del Producto

### 4.1 Perspectiva del producto
El producto es un sistema de dashboards integrado en AWS, diseñado para centralizar y visualizar datos financieros y operativos de Zofratacna. Utiliza herramientas de BI para transformar datos de Excel en insights accionables.

### 4.2 Resumen de capacidades
- **Importación de datos**: Subida de archivos Excel a AWS.
- **Transformación de datos**: Procesamiento y limpieza de datos.
- **Visualización**: Creación de dashboards interactivos.
- **Automatización**: Actualización automática de datos y reportes.

### 4.3 Suposiciones y dependencias
- **Disponibilidad de datos**: Los datos se proporcionarán en formato Excel.
- **Acceso a AWS**: Se requiere acceso a los servicios de AWS para la implementación.
- **Competencia técnica**: Los usuarios clave tienen habilidades técnicas suficientes para interactuar con los dashboards.

### 4.4 Costos y precios
El proyecto incluye costos de suscripción a los servicios de AWS, licencias de software de BI y costos de capacitación para los usuarios.

### 4.5 Licenciamiento e instalación
- **Licencias**: Se adquirirán licencias necesarias para las herramientas de BI y servicios de AWS.
- **Instalación**: La configuración inicial y la instalación del sistema serán gestionadas por el equipo de TI de Zofratacna en colaboración con consultores externos si es necesario.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## 5. Características del producto
- **Interactividad**: Dashboards interactivos que permiten la exploración de datos.
- **Actualización automática**: Datos actualizados en tiempo real.
- **Seguridad**: Acceso seguro y controlado a los datos.
- **Personalización**: Capacidad para personalizar vistas y reportes según las necesidades del usuario.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## 6. Restricciones
- **Formato de datos**: Los datos deben ser proporcionados en formato Excel compatible.
- **Conectividad**: Requiere conexión estable a internet para acceder a los servicios de AWS.
- **Seguridad de datos**: Se deben seguir las políticas de seguridad de Zofratacna para la gestión de datos sensibles.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## 7. Rangos de Calidad
- **Disponibilidad**: El sistema debe estar disponible el 99.9% del tiempo.
- **Precisión**: Los datos presentados deben ser 100% precisos y verificados.
- **Rendimiento**: Los dashboards deben cargar en menos de 5 segundos.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## 8. Precedencia y Prioridad
1. Importación y procesamiento de datos.
2. Creación de dashboards.
3. Capacitación de usuarios.
4. Implementación de seguridad y acceso.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## 9. Otros requerimientos del producto

### 9.1 Estandares legales
Cumplir con todas las normativas y regulaciones locales e internacionales aplicables a la gestión de datos financieros.

### 9.2 Estandares de comunicación
Asegurar que toda la comunicación entre los sistemas de AWS y los usuarios finales esté encriptada y segura.

### 9.3 Estandaraes de cumplimiento de la plataforma
Seguir las mejores prácticas de AWS para la seguridad, disponibilidad y escalabilidad.

### 9.4 Estandaraes de calidad y seguridad
Implementar controles de calidad para garantizar la precisión de los datos y medidas de seguridad robustas para proteger la información sensible.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## Conclusiones
El proyecto de implementación de dashboards en AWS para Zofratacna permitirá una gestión más eficiente y precisa de los datos financieros y operativos, mejorando la toma de decisiones y reduciendo errores.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## Recomendaciones
- Realizar una fase piloto para probar el sistema con un subconjunto de datos.
- Proveer capacitación continua a los usuarios.
- Implementar un plan de mantenimiento y soporte para el sistema.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## Bibliografía
- Amazon Web Services Documentation
- Manuales internos de Zofratacna
- Guías de mejores prácticas en Business Intelligence

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

## Webgrafía
- [AWS Documentation](https://aws.amazon.com/documentation/)
- [Tutoriales de BI en AWS](https://aws.amazon.com/training/)
