```SQL
1. SELECT country, city FROM country
LEFT JOIN city ON city.country_id = country.country_id;
```

```SQL
2. SELECT payment_id, first_name, last_name FROM customer
RIGHT JOIN payment ON payment.customer_id = customer.customer_id;
```

```SQL
3. SELECT rental_id, first_name, last_name FROM customer
FULL JOIN rental ON rental.customer_id = customer.customer_id;
```
