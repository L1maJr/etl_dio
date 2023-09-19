# Pipeline de ETL com Python

## Esse repositório foi desenvolvido para um dos projetos do bootcamp Santander da DIO usando como exemplo a comunidade ativa e o curso de banco de dados.


### Projeto

O cliente tem 2 arquivos em formatos CSV e precisa que seja gerado um terceiro aquivo mesclando esses arquivos.


### Users
> Nesse arquivo temos os usuários e os IDs das cidades que eles vão viajar.

### Destinys
> Nesse arquivos temos os IDs das cidades e seus pontos turisticos.


# Solução

Após a ETL é gerado o arquivo [Travelers]('/data/travelers.csv') que é a junção dos dois arquivos anteriores unindo cada usuário com a cidade para onde está viajando e um ponto turistico daquela cidade.