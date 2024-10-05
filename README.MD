# Sistema de Locação de Carros

Este repositório contém um sistema de banco de dados para gerenciar locações de carros. O banco de dados é construído com tabelas que armazenam informações sobre clientes, carros, funcionários, marcas, modelos, cargos e locações.

## Estrutura do Banco de Dados

### Tabelas

1. **CUSTOMERS (Clientes)**
   - ID
   - NAME
   - LASTNAME
   - PHONE
   - EMAIL
   - ADDRESS
   - CITY
   - STATE
   - BIRTH_DATE

2. **CARS (Carros)**
   - ID
   - NAME
   - YEAR
   - COLOR
   - KM
   - STATUS
   - BRAND_ID
   - MODEL_ID

3. **CAR_MODEL (Modelos)**
   - ID
   - MODEL_NAME

4. **CAR_BRAND (Marcas)**
   - ID
   - BRAND_NAME

5. **POSITIONS (Cargos)**
   - ID
   - DESCRIPTION

6. **EMPLOYEES (Funcionários)**
   - ID
   - NAME
   - PHONE NUMBER
   - CONTRACT_DATE
   - POSITION_ID

7. **LOCATIONS (Locações)**
   - ID
   - START_DATE
   - END_DATE
   - TOTAL
   - CUSTOMER_ID
   - CAR_ID
   - EMPLOYEE_ID

## Consultas SQL

### Exemplo de Consultas

1. Exibir nome, sobrenome e e-mail dos clientes que moram no estado de SP.
2. Exibir somente os automóveis com o status “Liberado”.
3. Exibir todos os automóveis do ano 2016.
4. Exibir todos os funcionários e seus respectivos cargos.
5. Exibir somente os funcionários que realizaram mais ou igual a 2 locações.
6. Exibir somente os clientes que realizaram mais ou igual a 2 locações.
7. Exibir todas as locações realizadas, com o nome do cliente, do automóvel e do funcionário.
8. Exibir quantas locações existem na tabela de LOCATIONS.
9. Exibir a locação com o TOTAL com maior valor.
10. Exibir todas as locações realizadas entre as datas “2022-05-20” a “2022-12-25”.

## Como Executar

Para executar este sistema, siga as etapas:

1. **Criar o Banco de Dados**
   Execute as queries de criação de tabelas.

2. **Inserir os Dados**
   Utilize as queries de inserção para adicionar dados nas tabelas.

3. **Executar Consultas**
   Utilize as consultas SQL para extrair informações relevantes do banco de dados.


