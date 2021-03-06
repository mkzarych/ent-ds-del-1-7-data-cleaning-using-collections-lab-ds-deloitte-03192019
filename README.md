
# Data Cleaning Using Collections - Lab


## Introduction
In the last lesson we learned how to iterate over collections. In this one, we'll get some hands on practice applying different transformations to data sets. 

*Remember that this is a lab, so you need to work locally (fork, clone, cd into the directory, run `jupyter notebook`, open the `index.ipynb` file in the browser).*

## Objectives
You will be able to:
* Iterate over common Python collection types
* Use list comprehensions to clean up lists
* Create and iterate over collections of collections

Let's start by setting you up with some data to work with. Make sure to run the cell below so that the variables are declared and available to you in your code:


```python
company_1 = {
    "company_name": "Acme",
    "state_incorporated": "Alabama"    
}
company_2 = {
    "company_name": "Deville",
    "state_incorporated": "California"    
}
company_3 = {
    "company_name": "Goldwater",
    "state_incorporated": "New York"    
}
company_4 = {
    "company_name": "Adolfo",
    "state_incorporated": "New York"    
}
company_5 = {
    "company_name": "Ideo",
    "state_incorporated": "Delaware"    
}
company_6 = {
    "company_name": "Jimmys",
    "state_incorporated": "California"    
}
company_list = [company_1, company_2, company_3, company_4, company_5, company_6]
print(company_list)

```

## Tasks

For each of the following tasks, create a new cell (`Insert - Insert Cell Below`) and then write the code to solve the problem:
You should know how to do these ones (try to complete all of these):
1. Create a List of all of the company names
2. Create a List of all of the states of incorporation
3. Create a Set containing a deduped list of the states of incorporation
4. Create a list of all of the company names for companies incorporated in New York
5. Create a list of all of the company names for companies *not* incorporated in California

These will require a little more Googling/research (just do as many as you can):
6. Create a List of all of the company names in alphabetical order
7. Create a List containing a deduped list of the states of incorporation in alphabetical order
8. Create a List containing a deduped list of the states of incorporation in alphabetical order for companies with a company name starting with the letter A
9. Create a List of Dictionaries, ordered by the company_name and with a third key `name_and_state` in each dictionary containing the company name, a comma and a space and then the state of incorporation (e.g. "Acme, Alabama").


## Summary

Congratulations! You got a whole bunch of practice iterating over collections and retrieving data from them! This week we created a really solid foundation for the rest of the course. We ensured that everyone had Jupyter Notebook set up and working, introduced variables, data types and some common operations for data cleaning. We also learned about collections and how to iterate over them to clean up data.

Next week we're going to introduce you to some more powerful data types for working with data and how to use regular expressions to perform more sophisticated data clean up. By the end of next week you're going to be importing a data set, iterating over it, cleaning it up and saving it to a file like a pro!

