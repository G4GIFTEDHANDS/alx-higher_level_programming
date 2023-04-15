0x0F Python Object-Relational Mapping
This repository contains tasks for the ALX software engineering curriculum, specifically the Python Object-Relational Mapping (ORM) project. The ORM project aims to introduce students to the concept of object-relational mapping and how to interact with relational databases in Python.

Files
Below is a list of all the files in this repository, along with a brief description of each file:

Filename and Description
0-select_states.py	A Python script that lists all the states from the hbtn_0e_0_usa database.
1-filter_states.py	A Python script that lists all the states with a name starting with N from the hbtn_0e_0_usa database.
2-my_filter_states.py	A Python script that takes in an argument and lists all the states with a name starting with the argument value from the hbtn_0e_0_usa database.
3-my_safe_filter_states.py	A Python script that takes in an argument and lists all the states with a name starting with the argument value from the hbtn_0e_0_usa database. This script is safe from SQL injection attacks.
4-cities_by_state.py	A Python script that lists all the cities from the hbtn_0e_4_usa database.
5-filter_cities.py	A Python script that takes in the name of a state as an argument and lists all the cities of that state from the hbtn_0e_4_usa database.
7-model_state_fetch_all.py	A Python script that lists all State objects from the hbtn_0e_6_usa database using SQLAlchemy.
8-model_state_fetch_first.py	A Python script that prints the first State object from the hbtn_0e_6_usa database using SQLAlchemy.
9-model_state_filter_a.py	A Python script that lists all State objects that contain the letter a from the hbtn_0e_6_usa database using SQLAlchemy.
10-model_state_my_get.py	A Python script that prints the State object with the name passed as argument from the hbtn_0e_6_usa database using SQLAlchemy.
11-model_state_insert.py	A Python script that adds the State object "Louisiana" to the hbtn_0e_6_usa database using SQLAlchemy.
12-model_state_update_id_2.py	A Python script that changes the name of a State object with id = 2 to "New Mexico" in the hbtn_0e_6_usa database using SQLAlchemy.
13-model_state_delete_a.py	A Python script that deletes all State objects that contain the letter a from the hbtn_0e_6_usa database using SQLAlchemy.
model_state.py	A Python module that contains the definition of a State class and an instance Base of declarative_base() from SQLAlchemy.
model_city.py	A Python module that contains the definition of a City class and an instance Base of declarative_base() from SQLAlchemy.
relationship_city.py	A Python module that contains the definition of a City class and an instance Base of declarative_base() from SQLAlchemy.
