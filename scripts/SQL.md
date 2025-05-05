# SQL

## Order of Execution

1. FROM and JOINs
    - determine the data of interest
2. WHERE
    - filter out records that do not meet the condition(s)
3. GROUP BY
    - group the data based on some column(s)
4. HAVING
    - remove the created grouped records that do not meet the condition(s)
5. SELECT
    - derive all columns and expressions needed
6. ORDER BY
    - sort derived values
7. LIMIT and OFFSET
    - keep or skip specified number of rows