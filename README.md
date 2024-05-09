By connecting postgre sql database to python through python libraries like psycopg2
we implement transaction which follows ACID properties 


This is the list of transactions to be implemented:

Trans_1 - The product p1 is deleted from Product and Stock.
Trans_2 - The depot d1 is deleted from Depot and Stock.
Trans_3 - The product p1 changes its name to pp1 in Product and Stock.
Trans_4 - The depot d1 changes its name to dd1 in Depot and Stock.
Trans_5 - We add a product (p100, cd, 5) in Product and (p100, d2, 50) in Stock.
Trans_6 - We add a depot (d100, Chicago, 100) in Depot and (p1, d100, 100) in Stock.
