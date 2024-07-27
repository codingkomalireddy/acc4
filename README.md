#pattern equilateral triangle
n=4
c=0
for i in range(1,n+1):
    for k in range(n,i,-1):
        print(" ",end='')
    for j in range(1,i+1):
        print(c,end=' ')
        c+=1
    print()    
