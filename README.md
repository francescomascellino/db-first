# db-first
Boolean Class 104 exercise: First DB Template

## DATABASE NAME: used_cars

id: PRIMARY_KEY, INT, UNIQUE, AUTO_INCREMENT, NOTNULL

Company: VARCHAR(10), NOTNULL //es: Mercedes-Benz

Model: VARCHAR(50), NOTNULL //es: Coupè AMG Line GTronic

Fuel: VARCHAR(10), NOTNULL //es: GPL, diersel, gas

Transmission: VARCHAR(10), NOTNULL //es: manual, auto

Horse_power: SMALLINT, NULL //es: 204 CV

Km: FLOAT(5, 3), NULL //es: 30,000 Km

Year: YEAR, NULL

Status: VARCHAR(20), NULL //es: Like new, good, minor scratches, ecc...
Color: VARCHAR(10), NULL

Description: TEXT, NULL

Price: DECIMAL(5, 3), NULL //es: 20.000€

Notes: VARCHAR(255) NULL
