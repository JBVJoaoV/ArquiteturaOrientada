Codigo dado em aula que sera usado como base para o cp

Executar os comandos nessa ordem:
java -version
mvn -version
mvn clean install
mvn spring-boot:run


Depois, no navegador, perquisar os endpoints:
http://localhost:8080/h2-console

Colocar jdbc:h2:mem:testdb, no espaço JDBC URL:

Segundo endpoint:
http://localhost:8080/produtos
