It has been forever since I've used VSCode to take notes and of courese post them. I've decided to come back because I tend to forget the terminology for SQL and sqlite, so hopefully these notes will save me a good deal of time in the future. Off we go:

To start of, we open the terminal and write "sqlite myfile.db" or whatever name you prefer. db stands for database.

SQL commands:

create table characters(name text, level int, power text);

insert into characters(name, level, power) values("Necromancer", 99, "summoning");
insert into characters values("Paladin", 25, "blessings");
insert into characters(name, power) values("Druid", "nature");

select * from characters;
select name, power from characters;

update characters set level=40 where name="Druid";

delete from characters where power="nature";

select * from characters order by level desc;

select * from characters order by power collate nocase;

select * from characters order by level, name;

sqlite3 commands:

.backup mybackup
.tables (displays the names of the created tables)
.schema (displays the tables as well as their parameters)
.dump (displays the tables as well as the inserted values)
.exit
