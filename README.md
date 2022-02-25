# lab-25.02
Задание 1
from math import sqrt
 
def distance(a, b, c, d):
    return sqrt((a - c) ** 2 + (b - d) ** 2)
 
a = float(input())
b = float(input())
c = float(input())
d = float(input())
print(distance(a, c, b, d))
