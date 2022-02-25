# Feb-25-assignment-
n=int(input())
l=[]
t=[]
for i in range(n):
    x=int(input())
    l.append(x)
for i in range(n):
    if l[i]!=0:
        t.append(l[i])
print('count=',len(t))
print(t)
