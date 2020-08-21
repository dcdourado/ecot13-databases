# ecot13-databases

## Introdução

Ao utilizar este repositório você será capaz de executar os bancos exigidos pela disciplina.

Bancos de dados contemplados:

- MySQL com PhpMyAdmin (latest)
- Neo4j (latest)
- OracleDB (18.4.0)

## Pré-requisitos

[Docker](https://docs.docker.com/get-docker/)  
[Docker-Compose](https://docs.docker.com/compose/install/)  
15GB+ espaço livre (Oracle...)

## Tutorial

1. Clone o repositório

   > git clone https://github.com/dcdourado/ecot13-databases.git

2. Acesse o diretório clonado

   > cd ecot13-databases

3. Dê permissões para o diretório utilizado pelo OracleDB

   > sudo chmod 777 oracle/oradata

4. Altere a variável de ambiente de senha padrão em .env

   > DEFAULT_PASSWORD=sua_senha_aqui

5. Por fim, suba os containers
   > docker-compose up -d

## Fim

Meus parabéns, você agora pode acessar os serviços em:

- **PhpMyAdmin**
  - http://localhost:10001
- **Neo4j**
  - http://localhost:7474
- **Oracle OEM Express**
  - https://localhost:5500/em/

## Contribuição

Atualmente não é possível acessar o OEM da Oracle. Estou investigando o problema, caso queira contribuir sinta-se livre para criar um fork e realizar o pull request :)
