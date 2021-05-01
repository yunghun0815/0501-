1. ER다이어그램을 참고하여 Oracle DB에 테이블을 생성하세요.

create table person (
no NUMBER not null primary key,
id VARCHAR2(200) not null,
pw VARCHAR2(200) not null,
phone VARCHAR2(30),
reg TIMESTAMP );

2. no에 데이터 시퀀스를 참고하여 입력하기 위한 시퀀스를 만들어주세요.
 ![시퀀스](https://user-images.githubusercontent.com/82852887/116778383-82c55780-aaac-11eb-9d63-f4ee03d3d2b8.jpg)

3 ~ 10
 ![3~10번](https://user-images.githubusercontent.com/82852887/116778395-91ac0a00-aaac-11eb-9cca-62e6391c5452.JPG)
