SELECT country.name AS "country name", airport.name AS "airport name" FROM country JOIN airport ON country.iso_country = airport.iso_country WHERE country.name = 'Iceland';

![img](https://github.com/onnivaahtera/tietokannat/blob/main/images/Screenshot%202024-10-20%20at%201.46.50%20PM.png)