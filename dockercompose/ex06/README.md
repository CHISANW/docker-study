## 도커 컴포즈 백그라운드 실행법
docker-compose up -d


## MySQL 테스트 내용
use rootdb;

create table person(
id int primary key,
name varchar(20)
);

insert into person (id, name) values (1,"이름");