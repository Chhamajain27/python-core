# What is function

 Python Functions is a block of related statements designed to perform a computational, logical, or evaluative task.

# Importance of functions:

-Resusability

-Abstraction

-Modularity


```python
#case 1: no arguments no return 
print("hello")    
def add():
    num1,num2=input("enter the two numbers").split(",")
    num1=int(num1)
    num2=int(num2)
    result=num1+num2
    print(result)
print("before function calling")
add()
print("after function caling")

```

    hello
    before function calling
    enter the two numbers2,4
    6
    after function caling
    


```python
#case 2: with arguments and no return
def add(num1,num2):
    result=num1+num2
    print(result)
    print("inside function calling")
n1,n2=input("enter the numbers").split(",")
print("before function calling")
n1=int(n1)
n2=int(n2)
add(n1,n2)
print("after function calling")
```

    enter the numbers1,2
    before function calling
    3
    inside function calling
    after function calling
    


```python
## case 3: without argument with return type
print("hello")    
def add():
    num1,num2=input("enter the two numbers").split(",")
    num1=int(num1)
    num2=int(num2)
    result=num1+num2
    return result
print("before function calling")
a=add()
print("after function caling")
print(a)

```

    hello
    before function calling
    enter the two numbers4,6
    after function caling
    10
    


```python
## case 3: with argument with return type
print("hello")
def add(a,b):
    l=[1,2,3,4]
    result=num1+num2
    return result,l
    print("inside the function")
num1,num2=input("enter the two numbers").split(",")
num1=int(num1)
num2=int(num2)
print("before function calling")
a,b=add(num1,num2)
print("after function caling")
print(a)
print(b)
```

    hello
    enter the two numbers7,8
    before function calling
    after function caling
    15
    [1, 2, 3, 4]
    

# Functions can be

- built-in 


- user-defined. 


# builtin functions:

- input()
- len()
- pow()
- id()
- ord()
- round(
- chr()
- type()
- print()
- float()
- int()
- str()
- help()

etc.


```python

```
