# python-codes1
. x=int(input("enter the number"))
if (x%2==0):
    print("the number is even")
else:
    print("the number is odd")
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
marks=int(input("enter your marks"))
if(marks<=500):
    percent =float(marks/500*100)
    print(percent)
    if (percent>=90 and percent <=100):
        print("o grade")
    elif (percent>=75 and percent<=89):
        print("a grade")
    elif (percent>=60 and percent<=74):
        print("b grade")
    elif (percent>=40 and percent<=59):
        print("c grade")
    else:
        print("fail")
else:
