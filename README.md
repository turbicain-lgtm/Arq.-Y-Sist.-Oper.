# Arquitectura y Sistemas Operativos 

Este repositorio contiene el proyecto final desarrollado para la materia **Arquitectura y Sistemas Operativos**. 

El núcleo del proyecto consiste en el despliegue de un entorno de ejecución basado en **Node-RED** utilizando **Docker**. Este entorno está configurado para automatizar tareas, procesar datos y simular/controlar flujos de integración, garantizando la persistencia de datos.


## Precondiciones

* [Docker](https://www.docker.com/) instalado y corriendo.

* **Git** para clonar el repositorio.

## Paso a Paso para instalar y ejecutar 
1) clonar este repositorio
2) Parado sobre el raiz del repositorio clonado ejecutar:
    ```bash
    docker compose up -d
    ```
3) Para acceder a la interfaz, ingresár a `http://localhost:1880/ui` en tu navegador.





## Estructura del Repositorio

A continuación se detalla la organización de los archivos principales para levantar el proyecto:

```text
    ├── node_red_data/          # Directorio mapeado para el Node-RED
    │   └──  flows.json         # Flujos de Node-RED exportados
    └── docker-compose.yml      # Archivo para el arranque del docker 

```
