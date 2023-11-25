## SQL databases (SQLite, postgresql, MySql)

Most suitable for apps.

## Document DB (MongoDB, Firestore)

MongoDB: Document store. It's glorified JSON.

Pros:
- good for logs

Cons:
 - have no relations

Firestore bad?

## Graph DBs (Fauna)
bad?
Persmission issues??

## K/V stores (Redis)

Pros: 
- fastest for cache-like solutions


<img width="353" alt="image" src="https://user-images.githubusercontent.com/23092460/184633409-b335db26-7347-4a46-8ac3-63f090d14475.png">



## Первичные ключи в PG (какой юзать)
serial, uuid4, ulid, uuid6

uuid6 (почти тоже самое, что и ulid) vs uui4
uuid6 лучше по перфомансу ()потомучто записи храняться на одной странице, у uuid4 рандом
https://www.youtube.com/watch?v=VC9KbAA_5rE&list=WL&index=1&t=1219s

## Нормальные формы базы данных (relation DB)
https://info-comp.ru/database-normalization
https://www.youtube.com/watch?v=0kq99Y8m0gw&list=WL&index=2
(3 нормальные формы)
