SQL 
SELECT * = SELECIONAR TODO DE ~SELECT ALL~
    (PUEDEN SELECCIONARSE TABLAS ESPECIFICAS Y DIVIDIRLAS CON (,) ~ESPECIFIC TABLES IT IS DIVIDE WITH (,)~
FROM = INDICA LA FUENTE DE SELECCIONAR ~INDICATE THE SOURCE OF INFORMATION~
ORDER BY = ORDENA LA INFORMACIÓN ~ ORDER OF INFORMATION ~
WHERE = PARA FILTRAR REGISTROS ~ TO FILTER RECORDS 
LIKE (=) = SELECCIONA UNA SALIDA DE UNA TABLA ~ SELECT THE OUTPUT FROM A TABLE IN SQL~
      EXAMPLE: 
      SELECT*
      FROM houses
      ORDER BY colors
      WHERE houses LIKE 'red' 
AND = agrega 1 o mas condiciones ~ add one or more conditions~ 
OR = agrega una u otra condicion ~ add one or other condition ~
NOT = niega una condicion ~ negates a condition~

EXAMNPLE:

SELECT *
FROM log_in_attempts
WHERE login_time > '18:00' AND success = FALSE;


SELECT * 
FROM log_in_attempts 
WHERE login_date = '2022-05-09' OR login_date = '2022-05-08';



SELECT * 
FROM log_in_attempts 
WHERE NOT country LIKE 'MEX%';



SELECT * 
FROM employees 
WHERE department = 'Marketing' AND office LIKE 'East%';


SELECT * 
FROM employees 
WHERE department = 'Finance' OR department = 'Sales';
<img width="1426" height="237" alt="image" src="https://github.com/user-attachments/assets/07cb9800-db04-4847-a554-8cd1f73d87ce" />


SELECT * 
FROM employees 
WHERE NOT department = 'Information Technology';

****<img width="983" height="131" alt="image" src="https://github.com/user-attachments/assets/57be90ae-1592-43ab-8cc0-584f0fab8eb1" />




              
