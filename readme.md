# Aplicação de aula sobre Java
aplicando conceitos na tela de notas

## Tecnologias 

* java 20
* javafx
* Postgressql

| Coluna 1 | Coluna 2  |
|----------|-----------|
| valor    | valor 2   |


´´´  java

public class ConexaoDataBase {

    private Connection conn = null;
    public synchronized Connection getConexao() throws SQLException {
        if (conn == null){
            conn = DriverManager.getConnection("jdbc:postgresql://localhost:5432/ecomerce", "postgres" , "postgres");
        }
        return conn;

    }
´´´







