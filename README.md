# OddEven
# cook your dish here
t=int(input())
while t:
    a,b=map(int,input().split())
    if((a+b)%2==0):
        print("Bob")
    else:
        print("Alice")
    t-=1
    
