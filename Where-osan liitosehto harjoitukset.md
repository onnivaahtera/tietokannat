1. SELECT country.name AS "country name", airport.name AS "airport name" FROM country JOIN airport ON country.iso_country = airport.iso_country WHERE country.name = 'Iceland';

	![img](https://github.com/onnivaahtera/tietokannat/blob/main/images/Screenshot%202024-10-20%20at%201.46.50%20PM.png)

2.  SELECT airport.name as 'airport name' from country join airport on country.iso_country = airport.iso_country WHERE airport.type = 'large_airport' and country.name = 'France';
	![img](obsidian://open?vault=tietokannat&file=images%2FScreenshot%202024-10-20%20at%202.05.21%20PM.png)

3. select country.name as "country_name", airport.name as "airport_name" from country join airport on country.iso_country = airport.iso_country WHERE country.continent = 'AN';
	![img](obsidian://open?vault=tietokannat&file=images%2FScreenshot%202024-10-20%20at%202.22.10%20PM.png)
4. select elevation_ft from airport join game on game.screen_name = 'Heini' and game.location = airport.ident;
	![img](obsidian://open?vault=tietokannat&file=images%2FScreenshot%202024-10-20%20at%2011.28.24%20PM.png)

5. select (elevation_ft * 0.3048) as elevation_m from airport, game where game.screen_name = 'Heini' and game.location = airport.ident;
	![img](obsidian://open?vault=tietokannat&file=images%2FScreenshot%202024-10-20%20at%2011.30.21%20PM.png)

6. 