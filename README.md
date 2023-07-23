# Class-232

select customers.first_name, customers.last_name, company_orders.date, company_orders.total_amount,
from customers inner join company_orders on customers.id = company_orders.customer_id 

Error

(psycopg2.errors.SyntaxError) syntax error at or near "from" LINE 1: ...company_orders.date, company_orders.total_amount, from custo... ^ [SQL: select customers.first_name, customers.last_name, company_orders.date, company_orders.total_amount, from customers inner join company_orders on customers.id = company_orders.customer_id ] (Background on this error at: https://sqlalche.me/e/14/f405)
