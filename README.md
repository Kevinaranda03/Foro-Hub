Foro creado con Java 
Configuración e Instalación
Prerrequisitos
JDK 17
Maven 3.8+
MySQL 8.0+
Pasos
Clonar el repositorio:
git clone https://github.com/castleortiz1/Challenge-ForoHub-AluraLatam
cd forohub
Configurar la base de datos:
Crear una base de datos en MySQL.
Actualizar las credenciales en el archivo application.properties:
spring.datasource.url=jdbc:mysql://localhost:3306/forohub
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña
Compilar y ejecutar la aplicación:
mvn clean install
mvn spring-boot:run
Acceder a la documentación de la API en: http://localhost:8080/swagger-ui.html
