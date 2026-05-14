# CSC Salud Comunitaria

## Índice de Acceso Rápido

* [Descripción del Proyecto](#descripción-del-proyecto)
* [Objetivos del Proyecto](#objetivos-del-proyecto)
* [Tecnologías Utilizadas](#tecnologías-utilizadas)
* [Arquitectura del Proyecto](#arquitectura-del-proyecto)
* [Principios de Diseño Aplicados](#principios-de-diseño-aplicados)
* [Funcionalidades Principales](#funcionalidades-principales)
* [Modelo Relacional General](#modelo-relacional-general)
* [Estructuras de Datos Utilizadas](#estructuras-de-datos-utilizadas)
* [Gestión de Datos](#gestión-de-datos)
* [Interfaz Gráfica](#interfaz-gráfica)
* [Buenas Prácticas Implementadas](#buenas-prácticas-implementadas)
* [Instalación](#instalación)
* [Estado del Proyecto](#estado-del-proyecto)
* [Autor](#autor)
* [Licencia](#licencia)
* [English Version](#english-version)

Sistema de gestión para un Centro de Salud Comunitario desarrollado en Java aplicando Programación Orientada a Objetos (POO), estructuras de datos y arquitectura modular.

---

# Descripción del Proyecto

CSC Salud Comunitaria es una aplicación diseñada para administrar procesos fundamentales de un centro médico comunitario, permitiendo la gestión organizada de:

* Pacientes
* Médicos
* Citas médicas
* Historias clínicas
* Servicios médicos
* Administración del sistema

El proyecto fue desarrollado con un enfoque académico y arquitectónico, implementando buenas prácticas de diseño de software, separación por capas y modularización de componentes.

---

# Objetivos del Proyecto

* Aplicar conceptos de Programación Orientada a Objetos.
* Implementar estructuras de datos en un sistema real.
* Diseñar una arquitectura escalable y mantenible.
* Gestionar información clínica de manera organizada.
* Simular el funcionamiento básico de un centro de salud comunitario.

---

# Tecnologías Utilizadas

| Tecnología              | Uso                            |
| ----------------------- | ------------------------------ |
| Java                    | Lógica principal del sistema   |
| Swing / GUI             | Interfaz gráfica               |
| POO                     | Modelado del sistema           |
| Estructuras de Datos    | Gestión interna de información |
| Persistencia en memoria | Gestión temporal de datos      |
| NetBeans                | Entorno de desarrollo          |
| Git & GitHub            | Control de versiones           |

---

# Arquitectura del Proyecto

El proyecto está organizado en módulos independientes para mejorar la mantenibilidad y escalabilidad.

```text
CSCSaludComunitaria
│
├── Model
│   ├── Personas
│   ├── Citas
│   ├── HistoriaClinica
│   └── Servicios
│
├── Servicios
│   ├── GestionPersonas
│   ├── GestionCitas
│   └── HistoriasClinicas
│
├── GUI
│
│
├── Utilidades
│
└── Main
```

---

# Principios de Diseño Aplicados

## Programación Orientada a Objetos

El sistema implementa:

* Encapsulamiento
* Herencia
* Polimorfismo
* Abstracción

Ejemplo:

```text
Persona
 ├── Paciente
 ├── Medico
 └── Administrador
```

---

# Funcionalidades Principales

## Gestión de Pacientes

* Registro de pacientes
* Consulta de información
* Actualización de datos
* Gestión de historial clínico

## Gestión de Médicos

* Registro de médicos
* Especialidades
* Administración de disponibilidad

## Gestión de Citas

* Agendamiento de citas
* Cancelación de citas
* Consulta de horarios
* Relación médico-paciente

## Historias Clínicas

* Registro de consultas
* Diagnósticos
* Tratamientos
* Seguimiento clínico

## Administración

* Gestión del sistema
* Control administrativo
* Organización de módulos

---

# Modelo Relacional General

Relaciones principales del sistema:

* Un paciente puede tener múltiples citas.
* Un médico puede atender múltiples citas.
* Un paciente posee una historia clínica.
* Una historia clínica contiene múltiples consultas.
* Una factura puede contener múltiples servicios.

---

# Estructuras de Datos Utilizadas

El sistema contempla el uso de estructuras de datos para optimizar la gestión de información:

* Listas
* Colas
* Árboles
* Colecciones dinámicas

Aplicaciones:

| Estructura | Uso                       |
| ---------- | ------------------------- |
| Cola       | Gestión de turnos y citas |
| Lista      | Pacientes e historiales   |
| Árbol      | Búsquedas organizadas     |

---

# Gestión de Datos

Actualmente el proyecto trabaja con almacenamiento temporal en memoria utilizando estructuras de datos y objetos durante la ejecución del programa.

No se implementa persistencia en bases de datos en esta versión.

La arquitectura fue diseñada para permitir una futura integración con sistemas de persistencia como Oracle, MySQL o PostgreSQL.

---

# Interfaz Gráfica

La aplicación incluye una interfaz gráfica orientada a escritorio para facilitar la interacción del usuario con el sistema.

Características:

* Navegación modular
* Formularios de registro
* Gestión visual de citas
* Administración intuitiva

---

# Buenas Prácticas Implementadas

* Separación de responsabilidades
* Modularización
* Arquitectura escalable
* Reutilización de código
* Organización por paquetes
* Manejo centralizado de lógica

---

# Instalación

## Requisitos

* Java JDK 17 o superior
* NetBeans IDE (Recomendado para editar la GUI) o Visual Studio Code 
* Git

## Clonar el Repositorio

```bash
git clone <URL_DEL_REPOSITORIO>
```

## Ejecutar el Proyecto

1. Abrir el proyecto en NetBeans.
2. Compilar el proyecto.
3. Ejecutar la clase principal.

---


# Estado del Proyecto

Proyecto en desarrollo activo.

Actualmente incluye:

* Arquitectura principal
* Modelado orientado a objetos
* Gestión de citas
* Gestión de pacientes
* Historias clínicas
* Estructura modular

---

# Autores

AyLZz (Daniel Ayala), Laura Ramirez, Johan Soto

Proyecto desarrollado como sistema académico y arquitectónico para gestión de un Centro de Salud Comunitario.

---

# Licencia

Este proyecto es de uso académico y educativo.


---

# English Version

## CSC Community Health System

CSC Community Health System is a Java desktop application developed using Object-Oriented Programming (OOP), data structures, and modular software architecture.

The project was created as an academic and architectural system designed to simulate the management processes of a community healthcare center.

---

## Project Description

The system allows organized management of:

* Patients
* Doctors
* Medical appointments
* Clinical histories
* Medical services
* Administrative processes

The application follows good software engineering practices, including layered architecture, modularization, and separation of responsibilities.

---

## Main Objectives

* Apply Object-Oriented Programming concepts.
* Implement data structures in a real-world system.
* Design a scalable and maintainable architecture.
* Organize healthcare information efficiently.
* Simulate the operation of a community healthcare center.

---

## Technologies Used

| Technology          | Purpose                      |
| ------------------- | ---------------------------- |
| Java                | Core system logic            |
| Swing / GUI         | Desktop graphical interface  |
| OOP                 | System modeling              |
| Data Structures     | Internal data management     |
| In-memory storage   | Temporary data persistence   |
| NetBeans            | Development environment      |
| Git & GitHub        | Version control              |

---

## Software Architecture

```text
CSCSaludComunitaria
│
├── Model
├── Services
├── GUI
├── Utilities
└── Main
```

---

## Implemented Features

### Patient Management

* Patient registration
* Information lookup
* Data updates
* Medical history management

### Doctor Management

* Doctor registration
* Specialty administration
* Availability management

### Appointment Management

* Appointment scheduling
* Appointment cancellation
* Schedule consultation
* Doctor-patient relationship management

### Clinical Histories

* Consultation records
* Diagnoses
* Treatments
* Clinical follow-up

### Administration

* Administrative management
* System organization
* Module coordination

---

## Data Management

Currently, the project uses temporary in-memory data storage through data structures and Java objects during execution.

Database persistence is not implemented in this version.

However, the architecture was designed to support future integration with Oracle, MySQL, or PostgreSQL databases.

---

## Graphical User Interface

The application includes a desktop graphical interface designed to improve user interaction and usability.

Features include:

* Modular navigation
* Registration forms
* Visual appointment management
* Intuitive administration panels

---

## Current Project Status

Project under active development.

Current implementation includes:

* Main architecture
* Object-oriented modeling
* Appointment management
* Patient management
* Medical records
* Modular structure
* Graphical interface (GUI)

---

## Authors

AyLZz (Daniel Ayala), Laura Ramirez, Johan Soto

Academic project focused on healthcare system architecture and software engineering.

---

## License

This project is intended exclusively for academic and educational purposes.
