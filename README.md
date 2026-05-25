# Final Project: Log Analytics with PySpark on Docker Swarm

## Descripción
Sistema de análisis de logs con arquitectura distribuida usando Docker Swarm y PySpark.

## Requisitos
- Docker Engine
- Git

## Despliegue
```bash
git clone https://github.com/jhoanstesuarez-beep/final-project.git
cd final-project
docker-compose up -d
API Endpoints
Enviar evento
curl -X POST http://localhost:5001/event -H "Content-Type: application/json" -d '{"page":"home","user_id":"usuario1"}'
Ver estadísticas
curl http://localhost:5002/stats
Componente PySpark
Procesa datos cada 5 minutos

Lee de raw_events

Calcula total de visitas y usuarios únicos por página

Tecnologías
Docker Swarm

PySpark

PostgreSQL

Flask
Autores
Jhoan Suárez y Daniel Brand

