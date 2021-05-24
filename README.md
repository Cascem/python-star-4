# python-star-4
print star pattern python(4)
import sys
n = int(sys.stdin.readline())
for i in range(n):
    for j in range(i):
        print(" ",end="")
    for j in range(n*2-1-2*i):
        print("*",end="")
    print("")
for i in range(n-1):
    for j in range(n-2-i):
        print(" ",end="")
    for j in range(3+2*i):
        print("*",end="")
    print("")
