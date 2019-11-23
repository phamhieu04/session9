//part1


list=['blue','red','teal','green']
print("our colour list:")
print(*list,sep=",")
ask=str(input("enter a new colour:"))
list.append(ask)
print(*list,sep=",")
