# 18047
# quadratic(abc)

#!/usr/bin/env python
# -*- coding: utf-8  -*-

import math
def quadratic(a,b,c):
    if a==0:
        raise TypeError(a can't be zero)
    if not isinstance(a,(int,float)) or not isinstance(b,(int,float)) or not isinstance(c,(int,float)):
        raise TypeError('Bad operand type')
        
    delta=b**2-4*a*c
    if delta<0:
        return 'no answer'
    elif:
        x1=(-b+math.sqrt(delta))/(2*a)
        x2=(-b-math.sqrt(delta))/(2*a)
        return x1,x2
        
a=input('a=')
b=input('b=')
c=input('c=')



print (quadratic(a,b,c))
    
