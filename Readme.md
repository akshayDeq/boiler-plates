docker run \
 -e POSTGRES_USER=postgres \
 -e POSTGRES_PASSWORD=password \
 -e POSTGRES_DB=productdb \
 -p 4444:5432 \
 -d postgres:latest


###### typeorm pgsql install:-
import { TypeOrmModule } from '@nestjs/typeorm';
npm install --save @nestjs/typeorm typeorm pg


###### .env config :-
import { ConfigModule } from '@nestjs/config';
npm i --save @nestjs/config


###### .env file :-
POSTGRES_HOST=localhost
POSTGRES_DB=productdb
POSTGRES_USER=postgres
POSTGRES_PASSWORD=password
POSTGRES_PORT=4444
