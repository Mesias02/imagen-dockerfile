### 1. Título
Generación de Imagen Docker a partir de una Aplicación React

### 2. Tiempo de duración
El tiempo estimado para completar este procedimiento fue de 120 minutos.

### 3. Fundamentos
## Docker y Contenerización
Docker permite encapsular aplicaciones en contenedores, garantizando un entorno consistente y aislado. La construcción de una imagen Docker para una aplicación React implica definir un Dockerfile, donde se especifican las dependencias y configuraciones necesarias para el despliegue.

![image](https://github.com/user-attachments/assets/dd3b44bd-a480-43aa-b1e2-50c76cd13bb1)

## Creación de Imágenes en Docker
Una imagen Docker es una plantilla inmutable que se utiliza para crear contenedores. Se construye a partir de un Dockerfile, el cual contiene instrucciones sobre la configuración de la aplicación.

![image](https://github.com/user-attachments/assets/eea1cea8-a69b-4ced-baf7-fbf51a8ca92e)

## Backend Simulado
Para que el frontend React funcione correctamente, es necesario contar con un servicio backend simulado, que actúa como API y proporciona los datos de prueba necesarios.

![image](https://github.com/user-attachments/assets/43760a1d-52b2-467e-8236-cf2492380452)


## Dockerfile
Un Dockerfile es un archivo de texto que contiene una serie de instrucciones que Docker sigue para construir una imagen. Estas instrucciones incluyen la definición de la imagen base, la instalación de dependencias, la copia de archivos y la configuración del entorno de ejecución. Es fundamental para la contenerización de aplicaciones, ya que permite la automatización del proceso de construcción y despliegue.

![image](https://github.com/user-attachments/assets/34ac3adc-5230-4e56-8392-e3b88e482946)


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
Clonar el repositorio del frontend.

![image](https://github.com/user-attachments/assets/356cac52-6a27-4c31-bda8-18ac500edb68)

Instalar las dependencias. 

![image](https://github.com/user-attachments/assets/a08d4ccd-9088-4aa2-82cb-9eeb7454fae0)

Ejecutar la aplicación localmente para verificar que funciona correctamente. 

![image](https://github.com/user-attachments/assets/4f7ee601-6546-4434-befb-584fb654eea7)

Acceder desde el navegador a http://localhost:3000 y validar que la interfaz carga correctamente. 

![image](https://github.com/user-attachments/assets/d81737d8-510f-464f-8d64-6f4f317670e2)

Parte 2: Crear el Dockerfile y generar la imagen
Crear un archivo Dockerfile en la raíz del proyecto. 

![image](https://github.com/user-attachments/assets/cf8e7665-31a1-4651-9d9a-0c361ba22e98)

Construir la imagen Docker. 

![image](https://github.com/user-attachments/assets/fa105dba-e4b1-4409-963c-b4f41d287e77)

Verificar que la imagen fue creada correctamente.

![image](https://github.com/user-attachments/assets/8d53be43-2d3b-4fa4-b427-a8cbb16bfd64)

Validar localhost http://localhost:3000/classmates/18

![image](https://github.com/user-attachments/assets/0315bf56-7463-4894-9fad-a9ece31a9c23)

![image](https://github.com/user-attachments/assets/d57d142c-ee5a-4d90-9645-cf5d6d7ee838)

Cambiar el localhost a 8000

![image](https://github.com/user-attachments/assets/1d0a232d-b2b5-439b-83fe-d04ec9653586)

Validar  localhost 8000

![image](https://github.com/user-attachments/assets/3b5a8a19-4685-411e-8b10-95df83cb8917)

![image](https://github.com/user-attachments/assets/ace68b4e-0cf7-42f3-a8bf-454f6d05c30b)

### 9. Resultados esperados
Al completar la práctica, se logró contenerizar exitosamente la aplicación React y generar una imagen Docker funcional. La aplicación frontend pudo ejecutarse tanto en el entorno local como en un contenedor Docker, manteniendo su correcto funcionamiento al integrarse con el backend simulado. Se verificó la conectividad entre el frontend y la API, garantizando una implementación efectiva del proceso de despliegue con Docker.

### 10. Bibliografía
Documentación oficial de Docker

Guía de despliegue de React

Repositorio de frontend

Repositorio de backend simulado

Referencia de Dockerfile
