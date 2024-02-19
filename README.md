# First_Project
# Basic Calculator in Python

def add(x,y):
    return(x+y)
    
def sub(x,y):
    return(x-y)
    
def multi(x,y):
    return(x*y)
    
def divide(x,y):
    return(x/y)



while True:
    
    operator = input('select from add, sub, multi, divide')
    
    if operator not in ['add','sub','multi','divide']:
        continue
        

    n1 = int(input('enter num 1: '))
    n2 = int(input('enter num 2: '))

    if operator == 'add':
        print('sum of two number: ', add(n1,n2))
    elif operator == 'sub':
        print('sub of two number: ', sub(n1,n2))
    elif operator == 'multi':
        print('multiplication of two number: ', multi(n1,n2))
    elif operator == 'divide':
        print('division of two number: ', divide(n1,n2))
    else:
        print('wrong input')
    continue
    
    
