# CANINOS SABS

## 📋 Descripción

Este es un proyecto desarrollado para la empresa **Caninos SABS**, que permite un manejo completo y eficiente de la información empresarial mediante una aplicación web con frontend y backend separados.


## 🛠️ Tecnologías utilizadas

- **Node.js**
- **Express**
- **MySQL**


---


## 🚀 Instalación del proyecto

### 1. Clonar el repositorio

Primero, crea una carpeta en tu sistema donde alojarás la API.

```bash
git clone https://github.com/JuanLondono01/CaninosFront.git](https://github.com/JuanLondono01/CaninosAPI.git
```

---


## ⚙️ Configuración

### 🔧 Backend (API - `server`)

1. Accede a la carpeta del servidor:

   ```bash
   cd server
   ```

2. Instala las dependencias:

   ```bash
   npm install
   ```

3. Configura las variables de entorno creando un archivo `.env` con los siguientes datos (ejemplo):

   ```env
   PORT=5000
   DB_HOST=localhost
   DB_USER=root
   DB_PASSWORD=tu_contraseña
   DB_NAME=caninos_sabs
   ```

4. Ejecuta el servidor:

   ```bash
   npm start
   ```

---


## ⚠️ Notas importantes

- Si el frontend no puede acceder a la API, asegúrate de configurar correctamente CORS:
  
  1. Abre el archivo `server/app.js`.
  2. Busca la configuración de `cors()`.
  3. Asegúrate de permitir la URL desde la que estás ejecutando el frontend (ej. `http://localhost:5173`).

- Para editar las variables de entorno de la API desplegada en railway.com
  1. Entrar al proyecto de la API
  2.   Dar click en Variables
  3.   Editar o agregar las que sean necesarias
