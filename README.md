# 4.6
print("Note : 1.Red-Red, 2.Black-Black, 3.Red-Black, 4.Black-Red")
x=input("enter a digit 1/2/3/4")
if x.isdigit():
    if int(eval(x)) == 1:
        p= (4/10)*(3/9)
        print("Probability of Red-Red is : ",end='')
        print(p)
    elif int(eval(x)) == 2:
        p= (6/10)*(5/9)
        print("Probability of Red-Red is : ",end='')
        print(p)
    elif int(eval(x)) == 3:
        p= (4/10)*(6/9)
        print("Probability of Red-Red is : ",end='')
        print(p)
    elif int(eval(x)) == 4:
        p= (6/10)*(4/9)
        print("Probability of Red-Red is : ",end='')
        print(p)
    else:
        print("enter the number 1/2/3/4 only")
else:
    print("inser a number please")
