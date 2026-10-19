# Prácticas de Docker Compose

Autor: Mateo Castellanos Romero

## Descripción

- Práctica 1: página web personalizada con Nginx.
- Práctica 2: WordPress con base de datos MySQL.

## Ejecución

Ejecutar estos comandos desde la carpeta de cada práctica.

Iniciar:
```bash
docker compose up -d
```

Comprobar los contenedores y puertos:
```bash
docker compose ps
```

Acceder desde el navegador a http://localhost:8080.
En WordPress, completar la instalación en el primer acceso.

Detener antes de ejecutar la otra práctica:
```bash
docker compose down
```

## Evidencias

- Capturas de la web y del contenedor.
- Capturas de WordPress instalado y de los dos servicios.

Cada carpeta contiene `captura1.png` y `captura2.png`.