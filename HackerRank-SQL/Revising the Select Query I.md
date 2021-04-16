# Revising the Select Query I

* [[Link]](https://www.hackerrank.com/challenges/revising-the-select-query/problem)

Query all columns for all American cities in the **CITY** table with populations larger than `100000`. The **CountryCode** for America is `USA`.

The **CITY** table is described as follows:

![img](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

---

* [[code]](./sql-code/20210416-01.sql)

```mysql
SELECT *
FROM CITY
WHERE POPULATION > 100000 AND COUNTRYCODE = 'USA'
```

