# prime-number
Author- Hrithk Mahato
<br>
This python code print first 10 prime number
<br>
count=0
<br>
for i in range(2,30):
<br>
    flag=False
    <br>
    for j in range(2,int(i/2)+1):
    <br>
        if(i%j==0):
        <br>
            flag=True
            <br>
            break
            <br>
    if(flag==False):
    <br>
        count+=1
        <br>
        print(count,i)
