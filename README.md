# PatikaSQL9
PatikaSQL ÖDEV9

SELECT city, country FROM city
INNER JOIN country ON country.country_id = city.city_id

SELECT payment_id, first_name, last_name FROM customer
INNER JOIN payment ON customer.customer_id = payment.customer_id

SELECT rental_id, first_name, last_name FROM customer
INNER JOIN rental ON rental.customer_id = customer.customer_id

https://app.patika.dev/furkanhaykirer
