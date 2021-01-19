1.

SELECT title, release_date FROM movies WHERE release_date BETWEEN '1983-01-01' AND '1993-01-01'
ORDER BY release_date DESC;

2.

SELECT movie_id, SUM(rating)/COUNT(*) AS average_rating FROM ratings GROUP BY movie_id
ORDER BY average_rating ASC;
