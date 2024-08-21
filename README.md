# DataBase

## 👉 Adding Field Names (Table) 👈
### Ex: field names: id, name, role, salary, age, phone
```
CREATE TABLE "employees" (
	"id"	INTEGER NOT NULL UNIQUE,
	"name"	TEXT NOT NULL,
	"role"	TEXT NOT NULL,
	"salary"	INTEGER NOT NULL,
	"age"	INTEGER NOT NULL,
	"address"	TEXT,
	"phone"	INTEGER NOT NULL
);
```
## 👉Adding Details in Field Names (Table)👈
### Adding full details on field names... 
```
INSERT INTO employees
	(id, name, role, salary, age, address, phone)
VALUES
	(1, "RaviNarayan", "Launch Executive", 14000, 21, "Surat", 9510421589);
```
