# Day-8
a=input()
b=list(map(str, input().split()))
for j in b:
    if a[0]==j[0] and a[1]==j[1]:
        print(j)
