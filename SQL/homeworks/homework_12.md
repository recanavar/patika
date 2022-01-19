```SQL
1. SELECT length FROM film
   WHERE length > (
        SELECT AVG(length) FROM film
   );
```

```SQL
2. SELECT COUNT(*) FROM film
   WHERE rental_rate = (
        SELECT MAX(rental_rate) FROM film
   );
```

```SQL
3. SELECT * FROM film
   WHERE rental_rate = (SELECT MIN(rental_rate) FROM film)
   AND
   replacement_cost = (SELECT MIN(replacement_cost) FROM film);
```

```SQL
4. SELECT payment.customer_id, first_name, last_name, COUNT(payment.customer_id) AS payment_count FROM payment
   LEFT JOIN customer ON payment.customer_id = customer.customer_id
   GROUP BY payment.customer_id, customer.first_name, customer.last_name
   ORDER BY payment_count DESC;
```

**Result for Question 4:**

<img src="/pics/query.png"/>
