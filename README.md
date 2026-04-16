# 🐶 DogApp - Agenda de Citas para Mascotas

Aplicación móvil desarrollada como parte del curso **Desarrollo de Aplicaciones para Dispositivos Móviles** de la **Universidad del Valle**, enfocada en la gestión de citas para una veterinaria.

---

## 📚 Información General

- **🏫 Universidad:** Universidad del Valle - Sede Cali  
- **🏢 Escuela:** Ingeniería de Sistemas y Computación  
- **👨‍🏫 Docente:** Ing. Walter Medina  
- **📅 Fecha:** Abril 2025  

---

## 📱 Descripción del Proyecto

**DogApp** es una aplicación móvil que permite a un administrador de una veterinaria gestionar citas de mascotas de manera eficiente.  

La app incluye funcionalidades como:
- Autenticación biométrica
- Registro de nuevas citas
- Visualización de citas
- Edición y eliminación de citas
- Consumo de APIs externas para información de razas e imágenes

El enfoque principal es mejorar la experiencia de usuario y facilitar la gestión de pacientes en entornos veterinarios.

---

## 🎯 Objetivos

- Implementar una aplicación móvil nativa funcional
- Aplicar arquitectura moderna (**MVVM**)
- Integrar almacenamiento local con **Room**
- Consumir APIs REST externas
- Diseñar interfaces intuitivas basadas en historias de usuario

---

## 🧩 Funcionalidades Principales

### 🔐 Login con Biometría
- Autenticación mediante huella digital
- Interfaz minimalista con animaciones

### 🏠 Home - Administrador de Citas
- Lista de citas registradas
- Visualización rápida de información relevante
- Acceso a detalles y creación de nuevas citas

### ➕ Crear Nueva Cita
- Registro de:
  - Nombre de la mascota
  - Raza (AutoComplete desde API)
  - Propietario
  - Teléfono
  - Síntomas
- Validación de campos
- Almacenamiento en base de datos local

### 📄 Detalle de Cita
- Visualización completa de la información
- Imagen asociada a la raza
- Opciones de edición y eliminación

### ✏️ Editar Cita
- Modificación de datos existentes
- Persistencia en base de datos

---

## 🛠️ Tecnologías Utilizadas

- **Lenguaje:** Kotlin  
- **Arquitectura:** MVVM + Repository  
- **Base de Datos:** SQLite (Room)  
- **Consumo API:** Retrofit  
- **UI:** XML (Android Views)  
- **Animaciones:** Lottie  
- **Control de versiones:** Git & GitHub  
- **Gestión de proyecto:** Jira  

---

## 🌐 APIs Utilizadas

- 🐕 Lista de razas:  
  https://dog.ceo/api/breeds/list/all  

- 🖼️ Imágenes de perros:  
  https://dog.ceo/api/breeds/image/random  

- 🎬 Animaciones:  
  https://lottiefiles.com  

---

## 🏗️ Arquitectura del Proyecto

El proyecto sigue el patrón **MVVM (Model - View - ViewModel)**:
