# meli-demo

## Instalación

- Descargar submodulos:

`git submodule update --recursive --remote`

- Crear archivo `.env`

`cp .env.example .env`

- Construir contenedores de docker:

`docker-compose build`

- Correr contenedores

`docker-compose up [servicios]`

Si se quiere correr solamente el servicio de _movies_ junto a su motor de base de datos:

- `docker-compose up -d movies mongodb`

Si se quiere correr solamente el servicio de _users_:

- `docker-compose up -d users postgres`