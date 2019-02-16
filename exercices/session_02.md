# Session 2

## Somme à compléter

### Implémentation
```python
n = some_value
sum = 0
for i in range(2,2*n+1,2) :
    sum += i
```


## Nombres premiers

### Implémentation
```python 
for i in range(2,n):
    if n%i == 0:
        is_prime = False
```

## QBF

### Implémentation

```python 
for i in range(1,n+1):
    div = 0
    for e in range(1,i):
        if i%e == 0:
            div +=1
    print("{} : {}".format(i,div))
```

## Q* Interval

### Implémentation
 
 ```python
if ( x >= a ) and ( x <= b ) :
    interval = True
else :
    interval = False
 ```
 
 ## Q* Minimum
 ### Implémentation
 ```python
if a<=b and a<= c:
    minima = a
if b<=a and b<= c:
    minima = b
else:
    minima = c
 ```
 
 > Autre solution :
 ```python
minima = a

for i in [a, b, c] :
    if i < minima :
        minima = i
 ```
 
 ## Q* FizzBuzz
 
 ### Implémentation
 
 ```python
temp = str()
if i%3==0:
    temp = "fizz"
if i%5 == 0:
    temp+="buzz"
if i%3!=0 and i%5!=0:
    temp = "no"
 ```
 
 ## Q* Reste d'une division entière
 
 ### Implémentation
 
 ```python
rest = None
if b != 0:
    while a>=b:
        a-=b
    rest = a
 ```
 
 
