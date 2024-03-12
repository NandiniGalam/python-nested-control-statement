# python-nested-control-statement
for i in range(3):
  for j in range(3):
    print("*",end="  ")
  print()  


#method 2 using list
a=[]
for i in range(3):
  x=[]
  for j in range(3):
    x.append("*")
  a.append(x)
print(a)
for i in a:
  print(*i,sep=" ")



#using only 1 for loop
a="*"
for i in range(3):
  print(a*3)
