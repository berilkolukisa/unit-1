# Solution to exercises on Snakify

## Exercise 1 Series-1
```.py
a=int(input('Please enter your first number'))
b=int(input('Please enter your seond number.'))
if abs(a <= b):
  for num in range(a,b+1):
    print(num)
else:
  print('0')
```

## Exercise 2 Series-2
```.py
a=int(input('Please enter your first number.'))
b=int(input('Please enter your second number.'))
if b>a:
    for num in range (a,b+1):
        print(num)
if a>b:
    for num in range (a,b-1,-1):
        print(num)
if a==b:
    print(a)
```

## Exercise 3 Sum of ten numbers
```.py
sum=0
for i in range(1,11):
    numbers=int(input('Please enter your numbers.'))
    sum += numbers
print(sum)
```

## Exercise 4 Sum of N numbers
```.py
sum=0
n=int(input('Please enter your numbers.'))
for i in range(1,n+1):
    n=int(input('Please enter your numbers.'))
    sum += n
print(sum)
```

## Exercise 5 Sum of cubes
```.py
s=0
number=int(input('Please enter your number.'))
for i in range (1,number+1):
    s+=i**3
print(s)
```

## Exercise 6 Factorial
```.py
factorial=1
sum=0
n=int(input('Please enter your number.'))
for i in range (1,n+1):
    factorial *= i
    sum += factorial
print(sum)
number=int(input('Please enter the number you want to calculate factorial of.'))
factorial=1
for i in range (1,number+1):
    factorial=factorial*i
print(factorial)
```

## Exercise 7 Number of Zeros
```.py
zeronumber=0
n=int(input('Please enter your numbers.'))
for i in range (n):
    n = int(input("please enter a number"))
    input==n
    if n==0:
        zeronumber += 1
print(zeronumber)
```

## Exercise 8 Adding Factorials
```.py
factorial=1
sum=0
n=int(input('Please enter your number.'))
for i in range (1,n+1):
    factorial *= i
    sum += factorial
print(sum)
```
## Exercise 9 Ladder

## Exercise 10 Lost Card

