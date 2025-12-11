tpl=eval(input("Enter Tuple : "))
length=len(tpl)
mean=sum=0
for i in range(0,length):
  sum+=tpl[i]
mean=sum/length
print("Given tuple is : ",tpl)
print("The Mean of given tuple is : ",mean)  



output:
Enter Tuple : 2,4,6,8
Given tuple is :  (2, 4, 6, 8)
The Mean of given tuple is :  5.0
