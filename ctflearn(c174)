#https://ctflearn.com/challenge/174
f = open("D:\Chrome Downloads\data.dat","r")
tcount = 0

for x in f:
    count = 0
    count1 = 0
    a = [char for char in x]
    for y in range(len(a)):
        if a[y] == "0":
            count += 1
        elif a[y] == "1":
            count1 += 1
    if count % 3 == 0 or count1 % 2 == 0:
        tcount += 1 
print(tcount)

f.close()
