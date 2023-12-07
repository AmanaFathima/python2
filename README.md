# python2
def happy_birthday(name,age):
    print(f"happy birthday {name}")
    print(f"you are {age} years old!!")
    print("happy birthday to you")
    print()
happy_birthday("elle",20)
happy_birthday("lily",39)
happy_birthday("kumar",80)

def display_invoice(username,amount,due_date):
    print(f"hello {username}")
    print(f"your bill ${amount:.2f} is due {due_date}")
display_invoice("hani",23,"01/02")

def add(x,y):
    z=x+y
    return z
def substract(x,y):
    z=x-y
    return z
def multiply(x,y):
    z=x*y
    return z
def divide(x,y):
    z=x/y
    return z
print(add(1,4))
print(substract(1,4))
print(multiply(1,4))
print(divide(1,4))

def create_name(first,last):
    first=first.capitalize()
    last=last.capitalize()
    return first + " " + last
fullname=create_name("amana","fathima")
print(fullname)
