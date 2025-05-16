# Program to Define a Class `Employee` with a Public Method `show()` to Display Employee Details
# Aim
To create a class `Employee` with a public method `show()` that displays the details of the employee, including attributes like employee name, ID, and department.

# Procedure
1. Define the class `Employee` with attributes like `emp_id`, `emp_name`, and `emp_department`.
2. Implement a public method `show()` within the class to display the employee details.
3. Create an object of the class and call the `show()` method to display the employee details.
# Program
```python
class Employee:
    # constructor
    def __init__(self, name, salary):
        # public data members
        self.name = name
        self.salary = salary
        
        
# creating object of a class
emp = Employee('Jessa', 10000)

# accessing public data members
print("Name: ", emp.name, 'Salary:', emp.salary)
print("Name: ", emp.name, 'Salary:', emp.salary)

# call public method of the class

```

# Output

![image](https://github.com/user-attachments/assets/a7f4b666-6652-4a92-a598-9c0ccf175b0e)

# Result
The program successfully defines the `Employee` class, creates an instance, and displays the employee details using the `show()` method.

