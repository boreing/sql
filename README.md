# sql
practice


create database Apple;
show databases;
use apple;
create table iphone_moblie_a
(
product_id int primary key not null, 
model_name varchar(50) not null, 
colour varchar(50) not null,
year_model year
);

insert into iphone_moblie_a values
(1301064, 'iphone 13', 'red',  2021),
(1302064, 'iphone 13', 'starlight', 2021),
(1303064, 'iphone 13', 'midnight',  2021),
(1304064, 'iphone 13', 'blue', 2021),
(1305064, 'iphone 13', 'pink',  2021),
(1306064, 'iphone 13', 'green', 2021),

(1301128, 'iphone 13', 'red',  2021),
(1302128, 'iphone 13', 'starlight', 2021),
(1303128, 'iphone 13', 'midnight',  2021),
(1304128, 'iphone 13', 'blue', 2021),
(1305128, 'iphone 13', 'pink',  2021),
(1306128, 'iphone 13', 'green', 2021),


(1301256, 'iphone 13', 'red',  2021),
(1302256, 'iphone 13', 'starlight', 2021),
(1303256, 'iphone 13', 'midnight',  2021),
(1304256, 'iphone 13', 'blue', 2021),
(1305256, 'iphone 13', 'pink',  2021),
(1306256, 'iphone 13', 'green', 2021),

(1501128, 'iphone 15', 'red', 2022),
(1502128, 'iphone 15', 'starlight', 2023),
(1503128, 'iphone 15', 'midnight', 2023),
(1504128, 'iphone 15', 'blue', 2023),
(1507128, 'iphone 15', 'purple', 2023),
(1508128, 'iphone 15', 'yellow', 2023),

(1501512, 'iphone 15', 'red', 2023),
(1502512, 'iphone 15', 'starlight', 2023),
(1503512, 'iphone 15', 'midnight', 2023),
(1504512, 'iphone 15', 'blue', 2023),
(1507512, 'iphone 15', 'purple', 2023),
(1508512, 'iphone 15', 'yellow', 2023),

(1501256, 'iphone 15', 'red', 2023),
(1502256, 'iphone 15', 'starlight', 2023),
(1503256, 'iphone 15', 'midnight', 2023),
(1504256, 'iphone 15', 'blue', 2023),
(1507256, 'iphone 15', 'purple', 2023),
(1508256, 'iphone 15', 'yellow', 2023)
;
select * from iphone_moblie_a;


drop table iphone_moblie_a;
drop database apple;
