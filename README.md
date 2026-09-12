## Animal Shelter Dashboard
CRUD dashboard and database project for SNHU CS-340.

## Project Overview

This project uses MongoDB as the database and a Python CRUD module to manage animal shelter records. A Dash dashboard provides an interactive interface that allows users to filter and view animal records based on criteria provided by Grazioso Salvare.

## Technologies

- Python
- MongoDB
- PyMongo
- Dash
- Jupyter Notebook

## Features

- MongoDB database containing animal shelter records
- Python CRUD module for database operations
- Interactive Dash dashboard
- Filtering based on rescue criteria
- Interactive data table
- Data visualizations
- Geographic map of selected animal records

## Course Reflection

Q. How do you write programs that are maintainable, readable, and adaptable? Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?

My CRUD Python module was built separately from the dashboard code so that the database operations were handled independently from the user interface. This makes the code easier to understand and modify because changes to database operations did not require rewriting the dashboard code itself. By keeping these basic  CRUD operations independent, it made them easier to read, maintain, and also made them for the future. Because my CRUD Python module is tested and reusable, it can be implemented for other databases or applications by making small, necessary tweaks to the code. 

Q. How do you approach a problem as a computer scientist? Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?

I use the SDLC framework/Agile techniques to approach problems as a computer scientist. I learned the importance of this framework from earlier courses and still implement it in current courses because it provides a step-by-step guideline on how to break down large projects into smaller, easier-to-manage parts. It also helps me keep users' needs in mind because of the heavy emphasis on planning and requirements! I think I would use this same strategy in the future to create databases to meet other client requests. 

Q. What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?

Computer scientists use programming and problem-solving techniques to develop solutions to real-world problems. For example, Grazioso Salvare has researched how specific kinds of dogs are easier to train for certain types of rescue and wants to see if the AAC has dogs that fit the criteria. Instead of combing through paperwork or manually searching through thousands of records in order to find a handful of dogs, the dashboard I created simplifies the search so Grazioso Salvare can quickly identify dogs that meet their requirements. This allows them to spend more time training dogs and helping people instead of manually searching through records for information that can be retrieved through a database query in seconds.
