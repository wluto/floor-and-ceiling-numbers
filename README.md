#first of all you set an float input for client (also you can try diffrent outputs)

UserInput=float(input("choose a number:"))

#after that you wanna put a int before the input so it turns the float to an integer and no matter what number we put int() gonna give us the floor number

FloorNumber=int(UserInput)

#we also want a ceiling so just +1 to it 

ceilingNumber=FloorNumber+1

#now print both of them to see the output

print("floor number:" , FloorNumber)
print("ceiling number:" , ceilingNumber)

#we have approximately found the closest int to any float given to us (even the negative ones) with this code

#GoodDay
