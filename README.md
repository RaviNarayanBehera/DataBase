# DataBase

## 👉 Adding Field Names 👈
### Ex: field names: id, name, role, salary, age, phone
```
CREATE TABLE "employees" (
	"id"	INTEGER NOT NULL,
	"name"	TEXT NOT NULL,
	"role"	INTEGER NOT NULL,
	"salary"	INTEGER NOT NULL,
	"age"	INTEGER NOT NULL,
	"address"	INTEGER,
	"phone"	INTEGER NOT NULL
);
```
## 👉Adding Details in Field Names👈
### Adding full details on field names... 
```
INSERT INTO employees
	(id, name, role, salary, age, address, phone)
VALUES
	(1, "RaviNarayan", "Launch Executive", 14000, 21, "Surat", 9510421589);
```
