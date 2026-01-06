n=int(input("enter the limit less than 9999999999:"))
small =9999999999
for i in range (1,n+1):
print("enter ",i,end ='')
a=int(input("th number:"))
if a<small:
small=a
print("smallest no. is:",small)

Output:
enter the limit less than 9999999999:8
enter 1th number:6
enter 2th number:5
enter 3th number:4
enter 4th number:4
enter 5th number:9
enter 6
th number:7
enter 7th number:8
enter 8th number:0
smallest no. is: 0
