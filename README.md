# spring-deploy
## Despliegue de apps Sprig boot en Heroku
creear archvi system.properties en la carpeta general del proyecto. Con la versión de java que estamos utilizando. `java.runtime.versio=17`
1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el ordenador:
    1. git config --global user.name "Ruin11"
    2. git config --global user.email "emilio_007_005@hotmail.com"
3. Subir el proyecto a github desde la propia herramienta: vcs en itelij idea > Share proyect on github.
4. Desde Heroku, crear app y elegir método github y buscar el repositorio subido.
5. Habilitar deploy automatico y ejecutar el deploy.

## Proveedores Cloud

* Herouku -- java, spring, PostgreSQL
* Netlify -- Frontend (React, Angular)
* Vercel -- Frontend (React, Angular)
