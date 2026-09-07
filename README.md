# Taller 7: Despliegue continuo en PaaS

Repositorio para el Taller 7 (despliegue de la API de `bankchurn` en Railway usando Docker).

## Pendiente antes de empezar

1. Descargar `docker-api-starter.zip` desde el enunciado del taller en la plataforma del curso (no incluido aquí).
2. Descomprimirlo en la raíz de esta carpeta, de forma que queden:
   - `bankchurn-api/`
   - `Dockerfile`
3. Hacer el primer commit con ese contenido y conectar este repo con uno nuevo en GitHub (ver pasos 1-3 del enunciado).

## Flujo del taller

1. Clonar este repo en la instancia EC2.
2. Crear cuenta/proyecto en [Railway](https://railway.app/dashboard) y desplegar desde el repo de GitHub.
3. Generar el dominio público (Networking > Generate Domain) y probar la API en `/docs`.
4. Modificar el título en `bankchurn-api/app/main.py` (agregar el nombre propio), commit + push, y verificar el redeploy automático en Railway.
