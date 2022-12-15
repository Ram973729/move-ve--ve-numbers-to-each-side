# move positive & negative numbers-to-each-side
l=[]
n=int(input())
ol=list(map(int,input().split()))
nl=[]
zl=[]
for i in range(0,n):
    if ol[i]<0:
        zl.append(ol[i])
    else:
        nl.append(ol[i])
l=zl+nl
for i in l:
    print(i,end=' ')
