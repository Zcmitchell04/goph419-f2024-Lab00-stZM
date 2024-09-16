# goph419-f2024-Lab00-stZM
Example repository for Lab #0
# GOPH 419 – Computational Methods for Geophysicists
*Semester:* F2024
*Instructor:* B. Karchewski
*Author:* Zoe Mitchell

#excersize in class

b=2
x=173
p=32
list=[]

while p=>0 AND x=>0:
    x=x-(b**p)
    if x=>0:
        d=1
    else:
        d=0
    list.append(d)
    p=p-1
print(list)
