

### 3  
SELECT name FROM airport WHERE iso_country = "FI" ORDER BY name
![[Screenshot 2024-09-17 at 1.32.46 PM.png]]
### 4
SELECT name, type FROM airport WHERE iso_country = "FI" ORDER BY type asc, name asc;
![[Screenshot 2024-09-17 at 1.30.40 PM.png]]

### 5
SELECT name FROM country WHERE name like "f%";
![[Pasted image 20240917142859.png]]
### 6
SELECT name FROM country WHERE name like "%f%";
![[Pasted image 20240917143432.png]]

### 7
SELECT location FROM game where screen_name = "Vesa";
![[Pasted image 20240917144139.png]]

### 8
SELECT co2_consumed FROM game where screen_name = "Ilkka";
![[Pasted image 20240917144320.png]]

### 9
SELECT co2_budget FROM game where screen_name = "Ilkka"
![[Pasted image 20240917144440.png]]