# Frequentused

@CrossOrigin(allowCredentials = "false",allowedHeaders =  "*",
origins = "*",methods = {RequestMethod.GET,RequestMethod.POST,
		RequestMethod.PUT,RequestMethod.DELETE} )

   "styles": [
              "node_modules/bootstrap/dist/css/bootstrap.css",
              "src/styles.css"
            ],
            "scripts": [
               "node_modules/bootstrap/dist/js/bootstrap.js"
            ]
            
  spring.datasource.driver-class-name = com.mysql.cj.jdbc.Driver
spring.datasource.url = jdbc:mysql://localhost:3306/food
spring.datasource.username = root
spring.datasource.password  = root@39

spring.jpa.hibernate.ddl-auto = update
spring.jpa.show-sql = true
#spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQLDialect

server.port = 8082

npx ng g guard Auth 
