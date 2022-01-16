```SQL
1. SELECT title, description FROM film;
```

```SQL
2. SELECT * FROM film
WHERE length > 60
AND
length < 75;
```

```SQL
3. SELECT * FROM film
WHERE rental_rate = '0.99'
AND
(replacement_cost = '12.99' OR replacement_cost = '28.99');
```

**4.** Smith

```SQL
5. SELECT * FROM film
WHERE NOT length > 50
AND
NOT (rental_rate = '2.99' OR rental_rate = '4.99');
```
