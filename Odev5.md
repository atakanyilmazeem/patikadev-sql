`Soru1:` film tablosunda bulunan ve film ismi (title) 'n' karakteri ile biten en uzun (length) 5 filmi sıralayın.
```SQL
SELECT * FROM film WHERE title LIKE '%n' ORDER BY length DESC LIMIT 5;
```
`Soru2:` film tablosunda bulunan ve film ismi (title) 'n' karakteri ile biten en kısa (length) ikinci(6,7,8,9,10) 5 filmi(6,7,8,9,10) sıralayınız.
```SQL
SELECT * FROM film WHERE title LIKE '%n' ORDER BY length ASC OFFSET 5 LIMIT 5;
```
`Soru3:` customer tablosunda bulunan last_name sütununa göre azalan yapılan sıralamada store_id 1 olmak koşuluyla ilk 4 veriyi sıralayınız.
```SQL
SELECT * FROM customer ORDER BY store_id, last_name LIMIT 4;
```
