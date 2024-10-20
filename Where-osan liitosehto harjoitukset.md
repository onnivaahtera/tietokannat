1. SELECT country.name AS "country name", airport.name AS "airport name" FROM country JOIN airport ON country.iso_country = airport.iso_country WHERE country.name = 'Iceland';
	![img](/images/4-1.png)

2.  SELECT airport.name as 'airport name' from country join airport on country.iso_country = airport.iso_country WHERE airport.type = 'large_airport' and country.name = 'France';
	![img](/images/4-2.png)

3. select country.name as "country_name", airport.name as "airport_name" from country join airport on country.iso_country = airport.iso_country WHERE country.continent = 'AN';
	![img](/images/4-3.png)
4. select elevation_ft from airport join game on game.screen_name = 'Heini' and game.location = airport.ident;
	![img](/images/4-4.png)

5. select (elevation_ft * 0.3048) as elevation_m from airport, game where game.screen_name = 'Heini' and game.location = airport.ident;
	![img](/images/4-5.png)

6. select name from airport, game where game.screen_name = 'Ilkka' and game.location = airport.ident;
	![img](/images/4-6.png)

7. select country.name as "name" from country, airport, game where game.screen_name = "Ilkka" and game.location = airport.ident and airport.iso_country = country.iso_country;
	![img](/images/4-7.png)

8. select name from goal, goal_reached, game where game.id = game_id and goal.id = goal_id and screen_name = "Heini";
	![img](/images/4-8.png)

9. select airport.name from airport, game, goal, goal_reached where game.screen_name = "Ilkka" and goal.name = 'CLOUDS' AND game.id = goal_reached.game_id and goal_reached.goal_id = goal.id and game.location = airport.ident;
	![img](/images/4-9.png)

10. select country.name from country, goal, goal_reached, airport, game where game.screen_name = "Ilkka" AND goal.name = 'CLOUDS' AND game.id = goal_reached.game_id and goal_reached.goal_id = goal.id and game.location = airport.ident AND airport.iso_country = country.iso_country;
	![img](/images/4-10.png)