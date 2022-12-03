# bestProject

number=int(input("Enter a number: "))

for item in range(1,2*number,2):
    print(("*"*item).center(2*number-1))

for item in range(2*number-3,0,-2):
    print(("*"*item).center(2*number-1))
    
