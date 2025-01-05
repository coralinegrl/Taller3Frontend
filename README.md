# Taller3Frontend

Este proyecto contiene el frontend para el Taller 3 de la asignatura de Arquitectura de Sistemas. Está diseñado para demostrar las capacidades de integración y despliegue continuo (CI/CD) utilizando Firebase Hosting y GitHub Actions.

## Descripción

El frontend está desarrollado con React y configurado para desplegarse automáticamente en Firebase Hosting mediante GitHub Actions cada vez que se hace push a la rama principal.

## Características

- **Despliegue Automático**: Configuración de CI/CD con GitHub Actions.
- **React**: Uso de React para la construcción del interfaz de usuario.
- **Firebase Hosting**: Hospedaje y manejo del frontend en Firebase.

## Prerrequisitos

Antes de comenzar, asegúrate de tener instalado:
- [Node.js](https://nodejs.org/en/) versión 14 o superior.
- NPM (se incluye con Node.js).
- [Git](https://git-scm.com/).

## Configuración Local

Sigue estos pasos para configurar el proyecto localmente:

1. **Clonar el Repositorio**:
   ``
   git clone https://github.com/tu-usuario/Taller3Frontend.git
   cd Taller3Frontend
   ``
2. Instalar Dependencias:
   ``
   npm install
   ``
3. Ejecutar el Proyecto:
   ``
   npm start
   ``

   Accede a la aplicación en http://localhost:3000.

   ## Despliegue

   Para desplegar este proyecto manualmente en Firebase Hosting:
1. Configura Firebase CLI:
   ``
   firebase login
   ``
2. Construye la Aplicación:
   ``
   npm run build
   ``
3. Despliega en Firebase Hosting:
   ``
   firebase deploy --only hosting
   ``

Contribuciones
Para contribuir al proyecto:

Haz fork del repositorio.
Crea una nueva rama para cada característica o mejora.
Realiza tus cambios.
Envía un pull request desde tu fork hacia la rama principal del repositorio original.
