# How to Solve HackerRank Population Census Problem

--Lets sum the required column values

SELECT SUM(CITY.POPULATION) FROM COUNTRY COUNTRY

--Join the both  CITY and COUNTRY table in countrycode and code

INNER JOIN CITY CITY ON CITY.COUNTRYCODE = COUNTRY.CODE

--Lets constraint the result

WHERE COUNTRY.CONTIENT = 'Asia'
