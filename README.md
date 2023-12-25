print("Welcome to the rollercoasterride!!!")

height = int(input("What is your height in cm? : "))

bill = 0

if height >= 120:

    print("You can ride the roller coaster")
    age = int(input("what is your age? "))
    if age < 12:
        bill = 5
        print("The Child ticket is $5")
    elif age <= 18:
        bill = 7
        print("Youth ticket for $7")
    else:
        bill = 12
        print("Adult ticket for $12")

    wants_photo = input("Do you want a photo taken? Y or N? Answer = ")
    if wants_photo == "Y":
     bill +=3

    print(f"Your final bill is ${bill}")
else:
    print("Sorry, you cannot ride the roller coaster")

