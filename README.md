# Configuração do banco local

```java
        dataSource.setDriverClassName("com.mysql.cj.jdbc.Driver");
        dataSource.setUrl("jdbc:mysql://127.0.01:3306/onhome");
        dataSource.setUsername("OnHome");
        dataSource.setPassword("adminonhome@");
```

### Crie um usuário no mysql com o seguinte comando: 
*** Entre no usuário root.
```mysql
CREATE USER 'OnHome'@'127.0.01' IDENTIFIED BY 'adminonhome@';
```

### Conceda todos os provilégios para esse usuário, com o comando:

```mysql
GRANT ALL PRIVILEGES ON * . * TO 'OnHome'@'127.0.01';
```

### Para que as mudanças tenham efeito, com o comando:

```mysql
FLUSH PRIVILEGES;
```

# Pronto para executar o arquivo .jar
