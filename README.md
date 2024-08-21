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
```
INSERT INTO employees
	(id, name, role, salary, age, address, phone)
VALUES
	(1, "RaviNarayan", "Launch Executive", 14000, 21, "Surat", 9510421589);
```

## 👉Adding Multiple Details in Field Names (Table)👈
```
INSERT INTO employees
	(id, name, role, salary, age, address, phone)
VALUES
	(1, "RaviNarayan", "Launch Executive", 14000, 21, "Surat", 9510421589),
	(2, "Sajid", "Electrician", 24000, 22, "Surat", 9316555468);
```

## 👉Read or Find all Details in Field Names (Table)👈
```
SELECT * FROM employees;
```

## 👉Read or Find specific Details in Field Names (Table)👈
```
SELECT name, salary FROM employees;
```

## 👉Read or Find specific Details in Field Names (Table) by their Category 👈
```
SELECT name, salary FROM employees WHERE role = "Launch Executive";
```

## 👉Search Details in Field Names (Table) by name Containing "Ra" 👈
```
SELECT * FROM employees WHERE name like "Ra%";
```

## 👉Find employees details who are older than 20 and earning more than 20,000👈
```
SELECT * FROM employees WHERE age > 20 AND salary > 20000;
```

## 👉Change the salary of an employee with ID 1👈
```
UPDATE employees SET salary = 17000 WHERE id = 1;
```

## 👉Update the address for employees "Launch Executive" role:👈
```
UPDATE employees SET address = "Udhana, Surat" WHERE role = "Launch Executive";
```

## 👉Remove an employee with ID 4👈
```
DELETE FROM employees WHERE id = 4;
```

## 👉Delete all employees under 20 👈
```
DELETE FROM employees WHERE age < 20;
```
