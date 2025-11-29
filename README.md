# 📘 Tutorial Paso a Paso: Cómo Levantar el Proyecto (Frontend + Backend + BD)

Este documento explica **paso a paso** cómo levantar el proyecto utilizando **Docker** y **Docker Compose**, incluso si nunca los has usado antes.

---

## ✅ 1. Requisitos Previos

Antes de comenzar, debes tener instalado:

### ✔️ Docker Desktop  
Descargar: https://www.docker.com/products/docker-desktop/  
Instalarlo y **reiniciar el computador** después de la instalación.

### ✔️ Git  
Para descargar el proyecto como ZIP.
DESCARGAR UN EN LINK QUE SE DEJARA, YA QUE SI SE DESCARGA POR SEPARADO CABE LA POSIBILIDAD DE QUE NO SE DESCARGEN TODO LOS ARCHIVOS NESESARIOS

---

## 🧭 2. Abrir Docker Desktop

1. En Windows, abre el menú **Inicio**.
2. Busca **"Docker Desktop"**.
3. Ábrelo.
4. Espera a que aparezca el mensaje **“Docker is running”** o un icono verde en la interfaz.

> ⚠️ No continúes hasta que Docker esté completamente iniciado.

---

## 📂 3. Estructura del Proyecto

El proyecto debe verse así:

project/ <br>
│── back-end/ <br>
│ └── Dockerfile + otros archivos <br>
│── front-end/ <br>
│ └── Dockerfile + otros archivos <br>
│── nginx/ <br>
│ └── (configuración) <br>
│── bd.sql <br>
│── docker-compose.yml <br>
│── README.md <br>


---

## 📁 4. Levantar el proyecto

0. Ir a la ubicacion del proyecto 

### En Windows:

1. Abrir **PowerShell** o **CMD**.
2. Navegar a la carpeta donde está el proyecto:

   cd C:\ruta\donde\esta\el\proyecto

3. Verifica que estás en el lugar correcto:
   
   coloca en la terminal: dir 

Debe aparecer el archivo docker-compose.yml.

4. En la terminal:

   colocar: docker compose up --build

5. Verificar la BD(opcional):

   coloca esto en esa terminal: mysql -h 127.0.0.1 -P 16010 -u root -proot

   y para comprobar que este todo bien: SHOW DATABASES;

6. Para ver el resultado, colocar en el navegador: http://localhost:6060/



