# Plataforma Web de Reserva de Horas Médicas - Proyecto DevOps

Servicio web estático ejecutado localmente con **Docker**, **Docker Compose** y **Nginx** (`nginx:alpine`).

## Ejecución Local
1. Levantar servicio: `docker compose up -d --build`
2. Verificar estado: `docker compose ps`
3. Abrir navegador en: `http://localhost:8080`
4. Revisar logs y métricas: `docker logs reserva-horas-medicas` y `docker stats --no-stream`
5. Detener servicio: `docker compose down`
