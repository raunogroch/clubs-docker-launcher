<center>
# Clubs Docker Launcher
</center>

## Dev

1. Clonar repositorio
2. Clonar microservicios en el directorio actual
3. Crear un archivo `.env` con las variables de entorno basado en el `.env.example`

## Stages

- Para trabajar en modo local y en desarrollo ejecutar el siguiente comando:

```
docker-compose up -d --build
```

- Para trabajar en modo produccion ejecutar el siguiente comando:

```
docker-compose -f docker-compose.prod.yaml up -d --build
```
