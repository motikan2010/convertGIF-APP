Convert Animation-GIF App
=======================
```sql
create table image(
    id int primary key auto_increment,
    image_name varchar(255) not null unique,
    ipaddr varchar(20),
    created_at datetime not null default current_timestamp,
    deleted_at datetime default null
);
```