//part7

list=['1.123','2.94','3.75','4.69']
print("High score:",*list,sep='\n')
ask=input("enter new high score:")
a=['5',ask]
print("new high score:",*list,sep='\n')
print(*a,sep='.')
