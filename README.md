# Proyecto: Agencia de Viajes - Rama Practicante 🚀

Este repositorio contiene los avances realizados por la **Practicante** en el flujo de trabajo colaborativo de la aplicación móvil "Agencia de Viajes".

## 👤 Información del Desarrollador
* **Nombre:** Liz Villalobos Urbina
* **Rol:** Practicante
* **Carrera:** Ingeniería de Software con IA
* **Institución:** SENATI

## 🛠 Cambios Realizados (Rama: `practicante`)

Se han diseñado e implementado cuatro interfaces clave en Android Studio utilizando `ConstraintLayout` para asegurar la adaptabilidad en diferentes dispositivos:

### 1. Interfaz Principal (`activity_main.xml`)
* Rediseño del título con jerarquía visual.
* Inclusión de imagen representativa (`imgBus`).
* Añadido pie de página con créditos de autoría para identificación en el laboratorio.

### 2. Menú Principal (`activity_menu.xml`)
* Implementación de navegación funcional mediante botones.
* Secciones añadidas: **Ver Destinos**, **Mis Reservas** y **Mi Perfil**.
* Uso de unidades `sp` para accesibilidad de texto.

### 3. Proceso de Reserva (`activity_proceso.xml`)
* Creación de formulario de entrada de datos.
* Campos incluidos: `EditText` para destino y selector de fecha.
* Botón de confirmación con estilo personalizado.

### 4. Módulo de Prueba (`activity_prueba.xml`)
* Implementación de componentes de control como `Switch` y `ProgressBar`.
* Diseñado para testear la lógica de configuración y carga de datos en segundo plano.

## 🚀 Instrucciones para la Integración (Merge)
Para integrar estos cambios a la rama principal:
1. Asegurarse de estar en la rama `main`.
2. Ejecutar `git merge practicante`.
3. Resolver conflictos en caso de cambios simultáneos en los layouts.

---
