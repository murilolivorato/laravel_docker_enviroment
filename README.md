
# YEP IMOVEIS


### INSTALAÇAO

- docker-compose up -d --build
- docker-compose run --rm composer install
- docker-compose run --rm artisan key:generate

## BANCO DE DADOS
Insira no .env , as seguintes informações do banco de dados

```
DB_CONNECTION=mysql
DB_HOST=172.20.0.1 ( ip do DB Local )
DB_PORT=3306
DB_DATABASE=sigo_database
DB_USERNAME=root
DB_PASSWORD=secret
```
## LIMPE O CACHE
- docker-compose run  --rm artisan config:cache

## MIGRATE DB
- docker-compose run  --rm artisan migrate

## INSTALAÇÃO PASSPORT
- docker-compose run --rm  artisan passport:install
- docker-compose run --rm  artisan passport
-
## PASSPORT - NOVOS TIPOS
docker-compose run --rm  artisan passport:client --password

## LIMPE O CACHE
- docker-compose run  --rm artisan config:cache
- docker-compose run  --rm composer dump-autoload

## DB SEED
- docker-compose run  --rm  artisan db:seed --class InitialDataSeeder
- docker-compose run  --rm  artisan db:seed --class UsersDataSeeder
- docker-compose run  --rm  artisan db:seed --class PostsDataSeeder
- docker-compose run  --rm  artisan db:seed --class PropsDataSeeder
- docker-compose run  --rm  artisan db:seed --class PropNewDataSeeder
- docker-compose run  --rm  artisan db:seed --class FinalDataSeeder


#CITIES AND NEIGHBORHOODS
-sÃO PAULO - CITY - 2210
-RIBEIRÃO PRETO - CITY - 2100
-BELO HORIZONTE - CITY - 997
-RIO DE JANEIRO - CITY - 1482
- PORTO ALEGRE - CITY - 7897
- CURITIBA - CITY - 6345
- SALVADOR - CITY - 2305
- MACEIO - CITY - 2811
- CAMPINAS - CITY - 2209
