//part3


# list=[1,5,11,14,15,17,20,25,27,30]
# ask=int(input("enter a number:"))
# if list.count(ask)==0:
#     print("Not found in our list")
# if list.count(ask)==1:
#     n=list.index(ask)+1
#     print("found,position:",n)

# -------------------------------------------

ask=input("Enter a list of number , seperate by ' ':")
a=list(ask.split(' '))
a=list(map(int,a))
sum=0
for i in range(len(a)):
    sum=sum+a[i]
print("sum of all entered number:",sum)
