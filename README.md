("Program to print star pattern in different style: \n");
n= int(input('Please enter the number of rows:'));
for i in range (0,n):
    for j in range (n,i,-1):
        print("* ", end="")
    print("\n")
