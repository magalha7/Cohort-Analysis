# Cohort-Analysis
This is an example of the Cohart Analysis test. For this, the W3Schools SQL code editor was used. 

For this, the W3Schools test database was used. To access it click: https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all.

The above link opens an editor linked to the W3Schools test database. Delete everything in **SQL Statement editor**.

To view the analysis below copy and paste the code from the **code.sql** file in *SQL Statement editor*.

To understand the modeling of the W3Schools database, see the image **modeling.png**

The result of each query can be shown in the table below

|     | M  | M1 | M2 | M3 | M4 |
|-----|----|----|----|----|----|
| AGO | 18 | 8  | 5  | 4  | 4  |
| SET | 19 | 5  | 5  | 2  | 4  |
| OUT | 20 | 5  | 8  | 5  | 6  |
| NOV | 21 | 10 | 9  | 2  | 0  |

**Legend**
  - *M* is the number of customers for the current month (Ex: AGO has 18 customers);
  - *M1* represents the first month in relation to the base month;
  - *M2* represents the second month in relation to the base month;
  - *M3* represents the third month in relation to the base month;
  - *M4* represents the fourth month in relation to the base month.

Example: Consider the OUT line. M =  Is month base and means October has 20 customers, M1 = November and has 5 customers in relation M, M2 = December and has 8 customers in relation M, M3 = January and has 5 customers in relation M, M4 = February and has 6 customers in relation M.

|     | M    | M1    | M2    | M3    | M4    |
|-----|------|-------|-------|-------|-------|
| AGO | 100% | 44.4% | 27.8% | 22.2% | 22.2% |
| SET | 100% | 26.3% | 26.3% | 10.5% | 21.1% |
| OUT | 100% | 25%   | 40%   | 25%   | 30%   |
| NOV | 100% | 47.6% | 42.9% | 9.5%  | 0%    |

Median

| Median | 100% | 35.8% | 34.2% | 16.8% | 18.3% |
|--------|------|-------|-------|-------|-------|


  
