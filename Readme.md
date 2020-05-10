I recently analyzed the database for a DVD rental company.

Data-set

The database DvdRental has 15 tables. Below are the different tables and a brief description of them.
actor — contains actors data including first name and last name.
film — contains films data such as title, release year, length, rating, etc.
film_actor — contains the relationships between films and actors.
category — contains film’s categories data.
film_category — containing the relationships between films and categories.
store — contains the store data including manager staff and address.
inventory — stores inventory data.
rental — stores rental data.
payment — stores customer’s payments.
staff — stores staff data.
customer — stores customer’s data.
address — stores address data for staff and customers
city — stores the city names.
country — stores the country names.

Database link: https://www.postgresqltutorial.com/postgresql-sample-database/

Before getting started with analyses, I first tried understanding the ERM (Entity Relationship Model) of this database also known as Schema. Here is the Schema below:
