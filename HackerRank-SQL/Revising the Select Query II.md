# Revising the Select Query II

* [[Link]](https://www.hackerrank.com/challenges/revising-the-select-query-2/problem)

Query the **NAME** field for all American cities in the **CITY** table with populations larger than `120000`. The **CountryCode** for America is `USA`.

The **CITY** table is described as follows:

![img](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

---

* [[code]](./sql-code/20210416-02.sql)

```mysql
SELECT NAME
FROM CITY
WHERE POPULATION > 120000 AND COUNTRYCODE = 'USA'
```

