# PySpark DVD Rental Data Analysis

This project contains a set of analytical tasks performed using **PySpark DataFrame API** on the DVD Rental (Sakila) demo database.

The objective of the project is to practice large-scale data processing, joins, aggregations, filtering, and window functions using PySpark without using SQL queries.

---

# Project Objectives

Using PySpark, the project solves the following business problems:

1. Output the number of movies in each category sorted in descending order.
2. Output the top 10 actors whose movies were rented the most.
3. Output the movie category on which the most money was spent.
4. Output the names of movies that are not in inventory.
5. Output the top 3 actors who appeared most in movies in the **Children** category (including ties).
6. Output cities with the number of active and inactive customers.
7. Output the movie category with the highest total rental hours:
   - For cities starting with the letter **"a"**
   - For cities containing the symbol **"-"**

---

# Technologies Used

- Python
- PySpark
- Apache Spark
- DataFrame API
- Window Functions

---

# Dataset

The project uses the **DVD Rental / Sakila Database**.

Required CSV files:

- film.csv
- category.csv
- film_category.csv
- actor.csv
- film_actor.csv
- inventory.csv
- rental.csv
- payment.csv
- customer.csv
- address.csv
- city.csv

---

# Project Structure



```bash
pyspark-dvd-rental-analysis/
│
├── data/
│   ├── film.csv
│   ├── category.csv
│   ├── film_category.csv
│   ├── actor.csv
│   ├── film_actor.csv
│   ├── inventory.csv
│   ├── rental.csv
│   ├── payment.csv
│   ├── customer.csv
│   ├── address.csv
│   └── city.csv
│
├── SakilaAnalysis_Pyspark.ipynb
└── README.md
