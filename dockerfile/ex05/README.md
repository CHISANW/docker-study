## Mysql 도커 생성파일


## UTF-8 설정 확인

SHOW variables LIKE 'character_set_%';

## 볼륨 옵션방법으로 실행방법
docker run -d -v C:\docker\ex05\mysql-volume:/var/lib/mysql -p 3307:3306 
--name myslq-container mysql_ig 
