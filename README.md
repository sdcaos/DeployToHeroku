# Deploy a Heroku

## Objeto del documento

Describir el proceso para deplegar a producción en [Heroku](https://www.heroku.com/) + [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) una aplicación de [ExpressJS](https://expressjs.com/).

## Objetivo del deploy

**Base de datos**: hacer el paso a producción de la base de datos local a una base de datos remota en MongoDB Atlas:
  1. Realizar el registro en MongoDB Atlas y crear la base de datos remota (stage 1)
  2. Exportar los datos de la base de datos local e importaros en la base de datos remota (stage 2)
  
**Servidor**: hacer el paso a producción de la aplicación de servidor local a una aplicación remota en Heroku:
  1. Realizar el registro en Heroku y crear la aplicación remota (stage 3)
  2. Transferir los archivos de la aplicación local a la aplicaciónn remota (stage 4)


## Fases de paso a producción

- Stage 1: [Registro en MongoDB Atlas y configuración base](https://github.com/sdcaos/DeployToHeroku/blob/main/stage1.md)
- Stage 2: [Paso a producción: base de datos](https://github.com/sdcaos/DeployToHeroku/blob/main/stage2.md)
- Stage 3: [Registro en Heroku y creación de aplicación para servidor](https://github.com/sdcaos/DeployToHeroku/blob/main/stage3.md)
- Stage 4: [Paso a producción: servidor](https://github.com/sdcaos/DeployToHeroku/blob/main/stage4.md)
# DeployToHeroku
