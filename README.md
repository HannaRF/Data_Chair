# Data_Chair

## Autores: Ari, Hanna Rodrigues, Lívia Cereja e Luiz

### Projeto para a disciplina de modelagem e uso de banco de dados da EMAP FGV ministrada pelo professor Renato Rocha Souza.

O Banco de dados Data_Chair possui informações nutricionais sobre os produtos e localização das redes de restaurantes de grandes multinacionais de fast-food da atualidade. Os dados foram coletados dos sites das próprias empresas e de Banco de Dados auxiliares.

## Fontes:
### Nutrição 

- [Starbucks](https://www.starbucks.co.uk/quick-links%2Fnutrition-info)
- [Mc Donalds](https://www.kaggle.com/mcdonalds/nutrition-facts)
- [Burguer King](http://bk-latam-prod.s3.amazonaws.com/sites/burgerking.com.br/files/documents/F171_AF_TABELA_NUTRICIONAL_C4_42X29_7_1407.pdf)

### Localização

- [Starbucks](https://www.kaggle.com/starbucks/store-locations)
- [Mc Donalds(sample)](https://data-lists.com/mcdonalds/)
- [Burguer King(sample)](https://www.aggdata.com/aggdata/complete-list-burger-king-locations)
- [Burguer King(sample)](https://www.scrapehero.com/store/product/burger-king-store-locations-in-the-usa/)

|     Chave     |     Tipo    |                      Descrição                     |   Tabela   |
|:-------------:|:-----------:|:--------------------------------------------------:|:----------:|
|   id_address  |     INT     | identificador exclusivo do endereço do restaurante |   address  |
|     street    | VARCHAR(45) |          Rua e complemento do restaurante          |   address  |
|      city     | VARCHAR(45) |                cidade do restaurante               |   address  |
|     state     | VARCHAR(45) |                estado do restaurante               |   address  |
|   post code   | VARCHAR(45) |            código postal do restaurante            |   address  |
|    country    | VARCHAR(45) |                 país do restaurante                |   address  |
| id_restaurant |     INT     |       identificador exclusivo do restaurante       | restaurant |
|     phone     | VARCHAR(45) |               telefone do restaurante              | restaurant |
|    id_chain   |     INT     |          indentificador exclusivo da rede          |    chain   |
|      name     | VARCHAR(45) |                    nome da rede                    |    chain   |
|   id_product  |     INT     |         identificador exclusivo do produto         |   product  |
|      name     | VARCHAR(45) |                   nome do produto                  |   product  |
|  id_category  |     INT     |   identificador exclusivo da categoria do produto  |  category  |
| serving size  |     INT     |            tamanho das porções do produto          |  category  |
