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