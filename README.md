# 📘 Tutorial Paso a Paso: Cómo Levantar el Proyecto (Frontend + Backend + BD)

Este documento explica **paso a paso** cómo levantar el proyecto utilizando **Docker** y **Docker Compose**, incluso si nunca los has usado antes.

---

## ✅ 1. Requisitos Previos

Antes de comenzar, debes tener instalado:

### ✔️ Docker Desktop  
Descargar: https://www.docker.com/products/docker-desktop/  
Instalarlo y **reiniciar el computador** después de la instalación.

### ✔️ Git  
Opcional si descargaste el proyecto como ZIP.

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

project/
│── back-end/
│ └── Dockerfile + otros archivos
│── front-end/
│ └── Dockerfile + otros archivos
│── nginx/
│ └── (configuración)
│── bd.sql
│── docker-compose.yml
│── README.md


---

## 📁 4. Ubicarse en la carpeta del proyecto

### En Windows:

1. Abrir **PowerShell** o **CMD**.
2. Navegar a la carpeta donde está el proyecto:

cd C:\ruta\donde\esta\el\proyecto

3. Verifica que estás en el lugar correcto:
   
dir

Debe aparecer el archivo docker-compose.yml.

4.En la terminal:

   docker compose up --build


