# Saurav-python
1.Write a function employe_deatails(name , age, departement) that prints employee information using keyword arguments and default argument department='CSE' call the function with argument in different orders.

def employee_details(name, age, department='CSE'):
    print("Employee Information")
    print("Name:", name)
    print("Age:", age)
    print("Department:", department)
    print()

employee_details(name="Saurav", age=19, department="IT")

employee_details(age=30, name="Anita", department="HR")

employee_details(name="Amit", age=22)  

employee_details(department="Finance", name="Riya", age=28)


2. Implement recursive function for finding factorial of a number.

def factorial(n):
    if n == 0 or n == 1: 
        return 1
    else:
        return n * factorial(n-1)

print(factorial(5))


3. Write a function filter_even_square(numbers) that takes a list of integers and return a new list containing the squares of only even numbers using list comprehension.

def filter_even_square(numbers):
    return [n**2 for n in numbers if n % 2 == 0]

nums = [1, 2, 3, 4, 5, 6]
result = filter_even_square(nums)
print(result)


4. Create a string and show string slicing, replication, concatenation and replacement.

s = "hello World"
print(s[0:5])
print(s[::-1])

print(s * 2)

s2 = "python"
print(s + s2)

print(s.replace("world", "Saurav"))

