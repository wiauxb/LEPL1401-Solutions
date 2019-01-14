# Session 1

## Median

> a = ... #variable à évaluer  
> b = ... #variable à évaluer  
> c = ... #variable à évaluer  
> median = ... #enregistrez dans cette variable la médiane des trois variables  

### Implémentation
```{python,echo=FALSE}
if (a>=b and a<=c) or (a>=c and a<=b):
    median = a
elif (b>=a and b<=c) or (b>=c and b<=a):
    median = b
else:
    median = c
    print(10)
```

```{python}
import matplotlib.pyplot as plt
plt.plot([0, 2, 1, 4])
plt.show()
```


## QBF
> s0 = ...    #Entier de départ

### Implémentation
```python
print(s0)
while s0 != 1:
    if s0%2 == 0:
        s0 =int(s0/2)
    else:
        s0 = 3*s0+1
    print(s0)
```



## Q* Somme

> x = ... #le nombre  
> result = ... #enregistre dans la variable la somme des c premiers entiers positifs

### Implémentation
```python
result = 0
for i in range(x+1):
    result += i
return result
```



## Q* Polynomial
> y = ...  # valeur du polynôme en abscisse `x`
### Implémentation
```python
y = a*x**6+b*x**2+c
```


## Q* Factorial
> x = ... #le nombre  
> result = ... #enregistre dans cette variable la factorielle de x
### Implémentation
```python
result = 1
for i in range(x,0,-1):
    result *= i
```

## Q* Bathtub with a hole 
### Implémentation
```python
import math
filled_time = 80/11
water_vol = 0
for i in range(math.ceil(filled_time)):
    water_vol += 11
```
