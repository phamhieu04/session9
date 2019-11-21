//part6

listQ=['ST  ','BD  ','BTL ','CG  ','DD  ','HBT ']
listDS=["150.300","246.100","333.300","266.800","420.900","318.000"]
listDT=["117.43","9.2240","43.350","12.040","9.9600","10.090"]
listMDDC=[]
print("Quan |","  Km2  ","|","Danso  |","Mat do dan cu")
sum=0
for i in range(len(listQ)):
    a=float(listDS[i])/float(listDT[i])
    listMDDC.append(a)
for i in range(len(listQ)):
    print(listQ[i],"|",listDS[i],"|",listDT[i],"|",listMDDC[i],sep=' ')
for i in range(len(listQ)):
    sum=float(listMDDC[i])+sum
print("Mat do dan cu trung binh:",sum/len(listQ))
