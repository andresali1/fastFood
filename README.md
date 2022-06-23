★ Proyecto para un ecomerce de comidas rapidas

★ Para correr el proyecto es necesario:
1. Tener MySql server activado 
2. npm install
3. crear un archivo .env que tenga las variables de entorno con este formato:
   
    DB_USER_DEV="(InsertarUsuarioPropioDe MySQL)"
    
    DB_PASSWORD_DEV="(InsertarContraseñaDe MySQL)"
    
    DB_DATABASE_DEV="(InsertarnombreDeLaDB en MySQL)" -> preferiblemente dejar el mismo nombre con el que se crea en el archivo structure.sql
    
    DB_HOST_DEV= "(InsertarHostDeMySQL)"
    
    DB_DIALECT="mysql"
    
4. En éste repositorio estan dos archivos .sql llamados structure.sql y data.sql con las sentencias de creación de la Bd e inserción de datos; entrar a MYSQL, abrir dichos archivos y ejecutarlos para crear la Bd de pruebas
5. Una vez realizado todo lo anterior correr "npm run dev" para ejecutar nodemon con las variables de entorno (verificar si está instalado nodemon en npm)


★ Por el momento se puede ver el ambiente de desarrollo en heroku en el siguiente link para probar todas las funcionalidads (register, login, añadir a carrito, entre otras)

○ http://fast-food-dh.herokuapp.com/
