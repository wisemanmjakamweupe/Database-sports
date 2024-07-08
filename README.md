# Database-sports
sports database
Create database Afcon;
use Afcon;
Create table PLAYER(
P_code varchar(5) not null,
Player_name varchar(50) not null,
Prof_club varchar(25) not null,
Goals int not null,
Country_code varchar(4) not null,

primary key(P_code)

);

Create table TEAMS(
Code_country varchar(2),
Country varchar(25),
Continent varchar(15),

primary key(Code_country)
);

insert into PLAYER values("G001","Junior Agogo","Birmingham","3","G1");
insert into PLAYER values("G002","Michael Essien","Chelsea","4","G1");
insert into PLAYER values("N021","JOhn Obi Mikel","Chelsea","1","N1");
insert into PLAYER values("E039","Mohammend Zidane","Bayern MUnich ","2","E2");
insert into PLAYER values("C087","Samuel E'too","Barcelona","5","C9");
insert into PLAYER values("G004","Stephen Appiah","Fernerbeche","2","G1");
insert into PLAYER values("E009","Hassan Osam","Al Ajli","0","E2");
insert into PLAYER values("N032","JJ Okocha","Chelsea Null","NULL","N1");

select * from PLAYER;

insert into TEAMS values("G1","Ghana","Africa");
insert into TEAM values("N1","Nigeria","Africa");
insert into TEAMS values("E2","Egypt","Africa");
insert into TEAMS values("C9","Cameroon","Africa");
insert into TEAMS values("K1","Kenya","Africa");

select * from TEAMS;
