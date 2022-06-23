★ Proyecto para un ecomerce de comidas rapidas
★ Para correr el proyecto es necesario:
1. Tener MySql server activado 
2. npm install
3. crear un archivo .env que tenga las variables de entorno con este formato:
    DB_USER_DEV="(InsertarUsuarioPropioDe MySQL)"
    DB_PASSWORD_DEV="(InsertarContraseñaDe MySQL)"
    DB_DATABASE_DEV="(InsertarnombreDeLaDB en MySQL)"
    DB_HOST_DEV= "(InsertarHostDeMySQL)"
    DB_DIALECT="mysql"
4. En el proyecto estan dos archivos .sql con las sentencias de creación de la Bd; entrar a MYSQL, abrir dichos archivos y ejecutarlos para crear la Bd de pruebas
5. Una vez realizado todo lo anterior correr "npm run dev" para ejecutar nodemon con las variables de entorno (verificar si está instalado nodemon en npm)
