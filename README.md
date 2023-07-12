# CompressTheVideo
# cook your dish here
t=int(input())
while t:
    x=int(input())
    a=list(map(int,input().split()))
    b=1
    for i in range (0,x-1):
        if a[i]!=a[i+1] :
            b+=1
    print(b)
    t-=1
   
