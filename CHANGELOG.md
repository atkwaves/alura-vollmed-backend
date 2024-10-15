# 0.6.0
[14/10/2024]

### Novas funcionalidades
* [#11](https://github.com/atkwaves/alura-vollmed-backend/issues/11) - Implementado o endpoint para cadastro de pacientes.

### Alterações na base de dados
* V4__create-table-pacientes.sql: Cria a tabela `pacientes`.

# 0.5.0
[13/10/2024]

### Novas funcionalidades
* [#9](https://github.com/atkwaves/alura-vollmed-backend/issues/9) - Implementado o endpoint para exclusão lógica de médicos.

### Alterações na base de dados
* V3__alter-table-medicos-add-column-ativo.sql: Adiciona a coluna `ativo` na tabela `medicos`.

# 0.4.0
[13/10/2024]

### Novas funcionalidades
* [#7](https://github.com/atkwaves/alura-vollmed-backend/issues/7) - Implementado o endpoint para atualização de dados cadastrais de médicos.

# 0.3.0
[12/10/2024]

### Novas funcionalidades
* [#5](https://github.com/atkwaves/alura-vollmed-backend/issues/5) - Implementado o endpoint para listagem de médicos.

# 0.2.0
[12/10/2024]

### Novas funcionalidades
* [#2](https://github.com/atkwaves/alura-vollmed-backend/issues/2) - Implementado o endpoint para cadastro de médicos.

### Alterações na base de dados
* V1__create-table-medicos.sql: Cria a tabela `medicos`.
* V2__alter-table-medicos-add-column-telefone.sql: Adiciona a coluna `telefone` na tabela `medicos`.

### Alterações de dependências
* `spring-boot-starter-data-jpa`: N/A > 3.3.4
* `spring-boot-starter-validation`: N/A > 3.3.4
* `mysql-connector-j`: N/A > 8.3.0
* `flyway-core`: N/A > 10.10.0
* `flyway-mysql`: N/A > 10.10.0

# 0.1.0
[07/10/2024]

### Novas funcionalidades
* [#1](https://github.com/atkwaves/alura-vollmed-backend/issues/1) - Configura a estrutura inicial do projeto `Voll-med`.

### Alterações de dependências
* `spring-boot-starter-web`: N/A > 3.3.4
* `lombok`: N/A > 1.18.34
* `spring-boot-starter-test`: N/A > 3.3.4