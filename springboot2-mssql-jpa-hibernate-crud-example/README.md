-- auto-generated definition
create table speedlayer.employees
(
    id            int identity
        constraint employees_pk
            primary key nonclustered,
    first_name    varchar(1000) not null,
    last_name     varchar(1000) not null,
    email_address varchar(1000) not null
)
go