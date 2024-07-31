``` sql
SELECT DISTINCT replacement_cost FROM film;

SELECT COUNT (*) DISTINCT replacement_cost FROM film;

SELECT COUNT (*) FROM film WHERE title LIKE 'T%' AND rating = 'G';

SELECT * FROM film WHERE LENGTH (country) = 5;

SELECT COUNT (*) FROM city WHERE city LIKE '%R' OR city LIKE '%r';

```
