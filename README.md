//part2

# list=['1.blue','2.red','3.teal','4.green']
# print("our colour list:",*list,sep='\n')
# ask=input("Item to delete:")
# print("our new color list:")

# red=str("1.red")
# teal=str("2.teal")
# green=str("3.green")

# if ask==1:
#     list.remove('1.blue')
#     list[1]=red
#     list[2]=teal
#     list[3]=green
#     print(*list,sep='\n')
# if ask==2:
#     list.remove('2.red')
#     list[2]=teal
#     list[3]=green
#     print(*list,sep='\n')
# if ask==1:
#     list.remove('3.teal')
#     list[3]=green
#     print(*list,sep='\n')
# if ask==4:
#     list.remove('4.green')
#     print(*list,sep='\n')
# if ask=="blue":
#     list.remove('1.blue')
#     list[1]=red
#     list[2]=teal
#     list[3]=green
#     print(*list,sep='\n')
# if ask=="red":
#     list.remove('2.red')
#     list[2]=teal
#     list[3]=green
#     print(*list,sep='\n')
# if ask=="teal":
#     list.remove('3.teal')
#     list[3]=green
#     print(*list,sep='\n')
# if ask=="green":
#     list.remove('4.green')
#     print(*list,sep='\n')

# ---------------------------------

from turtle import*


color("red")
begin_fill()
forward(100)
end_fill()

color("blue")
begin_fill()
forward(100)
end_fill()

color("teal")
begin_fill()
forward(100)
end_fill()

color("green")
begin_fill()
forward(100)
end_fill()


mainloop()
