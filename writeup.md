# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
A key programming concept that I better understood while completing this assignment was how variables work in Python, they are also used to store information. In the pythonic way it uses less characters and it is easier to make compared to in Javascript due to the way that it is structured.   


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
The overall movie chatbot system works by first, the user types in a question like "who acted in Casper?", then the pattern-matching chatbot system goes through its database(movies.py), searches for the movie Casper, searches the actors who acted in that movie and then return those actors to the user.


3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
Some real-world applications where this type of pattern-matching chatbot system could be useful would be for programmers programming search engines like Google. This could be useful to them because they need to make a pattern-matching system where whenever someone searches something up like a question then their system checks if what the person searched up matches what is in their database by using if and else statements, and then gives the individual the answer they were looking for based on the pattern-matching that was performed.