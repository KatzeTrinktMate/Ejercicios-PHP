# Ejercicios-PHP
Repositorio para guardar ejercicios de php en bachillerato en 2025
El repositorio consiste en dos partes, algunos ejercicios están hechos con bases de datos y otros no lo tienen.     <img src="https://i.pinimg.com/originals/93/25/4d/93254db425f0b9550179ac0f7b7d9030.gif" alt="elefant" width="50" height="50">

## Proyectos con base de datos
### Requisitos
- [Docker](https://docs.docker.com/get-docker/) instalado (incluye `docker compose`)
### Cómo ejecutarlos
1. Abrí una terminal y entrá a la carpeta del proyecto:
`cd con_base_de_datos/<nombre-del-proyecto>
`
2. Levantá los contenedores:
  `docker compose up`
3. Esperá a que termine de arrancar y abrí en el navegador la URL de la tabla de abajo.
4. Para detenerlo, presioná `Ctrl + C` y después:
`
   docker compose down
`
### URLs de cada proyecto
| Proyecto    | Qué hace          | URL                                       |
| ----------- | ----------------- | ----------------------------------------- |
| Login       | <una línea>       | http://localhost:8080/<frontend/index.php?> |
| ParcialUno  | <una línea>       | http://localhost:8082                     |

- **Nota:** si los puertos no coinciden, corré `docker ps` y mirá la columna
- `PORTS`. En una línea como `0.0.0.0:8080->80/tcp`, el número de la
- izquierda (8080) es el que va en la URL.

## Proyectos sin base de datos
 * Para los proyectos en la carpeta sin_base_de_datos puedes usar un entornos de desarrollo local para ejecutar el index.php. También puedes usar la linea de comandos, yendo a la carpeta del ejercicio y con el comando `php -S localhost:PUERTO` y en el navegador escribe http://localhost:8000/index.php (tienes que buscar el archivo que por lo general es index.php).
