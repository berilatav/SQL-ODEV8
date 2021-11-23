# SQL-ODEV8
Create Table, Insert Into, Update, Delete
##

1) Test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee (

id SERIAL PRIMARY KEY,

name VARCHAR(50)NOT NULL,

birthday DATE,

email VARCHAR(100) );

2)Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (name, birthday, email) values ('Markos', '2008-11-23', 'mgarrod0@google.com.au');

insert into employee (name, birthday, email) values ('Ailene', '2002-02-11', 'agallienne1@usnews.com');

insert into employee (name, birthday, email) values ('Minnaminnie', '1973-02-08', 'mdawtre2@princeton.edu');

insert into employee (name, birthday, email) values ('Zacherie', '1963-09-29', 'zburgett3@wiley.com');

insert into employee (name, birthday, email) values ('Glyn', '1928-10-24', 'glabusch4@github.io');

insert into employee (name, birthday, email) values ('Clarey', '1924-11-05', 'ccrittal5@nba.com');

insert into employee (name, birthday, email) values ('Tove', '1977-10-17', 'tlanning6@goo.gl');

insert into employee (name, birthday, email) values ('Thelma', '1919-06-12', 'thunnybun7@bloglines.com');

insert into employee (name, birthday, email) values ('Dulcy', '1969-03-26', 'dholbarrow8@facebook.com');

insert into employee (name, birthday, email) values ('Yolanda', '2000-07-27', 'ygimeno9@biglobe.ne.jp');

insert into employee (name, birthday, email) values ('Joela', '1989-12-20', 'jsmootea@mtv.com');

insert into employee (name, birthday, email) values ('Tildie', '2017-08-09', 'tstrewtherb@google.com');

insert into employee (name, birthday, email) values ('Catriona', '2003-10-31', 'ctoffalonic@wikimedia.org');

insert into employee (name, birthday, email) values ('Francesco', '1983-10-03', 'fbenedekd@narod.ru');

insert into employee (name, birthday, email) values ('Amitie', '1937-03-01', 'awilcotte@dedecms.com');

insert into employee (name, birthday, email) values ('Donella', '1912-06-07', 'dlongleyf@gravatar.com');

insert into employee (name, birthday, email) values ('Kelwin', '1965-12-16', 'kgranleeseg@soup.io');

insert into employee (name, birthday, email) values ('Amaleta', '1912-08-28', 'athewysh@umich.edu');

insert into employee (name, birthday, email) values ('Maighdiln', '2013-11-14', 'mdrani@soundcloud.com');

insert into employee (name, birthday, email) values ('Sergent', '1960-02-24', 'scastagnej@cornell.edu');

insert into employee (name, birthday, email) values ('Brinn', '1979-07-19', 'bsnariek@cisco.com');

insert into employee (name, birthday, email) values ('Meris', '2016-10-30', 'mboustredl@yelp.com');

insert into employee (name, birthday, email) values ('Nicolina', '2009-05-18', 'nishakm@house.gov');

insert into employee (name, birthday, email) values ('Cindelyn', '1931-10-19', 'carnoutn@jigsy.com');

insert into employee (name, birthday, email) values ('Kippie', '1983-12-01', 'kpiechniko@aboutads.info');

insert into employee (name, birthday, email) values ('Berty', '1917-03-22', 'bsteadp@dion.ne.jp');

insert into employee (name, birthday, email) values ('Gert', '1918-09-22', 'gjardeinq@discuz.net');

insert into employee (name, birthday, email) values ('Shayne', '1940-02-25', 'smcleanr@imgur.com');

insert into employee (name, birthday, email) values ('Ransell', '1977-07-10', 'rleforts@mail.ru');

insert into employee (name, birthday, email) values ('Arielle', '2017-12-06', 'amcguirkt@symantec.com');

insert into employee (name, birthday, email) values ('Durante', '1915-03-12', 'dgrioliu@homestead.com');

insert into employee (name, birthday, email) values ('Hermione', '1944-03-30', 'hwhipplev@myspace.com');

insert into employee (name, birthday, email) values ('Ulla', '1988-01-31', 'uscoatesw@printfriendly.com');

insert into employee (name, birthday, email) values ('Gunner', '2014-06-26', 'gelmorex@nasa.gov');

insert into employee (name, birthday, email) values ('Natal', '1947-03-17', 'ngillyatty@quantcast.com');

insert into employee (name, birthday, email) values ('Kelbee', '1979-09-08', 'ktempestz@columbia.edu');

insert into employee (name, birthday, email) values ('Michael', '1959-01-08', 'mrumford10@npr.org');

insert into employee (name, birthday, email) values ('Zarla', '1970-04-02', 'zrappport11@earthlink.net');

insert into employee (name, birthday, email) values ('Dimitry', '1997-06-15', 'drustich12@rambler.ru');

insert into employee (name, birthday, email) values ('Koren', '1944-07-26', 'kburkinshaw13@reddit.com');

insert into employee (name, birthday, email) values ('Brit', '2014-04-14', 'bvanarsdale14@elegantthemes.com');

insert into employee (name, birthday, email) values ('North', '1904-07-17', 'nbonham15@harvard.edu');

insert into employee (name, birthday, email) values ('Doralin', '1904-07-24', 'dlobley16@ftc.gov');

insert into employee (name, birthday, email) values ('Christian', '1987-07-18', 'chutable17@toplist.cz');

insert into employee (name, birthday, email) values ('Benjie', '1955-07-23', 'bstorah18@msu.edu');

insert into employee (name, birthday, email) values ('Demetre', '1957-08-06', 'dcauley19@twitpic.com');

insert into employee (name, birthday, email) values ('Maria', '1978-02-19', 'mtrynor1a@omniture.com');

insert into employee (name, birthday, email) values ('Oates', '1903-04-29', 'omacterlagh1b@acquirethisname.com');

insert into employee (name, birthday, email) values ('Dorie', '2003-01-24', 'ddeluze1c@apache.org');

insert into employee (name, birthday, email) values ('Pepillo', '1937-04-16', 'pmidlane1d@e-recht24.de');

3)Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee

SET name ='Beril'

WHERE id=1 ;	

UPDATE employee

SET name ='Beren'

WHERE id=2 ;

UPDATE employee

SET email ='mavi@gök.com'

WHERE name LIKE 'P%' ;	

UPDATE employee

SET email ='pembe@şeker.com'

WHERE name LIKE '%n' ;	

UPDATE employee

SET name ='Elif'

WHERE id=30 ;

4)Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee

WHERE name= 'Clarey';

DELETE FROM employee

WHERE email= 'awilcotte@dedecms.com' ;

DELETE FROM employee

WHERE name='Meris' ;

DELETE FROM employee

WHERE name='Berty' ;

DELETE FROM employee

WHERE email='tlanning6@goo.gl' ;



