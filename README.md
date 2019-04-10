# SQL Teaching
### [Lesson 1: SELECT *](https://www.sqlteaching.com/#!select)
```SQL
SELECT * 
FROM family_members;
```

### [Lesson 2: SELECT specific columns](https://www.sqlteaching.com/#!select_columns)
```SQL
SELECT name, species
FROM family_members;
```

### [Lesson 3: WHERE ... Equals](https://www.sqlteaching.com/#!where_equals)
```SQL
SELECT *
FROM family_members
WHERE species = 'dog';
```

### [Lesson 4: WHERE ... Greater than](https://www.sqlteaching.com/#!where_greater_than)
```SQL
SELECT * 
FROM family_members
WHERE num_books_read > 190;
```

### [Lesson 5: WHERE ... Greater than or equal](https://www.sqlteaching.com/#!where_greater_than_or_equal)
```SQL
SELECT * 
FROM family_members
WHERE num_books_read >= 180;
```

### [Lesson 6: AND](https://www.sqlteaching.com/#!and)
```SQL
SELECT *
FROM friends_of_pickles
WHERE species = 'dog' AND height_cm < 45;
```

### [Lesson 7: OR](https://www.sqlteaching.com/#!or)
```SQL
SELECT *
FROM friends_of_pickles
WHERE species = 'dog' OR height_cm < 45;
```

### [Lesson 8: IN](https://www.sqlteaching.com/#!in)
```SQL
SELECT *
FROM friends_of_pickles
WHERE species NOT IN('cat', 'dog');
```

### [Lesson 9: DISTINCT](https://www.sqlteaching.com/#!distinct)
```SQL
SELECT DISTINCT SPECIES
FROM friends_of_pickles
WHERE height_cm > 50;
```

### [Lesson 10: ORDER BY](https://www.sqlteaching.com/#!order_by)
```SQL
SELECT *
FROM friends_of_pickles
ORDER BY height_cm DESC;
```

### [Lesson 11: LIMIT # of returned rows](https://www.sqlteaching.com/#!limit)
```SQL
SELECT *
FROM friends_of_pickles
ORDER BY height_cm DESC LIMIT 1;
```

### [Lesson 12: COUNT(*)](https://www.sqlteaching.com/#!count)
```SQL
SELECT COUNT(*)
FROM friends_of_pickles;
```

### [Lesson 13: COUNT(*) ... WHERE](https://www.sqlteaching.com/#!count_where)
```SQL
SELECT COUNT(*)
FROM friends_of_pickles
WHERE species = 'dog';
```