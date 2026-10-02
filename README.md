# DAY-3-MY-Learning
EXTRA OPERATORS IN SQL
1.LIKE  2.AS  3.BETWEEN  4.UNION 5.UNION ALL  6.INTERSECT   8.EXCEPT


 LIKE:  (%) = any number of chars, _ = exactly one char.


 AS: alias (rename a column or table in the output)


 BETWEEN: range, both ends inclusive.


 UNION: combines two results and removes duplicates.


 UNION ALL: same, but keeps duplicates (faster)


 INTERSECT: only rows present in both results


 EXCEPT: rows in the first result but not in the second (MINUS in Oracle)

 Rules for UNION / INTERSECT / EXCEPT:

1.Same number of columns in both queries
2.Compatible data types in matching positions
3.Column names come from the first query
