# the_restaurant

Proyecto para restaurante el cual debera realizar un pedido y seleccionar una receta aleatoria de las 6 disponibles

Tiene control de ingredientes en la bodega, la cual inicia con una cantidad de 5, si se queda sin ingredientes debera ir a la plaza de mercado y comprar

La plaza de mercado tiene un historial de compras

## Setup

# Clonamos el repositorio con sus submodulos
- git clone --recurse-submodules https://github.com/JuanGuauque/the_restaurant.git
- cd the_restaurant

# Creamos los contenedores con las imagenes y la base de datos
- docker-compose up --build

# Entramos a la aplicacion
- Ingresamos mediante http://localhost:3004