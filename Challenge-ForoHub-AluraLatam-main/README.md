Foro Desarrollado en Java 

### **Prerrequisitos**
- JDK 17
- 
- Maven 3.8+
- 
- MySQL 8.0+
- 

### **Pasos**


1. Configurar la base de datos:

2. 
   - Crear una base de datos en MySQL.
   - 
   - Actualizar las credenciales en el archivo `application.properties`:
   - 
     ```properties
     
     spring.datasource.url=jdbc:mysql://localhost:3306/forohub
     
     spring.datasource.username=tu_usuario
     
     spring.datasource.password=tu_contraseña
     
     ```
3. Compilar y ejecutar la aplicación:
 
   ```bash
   
   mvn clean install
   
   mvn spring-boot:run
   
   ```
4. Acceder a la documentación de la API en:
   
   [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)

---
