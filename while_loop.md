# Solution to exercises on Snakify 
## Exercise 1 List of squares
```.py
number=int(input('Please enter your number.'))
int = 1
while int**2 <= number:
    print(int**2)
    int += 1
```

## Exercise 2 Least divisor
```.py
n=int(input('Please enter your number.'))
i = 2
while n%i!=0:
    i += 1 
print (i)
```

## Exercise 3 The power of two
```.py
N=int(input('Please enter your number.'))
x = 1
while 2**x <= N:
    x += 1 
print(x-1 ,2**(x-1))
```

## Exercise 4 Morning jog

## Exercise 5 The length of the sequence
```.py
l=0
n=int(input())
while n != 0:
    l += 1
    n=int(input())
print(l)
```

## Exercise 6 The sum of the sequence
```.py
n=int(input())
sum=0
while n> 0:
    sum+=n
    n=int(input())
print(sum)
```

## Exercise 7 The average of the sequence
```.py
num=int(input())
sum=0
div=0
while num != 0 :
    sum += num
    div +=1
    num=int(input())
print(sum/div)
```

## Exercise 8 The maximum of the sequence
```.py
n=int(input())
big=0
while n != 0:
    if n > big:
         big  = n
    n=int(input())
print(big)
```





    








    










 
