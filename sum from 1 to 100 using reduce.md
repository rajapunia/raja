# raja

from functools import reduce
a=range(0,101)

sum=reduce(lambda a,x:a+x,a)
print(sum) 
