# Pattern
#To print numbers in a Pattern
n=int(input("Enter number of rows to be printed:"))
for i in range(1,n+1):
    for j in range(1,i+1):
        print(j, end=" ")
    print()
