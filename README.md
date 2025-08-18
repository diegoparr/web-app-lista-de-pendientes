Aquí tienes las instrucciones para tu archivo `README.md` con el enlace a tu repositorio. Simplemente copia y pega este texto y reemplaza los marcadores de posición si es necesario.

## **Cómo ejecutar el proyecto 🚀**

Sigue estos pasos para poner en marcha el proyecto en tu máquina local.

-----

### **1. Clonar el repositorio**

Abre la terminal y clona el proyecto con el siguiente comando:

```bash
git clone https://github.com/diegoparr/web-app-lista-de-pendientes.git
```

-----

### **2. Configurar el entorno virtual**

Dirígete a la carpeta del proyecto y crea un entorno virtual para aislar las dependencias:

```bash
cd web-app-lista-de-pendientes
python -m venv venv
```

-----

### **3. Activar el entorno virtual**

Activa el entorno virtual según tu sistema operativo:

**En Windows:**

```bash
venv\Scripts\activate
```

**En macOS o Linux:**

```bash
source venv/bin/activate
```

-----

### **4. Instalar las dependencias**

Instala todas las librerías necesarias para el proyecto usando el archivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

-----

### **5. Ejecutar la base de datos (Django)**

Ejecuta las migraciones para crear la base de datos:

```bash
python manage.py makemigrations
python manage.py migrate
```

-----

### **6. Iniciar el servidor**

Finalmente, inicia el servidor de desarrollo para ver la aplicación:

```bash
python manage.py runserver
```

Una vez que el servidor esté activo, podrás acceder a la aplicación en la siguiente dirección:

```
http://127.0.0.1:8000/
```
