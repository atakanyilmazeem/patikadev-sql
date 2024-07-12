`Soru1:` test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```SQL
CREATE TABLE employee (
	id INT,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);
```
`Soru2:` Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```SQL
insert into employee (id, name, birthday, email) values (1, 'Barrett Osgordby', '1961-07-27', 'bosgordby0@home.pl');
insert into employee (id, name, birthday, email) values (2, 'Corinna Proppers', '1972-07-06', 'cproppers1@ft.com');
insert into employee (id, name, birthday, email) values (3, 'Ruthi Conkay', '1986-02-11', 'rconkay2@time.com');
insert into employee (id, name, birthday, email) values (4, 'Meredeth Rahlof', '1964-05-01', 'mrahlof3@blogtalkradio.com');
insert into employee (id, name, birthday, email) values (5, 'Melitta Pigot', '1982-01-31', 'mpigot4@wikia.com');
insert into employee (id, name, birthday, email) values (6, 'Alissa Lightowler', '1960-12-12', 'alightowler5@youku.com');
insert into employee (id, name, birthday, email) values (7, 'Blaire Woodhams', '1993-04-20', 'bwoodhams6@addthis.com');
insert into employee (id, name, birthday, email) values (8, 'Doralynne Bourne', '1994-05-18', 'dbourne7@i2i.jp');
insert into employee (id, name, birthday, email) values (9, 'Monah Rooze', '1965-02-16', 'mrooze8@nymag.com');
insert into employee (id, name, birthday, email) values (10, 'Shaylyn Rolfe', '2002-10-27', 'srolfe9@amazon.com');
insert into employee (id, name, birthday, email) values (11, 'Urban Brownlie', '1986-11-07', 'ubrownliea@opera.com');
insert into employee (id, name, birthday, email) values (12, 'Claire Sjollema', '1970-03-18', 'csjollemab@java.com');
insert into employee (id, name, birthday, email) values (13, 'Olga Greensmith', '1953-06-01', 'ogreensmithc@drupal.org');
insert into employee (id, name, birthday, email) values (14, 'Mattie Wimmer', '1962-08-28', 'mwimmerd@histats.com');
insert into employee (id, name, birthday, email) values (15, 'Nada Darnbrook', '1989-06-06', 'ndarnbrooke@com.com');
insert into employee (id, name, birthday, email) values (16, 'Reuven Henrique', '1992-03-08', 'rhenriquef@microsoft.com');
insert into employee (id, name, birthday, email) values (17, 'Maybelle Leonards', '1999-01-01', 'mleonardsg@phoca.cz');
insert into employee (id, name, birthday, email) values (18, 'Lani Iannazzi', '1970-01-04', 'liannazzih@bluehost.com');
insert into employee (id, name, birthday, email) values (19, 'Beth Bark', '1957-11-12', 'bbarki@china.com.cn');
insert into employee (id, name, birthday, email) values (20, 'Finn Stairmond', '1957-06-14', 'fstairmondj@rediff.com');
insert into employee (id, name, birthday, email) values (21, 'Hank Creswell', '2001-07-31', 'hcreswellk@fc2.com');
insert into employee (id, name, birthday, email) values (22, 'Lewes Kindall', '1961-05-22', 'lkindalll@archive.org');
insert into employee (id, name, birthday, email) values (23, 'Derrik Allnutt', '1981-11-16', 'dallnuttm@miibeian.gov.cn');
insert into employee (id, name, birthday, email) values (24, 'Zara MacConnulty', '2005-09-21', 'zmacconnultyn@merriam-webster.com');
insert into employee (id, name, birthday, email) values (25, 'Hephzibah Balk', '2000-09-27', 'hbalko@hexun.com');
insert into employee (id, name, birthday, email) values (26, 'Charissa Dunklee', '1996-06-09', 'cdunkleep@dmoz.org');
insert into employee (id, name, birthday, email) values (27, 'Minda Pendre', '1977-03-02', 'mpendreq@canalblog.com');
insert into employee (id, name, birthday, email) values (28, 'Elora Mitcheson', '1997-07-26', 'emitchesonr@samsung.com');
insert into employee (id, name, birthday, email) values (29, 'Angelika Sabbatier', '1996-07-11', 'asabbatiers@homestead.com');
insert into employee (id, name, birthday, email) values (30, 'Julie Lambal', '1991-04-20', 'jlambalt@pbs.org');
insert into employee (id, name, birthday, email) values (31, 'Jammie Lampkin', '1957-10-22', 'jlampkinu@yellowbook.com');
insert into employee (id, name, birthday, email) values (32, 'Broddie Strand', '1983-02-05', 'bstrandv@goodreads.com');
insert into employee (id, name, birthday, email) values (33, 'Sumner Hedau', '1963-05-01', 'shedauw@friendfeed.com');
insert into employee (id, name, birthday, email) values (34, 'Saloma Arnoldi', '1972-02-12', 'sarnoldix@indiatimes.com');
insert into employee (id, name, birthday, email) values (35, 'Esme Madgett', '1966-04-30', 'emadgetty@time.com');
insert into employee (id, name, birthday, email) values (36, 'Adriane McCleverty', '1961-05-14', 'amcclevertyz@tripadvisor.com');
insert into employee (id, name, birthday, email) values (37, 'Heddi Bartlam', '1975-03-02', 'hbartlam10@ucla.edu');
insert into employee (id, name, birthday, email) values (38, 'Sterling Salsbury', '1954-04-13', 'ssalsbury11@ycombinator.com');
insert into employee (id, name, birthday, email) values (39, 'Marcus Murrigan', '1969-06-03', 'mmurrigan12@livejournal.com');
insert into employee (id, name, birthday, email) values (40, 'Jacinthe Jarrell', '1959-07-23', 'jjarrell13@shop-pro.jp');
insert into employee (id, name, birthday, email) values (41, 'Parnell Allatt', '1980-11-17', 'pallatt14@cornell.edu');
insert into employee (id, name, birthday, email) values (42, 'Thibaut Fishbourne', '1979-06-28', 'tfishbourne15@businesswire.com');
insert into employee (id, name, birthday, email) values (43, 'Marice Pastor', '1959-05-15', 'mpastor16@live.com');
insert into employee (id, name, birthday, email) values (44, 'Avivah Britney', '1987-07-26', 'abritney17@i2i.jp');
insert into employee (id, name, birthday, email) values (45, 'Elene Worsnip', '1961-09-01', 'eworsnip18@craigslist.org');
insert into employee (id, name, birthday, email) values (46, 'Almira Blackwood', '1995-04-03', 'ablackwood19@nyu.edu');
insert into employee (id, name, birthday, email) values (47, 'Maritsa Thurston', '1977-08-30', 'mthurston1a@army.mil');
insert into employee (id, name, birthday, email) values (48, 'Christina Claeskens', '1971-09-20', 'cclaeskens1b@networksolutions.com');
insert into employee (id, name, birthday, email) values (49, 'Meriel Awcock', '1956-09-11', 'mawcock1c@ezinearticles.com');
insert into employee (id, name, birthday, email) values (50, 'Isak Purselowe', '1960-03-25', 'ipurselowe1d@newsvine.com');
```
`Soru3:` Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```SQL
UPDATE employee SET name = 'Atakan Yilmaz' WHERE id = 1 RETURNING *;
UPDATE employee SET birthday = '1998-09-12' WHERE id = 1 RETURNING *;
UPDATE employee SET email = 'aspar@aspar.com' WHERE id = 1 RETURNING *;
UPDATE employee SET email = 'napar@aspar.com' WHERE id = 2 RETURNING *;
UPDATE employee SET name = 'Aspar Napar' WHERE id = 2 RETURNING *;
```
`Soru4:` Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```SQL
DELETE FROM employee WHERE id = 3 RETURNING *;
DELETE FROM employee WHERE name LIKE 'Ba%' RETURNING *;
DELETE FROM employee WHERE name LIKE '%d' RETURNING *;
DELETE FROM employee WHERE id = 5 RETURNING *;
DELETE FROM employee WHERE id = 6 RETURNING *;
```
