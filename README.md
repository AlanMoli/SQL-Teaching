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