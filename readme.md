### 1. Título
Generación de Imagen Docker a partir de una Aplicación React

### 2. Tiempo de duración
El tiempo estimado para completar este procedimiento fue de 120 minutos.

### 3. Fundamentos
Docker y Contenerización
Docker permite encapsular aplicaciones en contenedores, garantizando un entorno consistente y aislado. La construcción de una imagen Docker para una aplicación React implica definir un Dockerfile, donde se especifican las dependencias y configuraciones necesarias para el despliegue.

Creación de Imágenes en Docker
Una imagen Docker es una plantilla inmutable que se utiliza para crear contenedores. Se construye a partir de un Dockerfile, el cual contiene instrucciones sobre la configuración de la aplicación.

Backend Simulado
Para que el frontend React funcione correctamente, es necesario contar con un servicio backend simulado, que actúa como API y proporciona los datos de prueba necesarios.

Dockerfile
Un Dockerfile es un archivo de texto que contiene una serie de instrucciones que Docker sigue para construir una imagen. Estas instrucciones incluyen la definición de la imagen base, la instalación de dependencias, la copia de archivos y la configuración del entorno de ejecución. Es fundamental para la contenerización de aplicaciones, ya que permite la automatización del proceso de construcción y despliegue.

### 4. Conocimientos previos
Para llevar a cabo este procedimiento, se requiere:

Conocimientos básicos en Docker y la creación de imágenes.

Familiaridad con React y administración de dependencias en package.json.

Uso de comandos básicos de Docker (docker build, docker run, docker-compose).

Experiencia con configuración de backend y API.

### 5. Objetivos a alcanzar
Clonar el repositorio de la aplicación React.

Ejecutar la aplicación localmente y verificar su correcto funcionamiento.

Construir un Dockerfile que permita contenerizar la aplicación.

Generar una imagen Docker basada en la aplicación React.

Crear un contenedor a partir de la imagen generada.

Asegurar la conectividad entre el frontend y el backend simulado.

### 6. Equipo necesario
Computador con Docker instalado.

Acceso a internet para clonar el repositorio.

Editor de código (VS Code, IntelliJ, etc.).

Terminal o consola de comandos.

### 7. Material de apoyo
Documentación oficial de Docker.

Documentación de React sobre despliegue en contenedores.

Guías sobre configuración de imágenes y contenedores.

Cheatsheet de comandos Docker.

Videos tutoriales sobre Dockerfile y contenerización.

### 8. Procedimiento
Parte 1: Clonar el repositorio y ejecutar la aplicación
Clonar el repositorio del frontend. (Captura de pantalla aquí)

Instalar las dependencias. (Captura de pantalla aquí)

Ejecutar la aplicación localmente para verificar que funciona correctamente. (Captura de pantalla aquí)

Acceder desde el navegador a http://localhost:3000 y validar que la interfaz carga correctamente. (Captura de pantalla aquí)

Parte 2: Crear el Dockerfile y generar la imagen
Crear un archivo Dockerfile en la raíz del proyecto. (Captura de pantalla aquí)

Construir la imagen Docker. (Captura de pantalla aquí)

Verificar que la imagen fue creada correctamente. (Captura de pantalla aquí)

Parte 3: Ejecutar el contenedor y conectar con el backend
Clonar el repositorio del backend simulado. (Captura de pantalla aquí)

Ejecutar el backend simulado. (Captura de pantalla aquí)

Ejecutar el contenedor del frontend. (Captura de pantalla aquí)

Validar que la aplicación puede conectarse al backend y recuperar datos. (Captura de pantalla aquí)

### 9. Resultados esperados
Al completar la práctica, se logró contenerizar exitosamente la aplicación React y generar una imagen Docker funcional. La aplicación frontend pudo ejecutarse tanto en el entorno local como en un contenedor Docker, manteniendo su correcto funcionamiento al integrarse con el backend simulado. Se verificó la conectividad entre el frontend y la API, garantizando una implementación efectiva del proceso de despliegue con Docker.

### 10. Bibliografía
Documentación oficial de Docker

Guía de despliegue de React

Repositorio de frontend

Repositorio de backend simulado

Referencia de Dockerfile