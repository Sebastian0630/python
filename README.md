# python
import math

print("kwadrat") 
a = int(input("Podaj podstawę"))
print(a**2)

print("prostokąt")
b = int(input("Podaj podstawę"))
c = int(input("Podaj wysokość"))
print(b*c)

print("trójkąt")
d = int(input("Podaj podstawę"))
e = int(input("Podaj wysokość"))
print((d*e)/2)

print("trapez")
f = int(input("Podaj podstawę"))
g = int(input("Podaj drugą podstawę"))
h = int(input("Podaj wysokość"))
print(((f+g)*h)/2)

print("równoległobok")
i = int(input("Podaj podstawę"))
j = int(input("podaj wysokość"))
print(i*j)

print("koło")
k = int(input("Podaj promień"))
print(math.pi*k**2)

print("romb")
l = int(input("Podaj przekątną"))
m = int(input("Podaj drugą przekątną"))
print((l*m)/2)

print("deltoid")
n = int(input("Podaj przekątną"))
o = int(input("Podaj deugą przekątną"))
print((n*o)/2)


import math

a = float(input("a ="))
b = float(input("b ="))
c = float(input("c ="))
if a + b >= c and a +c >=b and b + c >= a:
    print("to jest tr")
    p = 1/2*(a+b+c)
    P = math.sqrt(p*(p-a)*(p-b)(p-c))
    print(f"pole powierzchni tr= {P}")
    if a**2 + b**2 == c**2 or c**2 + b**2 == a**2 or a**2 + c**2 == b**2:
        print("jest prostokatny")
    else:
        print("nie jest prostokatny")
else:
    print("nie jest5")
