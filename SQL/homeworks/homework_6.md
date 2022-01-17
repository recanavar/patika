```SQL
1.SELECT ROUND(AVG(rental_rate),3) FROM film; -- result: 2.980
```

```SQL
2. SELECT COUNT(title) FROM film
WHERE title LIKE 'C%'; -- result: 92
```

```SQL
3. SELECT MAX(length) FROM film
WHERE rental_rate = 0.99; -- result: 184
```

```SQL
4. SELECT COUNT(DISTINCT replacement_cost) FROM film
WHERE length > 150; -- result: 21
```
