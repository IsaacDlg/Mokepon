# Mokepon

Mokepon es un juego de batalla de mascotas multijugador en línea que permite a los jugadores seleccionar una mascota, moverse por un mapa y luchar contra otros jugadores.

## Características

- **Selección de Mascotas**: Elige entre Hipodoge, Capipepo y Ratigueya.
- **Mapa Interactivo**: Mueve tu mascota por el mapa para encontrar enemigos.
- **Multijugador**: Conéctate y lucha contra otros jugadores en tiempo real.
- **Sistema de Batalla**: Elige ataques (Fuego, Agua, Tierra) y compite estratégicamente.

## Tecnologías Utilizadas

- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Backend**: Node.js, Express
- **Comunicación**: Fetch API para peticiones HTTP

## Instalación y Uso

1.  **Clonar el repositorio** (si aplica) o descargar los archivos.
2.  **Instalar dependencias**:
    Abre una terminal en la carpeta del proyecto y ejecuta:
    ```bash
    npm install
    ```
3.  **Iniciar el servidor**:
    ```bash
    node index.js
    ```
    El servidor se iniciará en el puerto 8080 (o el configurado).
4.  **Jugar**:
    Abre tu navegador y ve a `http://localhost:8080` (o la IP de tu red local si juegas desde otro dispositivo).

## Estructura del Proyecto

- `index.js`: Servidor principal (Express).
- `public/`: Archivos estáticos del frontend.
  - `mokepon.html`: Estructura HTML del juego.
  - `mokepon.js`: Lógica del juego en el cliente.
  - `style.css`: Estilos del juego.
  - `img-mokepon/`: Imágenes de las mascotas y el mapa.

## Créditos

Desarrollado como parte del curso de programación básica de Platzi.
