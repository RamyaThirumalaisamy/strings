# strings
#seperate the string's odd and even indices

n=int(input())
for i in  range(0,n):
    b=""
    c=""
    string=input() 
    length=len(string)
    for i in range(0,length):
      if i %2==0:
        b+=string[i]
    

    for i in range(0,length):
        if i%2!=0:
            c+=string[i]

    print(b, c)
    
      
