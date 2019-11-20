# session9

list=['1.123','2.94','3.75','4.69','5.67']
w="5.69"
x="4.75"
y="3.29"
z="2.123"
print("High score:",*list,sep='\n')
ask=int(input("enter new high score:"))
if ask<67:
    print("new high score:",*list,sep='\n')
elif ask<=69:
    a=['5',ask]
    list.remove('5.67')
    print("new high score:",*list,sep='\n')
    print(*a,sep='.')
elif ask<=75:
    b=['4',ask]
    list.remove('4.69')
    list.remove('5.67')
    print("new high score:",*list,sep='\n')
    print(*b,sep='.')
    print(w)
elif ask<=94:
    c=['3',ask]
    list.remove('4.69')
    list.remove('5.67')
    list.remove('3.75')
    print("new high score:",*list,sep='\n')
    print(*c,sep='.')
    print(w,x,sep='\n')
elif ask<=123:
    d=['2',ask]
    list.remove('4.69')
    list.remove('5.67')
    list.remove('3.75')
    list.remove('2.94')
    print("new high score:",*list,sep='\n')
    print(*d,sep='.')
    print(w,x,y,sep='\n')
else :
    e=['1',ask]
    print(*e,sep='.')
    print(w,x,y,z,sep='\n')
