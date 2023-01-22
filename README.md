# Patika-Dev-SQL-Odev---4
## SQL Ödev - 4

### 1- film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.
````sql
SELECT DISTINCT replacement_cost FROM FILM ;
````
### 2- film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?
````sql
SELECT  COUNT(DISTINCT replacement_cost) FROM FILM;
````
### 3- film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?
````sql
SELECT COUNT(*) FROM FILM WHERE title LIKE 'T%' AND rating = 'G';
````
### 4- country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?
````sql
SELECT COUNT(*) FROM COUNTRY WHERE COUNTRY LIKE '_____';
````
### 5- city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?
````sql
SELECT COUNT(CITY) FROM CITY WHERE CITY LIKE 'R% OR CITY LIKE '%r';
````
