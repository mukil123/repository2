n=int(input("ENTER THE NUMBER OF TERMS:"))
a=0
b=1
count=0
if(n<=0):
   print("ENTER A POSITIVE NUMBER")
elif(n==1):
   print("FIBONACCI SERIES UPTO",n,":")
   print(a)
else:
   print("FIBONACCI SERIES:")
   while(count<n):
       print(a)
       nth=a+b
       a=b
       b=nth
       count+=1
