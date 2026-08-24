# 🛒 Tienda Online - Proyecto Full-Stack

Una aplicación web construida con Flask y PostgreSQL para la gestión y venta de productos físicos, digitales y perecibles. Incluye carrito de compras, sistema de autenticación, gestión de roles (Administrador y Cliente), subida de imágenes y un diseño moderno responsivo con modo oscuro.

## 🛠️ Instrucciones de Instalación y Ejecución

1. **Clonar el repositorio:**
   ```bash
   git clone 
   cd tienda_online

2.Crear y activar el entorno virtual:
	python -m venv venv
	# En Windows:
	venv\Scripts\activate
	# En Mac/Linux:
	source venv/bin/activate

3.Instalar las dependencias:
	pip install -r requirements.txt

4.Configurar variables de entorno:
Crea un archivo .env en la raíz del proyecto e incluye tus credenciales de PostgreSQL (y tu SECRET_KEY de Flask).

5.Inicializar la base de datos:
	python init_db.py

6.Ejecutar la aplicación:
	python app.py
La aplicación estará disponible en http://localhost:5000

7.Credenciales de Prueba

Para evaluar la aplicación, puedes utilizar las siguientes cuentas precargadas:

Usuario Administrador:

Email: admin@tienda.com (Cámbialo por el tuyo de prueba)

Contraseña: admin123

Usuario Cliente:

Email: cliente@tienda.com (Cámbialo por el tuyo de prueba)

Contraseña: cliente123

Imágenes 
Catálogo de productos
![image alt](https://github.com/AxelMasache/tienda_online/blob/36e35f2fa2b2b9d6189b31827b822648371deb3b/Catalogo_TiendaOnline_Masache_Axel.png)

Ver Detalle producto
 ![image alt](https://github.com/AxelMasache/tienda_online/blob/a35d20edb9ad27f696cfeb92d1998ecbb002d4ed/Ver_Detalle_Producto_Masache_Axel.png)

Agregar Carrito
![image alt](https://github.com/AxelMasache/tienda_online/blob/43112bb4bd7ba8a569c008819d486e29f94fb33f/Agregar_Carrito_Masache_Axel.png)

Mi Carrito
![image alt]()
