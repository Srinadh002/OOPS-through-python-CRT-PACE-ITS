class Employee1:
    def __init__(self, name, age, salary): 
        self.name = name
        self.age = age
        self.salary = salary

class ChildEmployee(Employee1):
    def __init__(self, name, age, salary, emp_id):  
       self.name=name
       self.age=age
       self.salary=salary
       self.id=id


emp1 = Employee1('srinadh', 18, 1000000000000)
print(emp1.age)
print(emp1.name)
print(emp1.salary)
