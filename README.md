l=[]
n=int(input('enter no:'))
for i in range(1,n+1):
    b=int(input('enter elemnts:'))
    l.append(b)
e=[]
o=[]
for j in l:
    if(j%2==0):
        e.append(j)
    else:
        o.append(j)
print('even:',e)
print('odd:',o)
