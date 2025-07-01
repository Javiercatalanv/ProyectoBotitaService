# ProyectoBotitaService


Botita’s Service

Descripción

Botita’s Service es un sistema de gestión para kioscos de venta, desarrollado con un backend en NestJS y un frontend en React. La aplicación permite la creación de productos, gestión de pedidos, y simulación de pagos. El sistema soporta distintos roles de usuario (administrador, vendedor, comprador, repartidor), y usa Docker para levantar la base de datos PostgreSQL.

Link de Descarga

Enlace de descarga

⸻

Instrucciones para levantar el proyecto

1. Clonar el repositorio

git clone https://github.com/tu-usuario/tu-repo.git
cd tu-repo

2. Levantar la base de datos con Docker

Desde la raíz del proyecto, ejecutar:

docker compose up --build

Esto levantará PostgreSQL y cualquier otro servicio definido en el archivo docker-compose.yml.

3. Levantar el backend

Desde la ruta:

cd BotitasBackendRial

Ejecuta:

npm install
npm run start

4. Levantar el frontend

Desde la ruta:

cd frontend

Ejecuta:

npm install
npm run start


⸻

Credenciales de prueba

Puedes usar los siguientes usuarios para probar la aplicación según sus roles:

Rol	Correo	Contraseña
Seller	vale@gmail.com	123456
Delivery	paaa@gmail.com	123456
Admin	ken@gmail.com	123456
Buyer	botitas@gmail.com	123456


⸻

Notas
	•	Asegúrate de tener Node.js y Docker instalados en tu máquina.
	•	Ejecuta npm install antes de iniciar tanto el frontend como el backend.

⸻

Error Conocido: Métodos de entrega

En el último control de avance, los métodos de entrega (delivery y retiro) estaban funcionando correctamente, pero al agregar los últimos puntos y cambios, los métodos dejaron de funcionar. Actualmente, al intentar agregar un producto al carrito, el sistema no muestra correctamente las opciones de entrega disponibles para el producto. El problema está siendo investigado y se actualizará el sistema una vez se resuelva.

⸻