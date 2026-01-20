# Guía Completa: Subir a GitHub y conectar con Vercel (Método Manual Web)

Esta guía te explica cómo llevar tus archivos a GitHub manualmente (usando el navegador) y luego conectarlo a Vercel. Este es el método más profesional y seguro.

---

## 📂 Parte 1: Subir archivos a GitHub (Sin comandos)

### 1. Crear el Repositorio
1.  Inicia sesión en [github.com](https://github.com/).
2.  Haz clic en el botón **"+"** (arriba a la derecha) y selecciona **"New repository"**.
3.  **Repository name:** Escribe un nombre (ej: `construccion-cabanas`).
4.  **Public/Private:** Selecciona **Public** (para que Vercel gratuito funcione sin problemas).
5.  **IMPORTANTE:** Marca la casilla **"Add a README file"**. (Esto facilita subir archivos después).
6.  Haz clic en **"Create repository"**.

### 2. Subir tus archivos
1.  En tu nuevo repositorio, haz clic en el botón **"Add file"** y selecciona **"Upload files"**.
2.  Abre la carpeta de tu proyecto en tu computadora (`e:\danilo empresas proyectos\construccion de cabañas`).
3.  **Selecciona TODOS los archivos y carpetas** (index.html, carpeta img, css, etc.) y **arrástralos** dentro del área gris en GitHub.
    *   *Nota: Espera a que carguen todos los archivos en la lista.*
4.  Baja hasta donde dice "Commit changes".
5.  En el cuadro de texto escribe: "Versión inicial".
6.  Haz clic en el botón verde **"Commit changes"**.

✅ *Ahora tus archivos están seguros en la nube de GitHub.*

---

## � Parte 2: Conectar con Vercel

### 1. Importar el proyecto
1.  Inicia sesión en [vercel.com](https://vercel.com/dashboard).
2.  Haz clic en el botón blanco **"Add New..."** y selecciona **"Project"**.
3.  Verás una lista de "Import Git Repository". Busca tu repositorio `construccion-cabanas`.
4.  Haz clic en el botón **"Import"** al lado de tu repositorio.

### 2. Configurar y Desplegar
1.  Te mostrará una pantalla de configuración ("Configure Project").
    *   **Project Name:** Déjalo como está.
    *   **Framework Preset:** Déjalo en "Other" o lo que salga por defecto.
    *   **Root Directory:** Déjalo vacío (puesto que tus archivos están en la raíz).
2.  Haz clic en el botón azul **"Deploy"**.

### 3. ¡Celebrar!
1.  Espera unos segundos mientras Vercel construye tu sitio (verás cohetes y confeti).
2.  Cuando termine, aparecerá una tarjeta con una imagen de tu web.
3.  Haz clic en la imagen o en el botón **"Visit"** para ver tu página online.

---

## 🔄 ¿Cómo actualizo mi página en el futuro?

Si cambiaste algo en tu archivo `index.html` o agregaste fotos:

1.  Ve a tu repositorio en GitHub.com.
2.  Haz clic en **"Add file"** -> **"Upload files"**.
3.  Arrastra SOLO los archivos que modificaste.
4.  Escribe un mensaje (ej: "Actualicé el precio") y dale a **"Commit changes"**.
5.  **¡Listo!** Vercel detectará el cambio automáticamente y actualizará tu página web en segundos. No tienes que hacer nada en Vercel.
