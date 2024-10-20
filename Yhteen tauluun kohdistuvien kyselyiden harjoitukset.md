

### 3  
SELECT name FROM airport WHERE iso_country = "FI" ORDER BY name
![img](/images/3-3.png)
### 4
SELECT name, type FROM airport WHERE iso_country = "FI" ORDER BY type asc, name asc;
![img](/images/3-4.png)

### 5
SELECT name FROM country WHERE name like "f%";
![img](/images/3-5.png)
### 6
SELECT name FROM country WHERE name like "%f%";
![img](/images/3-6.png)

### 7
SELECT location FROM game where screen_name = "Vesa";
![img](/images/3-7.png)

### 8
SELECT co2_consumed FROM game where screen_name = "Ilkka";
![img](/images/3-8.png)

### 9
SELECT co2_budget FROM game where screen_name = "Ilkka"
![img](/images/3-9.png)