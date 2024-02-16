# factors-of-a-number in python
# Approach-1
n = int(input())
for i in range(1,n+1):
  if n%i==0:
    print(i,end=" ")
  # Approach-2
  n = int(input())
a = []
for i in range(1,n+1):
  if n%i == 0:
    a.append(i)
for i in a:
  print(i,end=" ")
