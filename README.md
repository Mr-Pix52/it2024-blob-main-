import math
d = int(input())
x=int(input())
a = (((365-(75/(d**3))) / ((3*(d**2))-d))) * 5
b = (412-(125/(d**3))) / ((2*(d**2))) * 4
ax1 = math.floor(a*x)
bx1 = math.floor(a*x)
res = ax1+bx1
print(res)
