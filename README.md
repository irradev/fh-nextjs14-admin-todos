# Development

Pasos para levantar la app en desarrollo

1. Levantar la base de datos:

   ```
   docker-compose up -d
   ```

2. Renombrar el .env.template a .env
3. Reemplazar las variables de entorno
4. Instalar dependencias y levantar el proyecto:

   ```
   npm install
   npm run dev
   ```

5. Eejecutar los comandos de prisma:

   ```
   px primsa migrate dev
   npx prisma generate
   ```

6. Ejecutar el SEED para crear la [base de datos local](http://localhost:3000/api/seed)

## Nota: Usuario por defecto

**usuario:** admin@admin.com <br />
**password:** 123456

# Prisma commands

```
npx prisma init
npx primsa migrate dev
npx prisma generate
```

# Prod

# Stage
# fh-nextjs14-admin-todos
