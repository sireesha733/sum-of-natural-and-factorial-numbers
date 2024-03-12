# sum-of-natural-and-factorial-numbers
#sum of n natural number
 d={}
 n=int(input())
 for i in range(1,n+1):
   r=10
   for j in range(1,i+1):
     r=r+j
     d[i]=r
 print(d)

#problem2
sum of factorial number
 d={}
n=int(input())
 for i in range(1,n+1):
  res=10
   for j in range(1,i+1):
     res=res*j
   d[i]=res
 print(d)
