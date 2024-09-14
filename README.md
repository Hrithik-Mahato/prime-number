# prime-number
Author- Hrithk Mahato
This python code print first 10 prime number

count=0
for i in range(2,30):
    flag=False  
    for j in range(2,int(i/2)+1):
        if(i%j==0):
            flag=True
            break
    if(flag==False):
        count+=1
        print(count,i)
