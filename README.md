//part5

listQ=['ST ','BD ','BTL','CG ','DD ','HBT']
listDS=[150.300,246.100,333.300,266.800,420.900,318.000]
a=0
print("Quan ","|","Danso")

for i in range(6):
    print(*listQ[a],"|",listDS[a],sep=' ')
    a=a+1

# tim max
max=listDS[0]
b=1
print("quan co nhieu dan nhat:")
for i in range(5):
    if max<listDS[b]:
        max=listDS[b]
    b=b+1
k=listDS.index(max)
print(listQ[k],"|",max)

# tim min
min=listDS[0]
c=1
print("quan co nhieu dan nhat:")
for i in range(5):
    if min>listDS[c]:
        min=listDS[c]
    c=c+1
m=listDS.index(min)
print(listQ[m],"|",min)
