## SQL Queries
  # How to print duplicate rows in a table?
    1.  SELECT name FROM table1 GROUP BY name HAVING COUNT(*) > 1
