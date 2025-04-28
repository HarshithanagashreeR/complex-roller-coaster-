# complex-roller-coaster-
print("welcome to the roller coaster:)")
height=int(input("enter your height"))
if height>=120:
    print("yes you can ride")
    age=int(input("enter your age?"))
    bill=0
    if age <=12:
        bill+=5
    elif age >=18:
        bill+=7
    elif age >12<18:
        bill+=12
        photo=input("do you want a photo")
        if photo == "yes":
            bill+=3
print("your total bill is : ",bill)             
