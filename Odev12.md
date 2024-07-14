`Soru1:` film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?
```SQL
SELECT * FROM film
WHERE length >
(
	SELECT AVG(length) FROM film
);
```
`Soru2:` film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?
```SQL
SELECT COUNT(*) FROM film
WHERE rental_rate =
(
	SELECT MAX(rental_rate) FROM film
);
```
`Soru3:` film tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.
```SQL
SELECT * FROM film
WHERE rental_rate =
(
	SELECT MIN(rental_rate) FROM film
)
INTERSECT
SELECT * FROM film
WHERE replacement_cost =
(
	SELECT MIN(replacement_cost) FROM film
);
```
`Soru4:` payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.
```SQL
SELECT customer.customer_id, customer.first_name, customer.last_name, COUNT(*) AS ALISVERIS_SAYISI FROM payment
JOIN customer ON payment.customer_id = customer.customer_id
GROUP BY customer.customer_id
ORDER BY ALISVERIS_SAYISI DESC;
```
