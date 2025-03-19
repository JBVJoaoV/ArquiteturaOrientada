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

No terminal do primeiro endpoint, digitar, SELECT*FROM PRODUTOS;

Jogar o segundo endpoint no GET do postman
Depois troca pra POST
Depois ir em Body, raw e mudar para JSON
Cria o produto e depois da um SEND

Depois, para atualizar, usar o PUT e botar o id na URL, assim como no DELETE: http://localhost:8080/produtos/5
