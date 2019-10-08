# raja

n=int(input("please  enter the number"))
def printpascal(n):
    for line in range (1,n+1):
        v=1
        for i in range (1,line+1):
            print(v, end=' ')
            v=int(v*(line-i)/i)
        print(' ')
printpascal(n)
