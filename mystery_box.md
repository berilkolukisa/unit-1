# Here are my answers to the mystery box exercises.
##1

##2

## mystery_box3
```.py
number1=int(input('Please enter your first number'))
number2=int(input('Please enter your second number'))
number3=int(input('Please enter your third number'))

def lcm_calculator(number1,number2):
    if number1 > number2:
        greater =number1
    else:
        greater =number2
    while(True):
        if((greater % number1==0)and(greater % number2==0)):
            lcm=greater
            break
        greater +=1
    return lcm

def lcm_calculator2(lcm1,number3):
    if lcm1 > number3:
        greater =lcm1
    else:
        greater =number3
    while(True):
        if((greater % lcm1==0)and(greater % number3==0)):
            finallcm=greater
            break
        greater +=1
    return finallcm

lcm1=lcm_calculator(number1,number2)
finallcm=lcm_calculator2(lcm1,number3)
print(finallcm)
```



##4
