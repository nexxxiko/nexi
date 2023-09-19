"# nexi" 
from math import *
a,b,c=map(int,input().split())
s=[a,b,c]
s.sort()
p=(a+b+c)/2
if(s[0]+s[1]>s[2]):
    Sp = sqrt(p * (p - a) * (p - b) * (p - c))
    print('Ploshad treugolnika',round(Sp,2))
else:
    print('Net takogo treugolnika')
