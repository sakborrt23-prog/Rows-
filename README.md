 # Rows-
This is python code where input user enters number of rows and the user can view the same number of '*' as per the number of rows .
row = int(input("Enter the number of rows :"))
for i in range(1, row + 1):
    for j in range (0, i):
        print ("*", end = " ")
    print ()
