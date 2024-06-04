# SQL-Homework-2

select countrycode as country, count(ID) as number_of_cities from city where countrycode = 'USA';
select population, lifeexpectancy from country where code = 'ARG';
select district from city where countrycode = 'FRA';
select * from countrylanguage where language = 'french' and isofficial = 't';
select * from city where countrycode = 'USA' and population > 1000000;
