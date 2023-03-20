# SQL-ODEV-3
country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız. 
ÇÖZÜM: SELECT* FROM country
WHERE country LIKE 'A%a'

![11111111111](https://user-images.githubusercontent.com/128131203/226284406-041ebf8f-dae1-48a6-855b-a13cc6402a36.PNG)

country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' karakteri ile sonlananları sıralayınız.
ÇÖZÜM: SELECT* FROM country
WHERE country LIKE '_____%n'

![2222](https://user-images.githubusercontent.com/128131203/226284460-0425e617-6108-4394-ab60-5393676a529e.PNG)

film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin 'T' karakteri içeren film isimlerini sıralayınız.
ÇÖZÜM:SELECT* FROM film
WHERE title ILIKE '___T%'

![333333333](https://user-images.githubusercontent.com/128131203/226284928-cec78383-f50e-4532-b2e8-10b58325f3d7.PNG)

film tablosunda bulunan tüm sütunlardaki verilerden title 'C' karakteri ile başlayan ve uzunluğu (length) 90 dan büyük olan ve rental_rate 2.99 olan verileri sıralayınız.
ÇÖZÜM:SELECT* FROM film
WHERE title LIKE 'C%' AND length > 90 AND rental_rate =2.99

![44444](https://user-images.githubusercontent.com/128131203/226285636-47c72373-a0f4-459f-8d3f-7a4c836d99dd.PNG)
