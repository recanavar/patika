```SQL
1. SELECT DISTINCT replacement_cost FROM film;
```

```SQL
2. SELECT COUNT(DISTINCT replacement_cost) FROM film; -- result : 21 unique data
```

```SQL
3. SELECT COUNT(title) FROM film
WHERE title LIKE 'T%'
AND
rating = 'G'; -- result : 9 data
```

```SQL
4. SELECT COUNT(country) FROM country
WHERE country LIKE '_____'; -- 5 underscore

-- Alternative:
SELECT COUNT(country) FROM country
WHERE LENGTH(country) = 5; -- result : 13 data
```

```SQL
5. SELECT COUNT(city) FROM city
WHERE city ILIKE '%r'; -- result : 33 data
```
