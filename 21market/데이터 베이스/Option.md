create table if not exists kracker_v2.`option`  
(  
    id         int auto_increment  
        primary key,  
    name       varchar(100) not null,  
    sort       int          not null,  
    parentName varchar(100) null  
);

| id | name | sort | parentName | colorCode |
| --- | --- | --- | --- | ---|

