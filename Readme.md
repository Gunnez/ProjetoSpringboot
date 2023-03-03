## Projeto web usando java springboot
#
Este projeto faz com que requisições JSON possam ser usadas para se conseguir informações de um banco de dados ou adicionar algo no mesmo banco de dados, foi usado o banco H2 para fazer esses testes, segue o url a ser para requisições <br><br>
Para se conseguir todos os usuarios na tabela Users use:

    http://localhost:8080/users 

Para buscar um usuario especifico usando seu id use:
    
    http://localhost:8080/users/{id}  

Para adicionar um usuario é necessario mandar um arquivo json para a seguinte url:

    http://localhost:8080/users

Eu usei o programa Postman para conseguir mandar os arquivos json para essa url.<br>

Esse projeto foi feito como uma introdução a framework spring, ainda não sei tudo sobre essa framework mas esse exercicio me ajudou a ter uma grande noção doque é uma framework, como funciona e oque eu posso fazer usando ela. 