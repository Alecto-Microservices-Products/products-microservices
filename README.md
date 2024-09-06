# Product Microservice


## Dev
1. Clonar el respositorio
2. Instalar las dependencias
3. Crear un archivo `.env` basado en el `env.template`
4. Ejecutar migracion de prisma `npx prisma migrate dev`
5. Ejecutar `npm run start:dev`



## PROD
Ejecutar
```
docker build -f dockerfile.prod -t client-gateway .
```