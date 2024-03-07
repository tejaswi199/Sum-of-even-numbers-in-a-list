#Approach-1
n=int(input())
a=list(map(int,input().split()))
res=0
for i in range(n):
  if a[i]%2==0:
    res=res+a[i]
print(res)

#Approach-2
n=int(input())
a=list(map(int,input().split()))
res=0
for i in a:
  if i%2==0:
    res=res+i
print(res)
