---
tags:
  - SQL
links:
  - "[[SQL]]"
---
# Что такое View?
Представление - это механизм для простого запроса данных. В отличие от таблиц, представления не предназначены для хранения данных и занимают места на дисковом пространстве.

Пример создания представления
```sql
CREATE VIEW customer_vw
 (customer_id,
  first_name,
  last_name,
  email 
 )
AS
SELECT 
  customer_id,
  first_name,
  last_name,
  concat(substr(email,1,2), '*****', substr(email, -4)) email
FROM customer;
```

# Почему используют View?
## Безопасность данных
...
## Агрегация данных
...
## Сокрытие сложности
...
