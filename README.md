# Configuração do banco local

**Configurações do banco local:**

```java
        dataSource.setDriverClassName("com.mysql.cj.jdbc.Driver");
        dataSource.setUrl("jdbc:mysql://localhost:3306/onhome");
        dataSource.setUsername("onhome");
        dataSource.setPassword("******"); //Senha no planner do Projeto.
```

**Configurações do banco azure:**

```java
        dataSource.setDriverClassName("com.microsoft.sqlserver.jdbc.SQLServerDriver");
        dataSource.setUrl("jdbc:sqlserver://onhomesolutions.database.windows.net:1433;database=onHome;user=AdminOnHome@onhomesolutions;password={your_password_here};encrypt=true;trustServerCertificate=false;hostNameInCertificate=*.database.windows.net;loginTimeout=30;");
        dataSource.setUsername("AdminOnHome");
        dataSource.setPassword("******"); //Senha no planner do Projeto.
```


### Lembre-se de criar um usuário caso for utilizar o .jar Banco Local.
### Lembre-se de liberar acesso ao id da rede na platafoma da Azure caso for utilizar o .jar Banco na Azure.

# Pronto para executar o arquivo .jar

**Ao executar o arquivo .jar na tela de login (primeira tela a ser executada) coloque o seguinte usuário e senha:**

```
E-mail Andress: admin@onhome.com
Password: admin@admin
```

### No terminal, ao realizar o login se espera a segunte mensagem no terminal:

```
-------------------------------[ OnHome ]-------------------------------

Olá ao terminal da aplicação da OnHome \(^-^)/

---------------------------[ Banco de Dados ]---------------------------

Conectando ao Banco de Dados...

Banco de Dados Conectado!

-------------------------------[ Slack ]--------------------------------
Enviando mensagem de usuário logando...
Status: 404
Response: no_service
Mensagem não enviada! (X_X)
-----------------------------[ Computador ]-----------------------------
Validando computador...

Computador já existente na base de dados.

Bem-vindo de volta! \(^-^)/
-----------------------------[ Descrição ]------------------------------
Coletando dados do processador...
Insert realizado na tabela Monitoramento.
Coletando dados do processador...
Insert realizado na tabela Monitoramento.
Coletando dados do processador...
Insert realizado na tabela Monitoramento.
Coletando dados do processador...
Insert realizado na tabela Monitoramento.
Coletando dados do processador...
Insert realizado na tabela Processo.
Insert realizado na tabela Monitoramento.
Coletando dados do processador...
Insert realizado na tabela Processo.
Insert realizado na tabela Monitoramento.
Coletando dados do processador...
Insert realizado na tabela Processo.
Insert realizado na tabela Monitoramento.
Coletando dados do processador...
Insert realizado na tabela Processo.
------------------------------------------------------------------------
```

**E após a validação de acesso, o usuário já terá permissão de visualizar todas as outras telas (java swing)**

## Desenvolvedores
#
- @feliveiracamara
- @gabrielsouzaexe
- @julianaesteves
- @matheusferreira079
- @msuttobr

## Licença
#
© 2022 OnHome
