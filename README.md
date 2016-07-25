# [SwaggerGen](https://github.com/minichen2000/SwaggerGen)
[SwaggerGen](https://github.com/minichen2000/SwaggerGen) uses (Swagger codegen)(https://github.com/swagger-api/swagger-codegen) to generate java Client/Server libraries(based on Jersey2.x).

# How to generate
- Clone the project.
- Replace **swagger.json** with yours.
- Edit **config_ctrl_adp_client.json** and **config_ctrl_adp_server.json** as you want.
- Then:
````
mvn package
cd gen/ctrl_adp_server
mvn install
cd ../ctrl_adp_client
mvn install
````
- You will have the Client/Server libraries(jars) in sub-target directories and your local maven reponsitary.
