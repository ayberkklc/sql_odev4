# sql_odev4
<br></br><b> Soru 1 </b> 
<code> SELECT DISTINCT replacement_cost FROM film </code>
<br></br><b> Soru 2 </b> 
<code> SELECT COUNT (DISTINCT replacement_cost) FROM film</code>
<br></br><b> Soru 3 </b> 
<code> SELECT COUNT (title) FROM film
WHERE title LIKE ('T%') AND rating = ('G')</code>
<br></br><b> Soru 4 </b> 
<code> SELECT COUNT(country) FROM country
WHERE country LIKE ('_____')</code>
<br></br><b> Soru 5 </b> 
<code> SELECT COUNT(city) FROM city
WHERE city ILIKE ('%r')</code>
