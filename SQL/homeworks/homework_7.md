```SQL
1. SELECT rating FROM film
GROUP BY rating;
```

```SQL
2. SELECT replacement_cost, COUNT(*) FROM film
GROUP BY replacement_cost
HAVING COUNT(*) > 50;
```

```SQL
3. SELECT store_id, COUNT(*) FROM customer
GROUP BY store_id;

-- Results
-- store_id = 1 -> 326
-- store_id = 2 -> 273
```

```SQL
4. SELECT country_id, MAX(city_id) FROM city
GROUP BY country_id
ORDER BY MAX(city_id) DESC
LIMIT 1;

-- Results
-- country_id = 83
-- Max city = 600
```
