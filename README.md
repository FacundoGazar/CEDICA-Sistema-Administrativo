# Sistema de administración privado y portal público para CEDICA.

![](https://hips.hearstapps.com/hmg-prod/images/elm050121wlolivia-007-logo-1618513509.jpg)


# Contexto

El **Centro de Equitación para Personas con Discapacidad y Carenciadas**, **CEDICA**, es una Asociación Civil sin Fines de Lucro, fundada en 1994 en la ciudad de La Plata, Provincia de Buenos Aires, Argentina. CEDICA trabaja con la finalidad de IGUALAR OPORTUNIDADES en procura de la reinserción familiar, el logro de la escolaridad, la integración laboral y la mejora integral de la calidad de vida de los J&A (“Jinetes” y “Amazonas”) que forman parte de la institución.

Las actividades que se realizan se denominan Terapias y Actividades asistidas con Caballos –TACAs-, aunque históricamente también fueron conocidas con otros términos como Rehabilitación Ecuestre o Equinoterapia. Se trata de una terapia integral que apunta a la recuperación de la persona en sus dimensiones biológica, psíquica y social. El principal recurso de trabajo es el Caballo, como mediador y facilitador de las intervenciones terapéuticas que cada profesional de la salud o la educación planifica para las diferentes Personas con Discapacidad que asisten a la institución.

CEDICA cuenta con un Equipo de trabajo integrado por personal ecuestre, técnicos y profesionales: Terapistas Ocupacionales (T.O.), Psicólogos, Psicopedagogos, Psicomotricistas, Profesores de Educación Física y Equitación; Instructores de Volteo; Médico Veterinario, capacitados en TACAs. A ello se suman anualmente una gran cantidad de voluntarios, en su mayoría estudiantes universitarios de la UNLP y la UNQUI; y el plantel se completa con los caballos en actividad y potrillos en etapa de entrenamiento.

Este Equipo de trabajo se divide en 5 grandes Áreas, a saber: Área Técnica, Área Ecuestre, Área de Voluntariado, Área de Gestión y Administración; y Área de Capacitación. Cada una de ellas, cuenta con sus propios Procesos de Trabajo para cumplir con la tarea y los objetivos institucionales.

# Objetivo general

El objetivo de este trabajo es desarrollar una Aplicación Web que permita contar con mucha de la información en formato digital que contienen los diferentes procesos de trabajo de una institución de TACAs. Los usuarios directos serían los integrantes del equipo de CEDICA.

La solución tendrá un aplicación interna de administración (para usuarios y administradores) desarrollada en Python y Flask, y un portal web desarrollado en Vue.js donde se podrán visualizar los servicios ofrecidos por la institución. Utilizaremos una base de datos PostgreSQL y se implementará una API con los endpoints necesarios para la integración de estas dos aplicaciones.

# Funcionalidad de la aplicación

La aplicación permitirá:

-   Mantener un registro histórico de los legajos de los J&A (Jinetes y Amazonas), incluyendo anexos de documentación necesaria.
-   Mantener un registro de los Legajos de los profesionales del equipo.
-   Registrar la información de los caballos.
-   Obtener reportes estadísticos: la aplicación debe producir reportes que presenten estadísticas relevantes sobre los datos manejados.

# Componentes de la aplicación

Aplicación de administración en Python y Flask: desarrollar una aplicación que permita la administración de altas, bajas y modificaciones de los recursos necesarios para el sistema. También se deberá implementar un registro de usuarios y un sistema de autenticación para operar con la aplicación.

Portal en Vue.js: crear una interfaz de usuario interactiva que permita visualizar los diferentes servicios que brinda la institución (segunda etapa).

Base de datos PostgreSQL: diseñar la estructura de la base de datos para almacenar la información de las instituciones, servicios y usuarios de la aplicación.

API para consultas: implementar API que permitan realizar las consultas necesarias para obtener la información que se quiera visualizar en el portal.
